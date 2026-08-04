# Release Process

[Instructions](https://contribute.cncf.io/maintainers/community/release-management/)

<!-- template begins here -->

This document describes the release process for [TODO: PROJECTNAME].

## Release Cadence

<!-- TODO: Choose one -->

[TODO: PROJECTNAME] follows a [time-based / feature-based] release cadence. Releases are made approximately every [TODO: frequency, e.g. 6 weeks, quarterly].

## Versioning

[TODO: PROJECTNAME] follows [Semantic Versioning](https://semver.org/):

* **Major (X.0.0):** Incompatible API changes
* **Minor (x.Y.0):** New functionality, backwards compatible
* **Patch (x.y.Z):** Bug fixes, backwards compatible

## Release Types

| Type | Description | Example |
| ---- | ----------- | ------- |
| Stable | Production-ready releases | v1.2.0 |
| Pre-release | Release candidates and betas | v1.3.0-rc.1 |
| Security | Patches for security vulnerabilities | v1.2.1 |

## Branch Strategy

<!-- TODO: Describe your branching model -->

* `main` - Development branch for the next release
* `release-x.y` - Maintenance branches for supported releases

## Supported Versions

<!-- TODO: Define your support policy -->

[TODO: PROJECTNAME] maintains support for the most recent **[TODO: Number]** minor releases. Security patches are backported to all supported versions.

| Version | Status |
| ------- | ------ |
| x.y     | Active |
| x.y-1   | Maintenance |

## Release Artifacts

Each release includes:

<!-- TODO: Check all that apply and add project-specific artifacts -->

* Source code archives (tar.gz, zip)
* Container images published to [TODO: registry, e.g. ghcr.io/org/project]
* Binary releases for [TODO: platforms, e.g. linux/amd64, linux/arm64, darwin/amd64]
* Checksums file (SHA256)
* [TODO: Signed releases / SBOM / other artifacts]

## Creating a Release

<!-- TODO: Document the steps your project follows to create a release -->

1. [TODO: List the release steps]

## Release Roles

Release management is handled by the project maintainers. See [GOVERNANCE.md](GOVERNANCE.md) for how release responsibilities are assigned.
