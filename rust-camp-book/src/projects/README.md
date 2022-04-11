# Rust Projects

A curated list of projects at Camptocamp where Rust is used.

## Abbreviator

[Abbreviator](https://github.com/camptocamp/abbreviator) is a URL Shortener with a `SQLite` database and is based on [Tide](https://github.com/http-rs/tide) and [sqlx](https://github.com/launchbadge/sqlx) leveraging the `async-std` runtime.

It features basic Rust CI, configuration through environment variables, CORS and a minimal Docker image.

## OGC API
The [ogcapi](https://github.com/camptocamp/ogcapi) project is an ongoing impementation of various [OGC API standards](https://ogcapi.ogc.org/).

It features comprehensive `type definitions`, a server implementation for collections, features, tiles and styles, a `PostgreSQL` driver and vector data import leveraging gdal.

## Swissgeol Viewer

The [Swissgeol Viewer](https://github.com/swissgeol/ngm) has a api written in Rust with a `PostgreSQL` database and is based on [axum](https://github.com/tokio-rs/axum) and [sqlx](https://github.com/launchbadge/sqlx) leveraging the `tokio` runtime.

Some key features include `Json Web Token` authorization, `Amazon S3` integration through [aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust), reversible database migrations and a local development environment base on `Docker Compose`.
