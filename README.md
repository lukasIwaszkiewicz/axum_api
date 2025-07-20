# Rust Axum REST API

*Following [Rust Axum REST API](https://www.rustfinity.com/blog/create-high-performance-rest-api-with-rust)*

This project sets up a basic REST API using the Axum framework in Rust, with SQLx for database interactions.


## Database Setup

### Features

- PostgreSQL is used as the database backend.
- The `sqlx` crate is included for asynchronous database operations.
- The `tokio` runtime is used for asynchronous programming.
- Native TLS support is enabled for secure database connections.

### Create a database

To create the PostgreSQL database, you can use the following command:

```ps1
    sqlx database create --name rust-axum-rest-api
```

Create user table

```ps1
   sqlx migrate add create_users_table
```
