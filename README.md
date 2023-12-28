# Native DB + Tauri + Vanilla

This is a simple example of a Tauri app using a [`native_db`](https://github.com/vincent-herlemont/native_db).

Key points:
- Define an api: 1 model `Person` with 2 versions, *source [main.rs#L10-L43](https://github.com/vincent-herlemont/native_db_tauri_vanilla/blob/7787ed7c02083274abeecd3aa483b9a33bddc165/src-tauri/src/main.rs#L10-L43)*.
- Use `native_db` as a [Tauri managed state](https://tauri.app/v1/guides/features/command/#accessing-managed-state), *source [main.rs#L93-L95](https://github.com/vincent-herlemont/native_db_tauri_vanilla/blob/7787ed7c02083274abeecd3aa483b9a33bddc165/src-tauri/src/main.rs#L93-L95)*.
- Migrate the database during the app setup, *source [main.rs#L87-L91](https://github.com/vincent-herlemont/native_db_tauri_vanilla/blob/7787ed7c02083274abeecd3aa483b9a33bddc165/src-tauri/src/main.rs#L87-L91)*.