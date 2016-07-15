# gauge-rust

Rust language plugin for Gauge

**Status: Work-in-progress/Incomplete**

# Develop

## Build

```sh
$ cargo build --release
```

## Install plugin locally

Create package file and install with `gauge`:

```sh
$ sh scripts/package.sh
$ gauge --install rust --file deploy/gauge-rs-<version>-<platform>.<arch>.zip
```

Or, Install package directly:

```sh
$ sh scripts/install.sh
```
