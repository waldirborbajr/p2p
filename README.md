
## Add dependency

```
cargo add serde --features derive
cargo add serde_json
```

## Execute

```
cargo run --quiet -- 8081
cargo run --quiet -- 8082 0.0.0.0:8081
cargo run --quiet -- 8083 0.0.0.0:8081 0.0.0.0:8082
```
