# SigmaOS-hibernation

Hibernation/suspend-to-disk management: power states, hibernation images, resume

- **Category:** System Services
- **Engine:** hibernation
- **Tier:** 2
- **Language:** Rust
- **Provides:** sigmahibernation

Part of the [SigmaOS](https://github.com/AaryanSinghChauhan09/SigmaOS)
multi-repository component ecosystem.

## Build & Test

```sh
cargo build
cargo test
```

## Contract

This component declares its interface in `COMPONENT.toml`:

- `provides` — capabilities other components may depend on
- `depends_on` — component names this component requires

## License

Apache-2.0 — see [LICENSE](LICENSE).
