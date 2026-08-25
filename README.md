# rustdesk-build

Automated build of RustDesk desktop/mobile clients via GitHub Actions.

Source, patches and per-build configuration are provided at build time; nothing
sensitive is stored in this repository. Build tooling reuses parts of
[rdgen](https://github.com/bryangerlach/rdgen) (GPL-3.0) and the upstream
[RustDesk](https://github.com/rustdesk/rustdesk) build scripts.

## License

GPL-3.0 (see `LICENSE`), inherited from the reused RustDesk / rdgen tooling.
