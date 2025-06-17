# MySQL Server + MySQL Workbench (Docker Compose)

A minimal Docker Compose setup for running MySQL 8.0 and MySQL Workbench. Suitable for local development, for example.

## Images

More information about the images can be found on the images' pages:

- [**MySQL Server**](https://hub.docker.com/_/mysql)
- [**MySQL Workbench (GUI)**](https://hub.docker.com/r/linuxserver/mysql-workbench)

## Notes

- Credentials are managed via a `.env` file (not included in this repo).
- MySQL data is persisted by default using a local volume (`./data`).

