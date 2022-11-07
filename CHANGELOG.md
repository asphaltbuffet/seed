# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- FORMATTING CHEATSHEET:
## [M.m.p] - yyyy-mm-dd

### Added  - for new features.
### Changed - for changes in existing functionality.
### Deprecated - for soon-to-be removed features.
### Removed - for now removed features.
### Fixed - for any bug fixes.
### Security - in case of vulnerabilities. 

[Unreleased]: https://github.com/asphaltbuffet/seed/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/asphaltbuffet/seed/compare/v0.0.1...v1.0.0
[0.0.1]: https://github.com/asphaltbuffet/seed/releases/tag/v0.0.1
-->

## [Unreleased]

## [2.0.0] - 2022-11-07

### Added

- misspell application used for spelling localization (US vs UK)
- linters
  - dogsled
  - gochecknoinits
  - godox
  - goimports
  - maintidx
  - nakedret
  - wsl

### Changed

- matrix build now uses `latest` for all OS targets
- updated Go from 1.18 to 1.19
- coverage files now indicate OS
- CodeCov action only specifies major version
- release action now uses GitHub Container Registry
- vsCode settings layout
- makefile layout
- updates to [README](README.md)

### Removed

- Docker container for go development
- linters:
  - deadcode
  - structcheck
  - typecheck
  - varcheck
  - gci
  - gocognit
  - ifshort
  - rowserrcheck
  - sqlclosecheck
  - tparallel
  - errorlint *(already disabled)*
  - goerr113 *(already disabled)*
  - wrapcheck *(already disabled)*
- `fmt`, `release`, `dev`, `run` target in [Makefile](Makefile)

### Fixed

- spelling and grammar errors in [README](README.md)
- whitespace and other formatting

### Security

- explicit permissions for codeql analysis action
- explicit permissions for release action

## [1.0.0] - 2022-06-20

Forked from [golang-templates/seed](https://github.com/golang-templates/seed/releases/tag/v0.15.0)

### Changed

- Switched docker image from go1.16 to go1.18
- Renamed module paths to match forked repo
- Updated build directive to satisfy formatting rules `//go:build tools`
- Replace email address in the [Code of Conduct](CODE_OF_CONDUCT.md)
- Updated Code of Conduct to v2.1

[Unreleased]: https://github.com/asphaltbuffet/seed/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/asphaltbuffet/seed/releases/tag/v2.0.0
[1.0.0]: https://github.com/asphaltbuffet/seed/releases/tag/v1.0.0
