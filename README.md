# Getting Started

## Initializing a new project
```shell
cargo new --lib diesel_demo
cd diesel_demo
```

## Installing Diesel CLI
```shell
cargo install diesel_cli --no-default-features --features postgres
```

## Initializing diesel
```shell
echo DATABASE_URL=postgres://username:password@localhost/diesel_demo > .env
```

```shell
diesel setup
diesel migration generate create_posts
diesel migration run
# diesel migration redo
```

# show_posts
```shell
cargo run --bin show_posts
```

# write_post
```shell
cargo run --bin write_post
```

# publish_post
```shell
cargo run --bin publish_post 1
```

# show_posts
```shell
cargo run --bin delete_post test
```
