# Rust Axum REST API

# This project sets up a basic REST API using the Axum framework in Rust, with SQLx for database interactions.

## Database Setup

### Features

- PostgreSQL is used as the database backend.
- The `sqlx` crate is included for asynchronous database operations.
- The `tokio` runtime is used for asynchronous programming.
- Native TLS support is enabled for secure database connections.

### Create a database

To create the PostgreSQL database, you can use the following command:

```bash
sqlx database create --name rust-axum-rest-api
```
