# zero2prod

Code developed following the book [Zero To Production In Rust](https://www.lpalmieri.com/posts/2020-05-24-zero-to-production-0-foreword/).

## Important

Install [SQLx CLI](https://crates.io/crates/sqlx-cli) to manage migrations:
>cargo install sqlx-cli --no-default-features --features postgres

Remember to add your user to `docker` group:
>sudo usermod -a -G docker USERNAME
