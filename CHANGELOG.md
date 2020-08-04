# Changelog

## [0.2.0] - 2020-08-04Z

### Changed

- Splitted the `download` command into `new`, `open`, and `download`. ([#3](https://github.com/qryxip/cargo-compete/pull/3))
- Renamed `workspace-metadata.toml` to `compete.toml`. ([#7](https://github.com/qryxip/cargo-compete/pull/7))
    - Now `test-suite`s are [Liquid](https://shopify.github.io/liquid/) templates.  ([#4](https://github.com/qryxip/cargo-compete/pull/4))
    - Now `open`s are [jq](https://github.com/stedolan/jq) commands. ([#5](https://github.com/qryxip/cargo-compete/pull/5))
    - Renamed `template.code` to `template.src`.  ([#8](https://github.com/qryxip/cargo-compete/pull/8))
    - Now `template.manifest` instead of `template.dependencies` is used for each `Cargo.toml`.  ([#8](https://github.com/qryxip/cargo-compete/pull/8))

### Fixed

- Fixed `package.repository` of this package. ([#2](https://github.com/qryxip/cargo-compete/pull/3))