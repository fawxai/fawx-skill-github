# Github Skill

WASM skill plugin for [Fawx](https://github.com/fawxai/fawx).

## Install

```bash
fawx skill install fawxai/github
```

## Build from Source

```bash
cargo build --release --target wasm32-unknown-unknown
fawx skill install ./target/wasm32-unknown-unknown/release/github_skill.wasm
```

## License

Apache 2.0
