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

Based on GitHub Actions (typescript-action)[https://github.com/actions-rs/core/tree/1b3bf36903648e0f2db0286ede1348abbac16f60] template, licensed under the MIT license.

