<p align="center">
  <a href="https://github.com/foresterre/action"><img alt="action status" src="https://github.com/foresterre/action/workflows/build-test/badge.svg"></a>
</p>

# Cargo Publish Action

Intent:

- [ ] check version of package in `Cargo.toml` (at the root of the repo) against crates.io version `iff publish = true`
    - [ ] allow specifying custom `Cargo.toml` location
    - [ ] validate semver version is newer
- [ ] add `cargo publish` support for newer versions
- [ ] Add support for workspaces

### Acknowledgements

Based on GitHub Actions [typescript-action](https://github.com/actions/typescript-action) template, licensed under the MIT license.

