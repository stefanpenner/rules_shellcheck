# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

This document is maintaining changes since the last released version (0.1.1)

## Unreleased

### Changed

Breaking changes:

* Rename the workspace and module from `com_aignas_com_rules_shellcheck` to
  `rules_shellcheck` so that a migration to `bazel-contrib` or somewhere else
  could be possible at some point.

### Fixed

* Add a missing `sha256` to the `README`.

### Added

* Bump shellcheck to `0.9.0`.
* Add `severity` and `format` attributes.