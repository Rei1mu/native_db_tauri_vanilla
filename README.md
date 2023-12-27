# Native DB + Tauri + Vanilla

This is a simple example of a Tauri app using a [`native_db`](https://github.com/vincent-herlemont/native_db).

Key points:
- Define an api: 1 model `Persone` with 2 versions, *source [main.rs#L9-L43](https://github.com/vincent-herlemont/native_db_tauri_vanilla/blob/0c0e43a7b96ca54aef3a69e4006bff087a030f30/src-tauri/src/main.rs#L9-L43)*.
- Use `native_db` as a [Tauri managed state](https://tauri.app/v1/guides/features/command/#accessing-managed-state), *source [main.rs#L57-L76](https://github.com/vincent-herlemont/native_db_tauri_vanilla/blob/0c0e43a7b96ca54aef3a69e4006bff087a030f30/src-tauri/src/main.rs#L57-L76)*.
- Migrate the database during the app setup, *source [main.rs#L94-L101](https://github.com/vincent-herlemont/native_db_tauri_vanilla/blob/0c0e43a7b96ca54aef3a69e4006bff087a030f30/src-tauri/src/main.rs#L94-L101)*.