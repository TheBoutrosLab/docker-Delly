# Changelog

All notable changes to the Delly Docker file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2026-05-18

### Changed

- Update Delly `v1.7.3` to `v2.0.0`

## [1.7.3] - 2026-04-16

### Added

- Add release automation workflows for prepare, finalize, and alias tags
- Add `dependabot.yml` for weekly dependency and GitHub Actions updates

### Changed

- Update Delly `v1.5.0` to `v1.7.3`
- Update Miniforge version to `v26.1.1-2`
- Update Ubuntu version to `v24.04`
- Replace `condaforge/mambaforge` with `condaforge/miniforge3`

## [1.5.0] - 2025-07-30

### Changed

- Update Delly `v1.3.3` to `v1.5.0`
- Update miniforge version to `v24.9.2-0`
- Update Ubuntu version to `v25.04`

## [1.3.3] - 2025-01-17

### Changed

- Update Delly `v1.3.2` to `v1.3.3`

## [1.3.2] - 2025-01-16

### Changed

- Update Delly `v1.3.1` to `v1.3.2`

## [1.3.1] - 2025-01-15

### Changed

- Update Delly `v1.2.9` to `v1.3.1`
- Update Ubuntu `v24.04`

## [1.2.9] - 2024-09-25

### Changed

- Update Delly `v1.2.8` to `v1.2.9`

## [1.2.8] - 2024-09-24

### Changed

- Update Delly `v1.2.6` to `v1.2.8`

## [1.2.6] - 2023-12-22

### Changed

- Update Delly `v1.1.7` to `v1.2.6`

## [1.1.7] - 2023-10-04

### Added

- Add `Discussions` and `Contributors` to `README.md`
- Add image source link to `LABEL`
- Add `condaforge/mambaforge` as builder

### Changed

- Update Delly `v1.1.5` to `v1.1.7`
- Update Ubuntu `v20.04` to `v23.04`

### Removed

- Remove `blcdsdockerregistry/bl-base` as builder

## [1.1.5] - 2022-10-24

### Added

- Add `Docker-build-release.yaml` to the repo

### Changed

- Update Delly v1.1.5 in Dockerfile
- Update `.gitignore` file

## [1.1.3] - 2022-08-03

### Changed

- Replace `conda` with `mamba` in Dockerfile based on the BL Docker Template
- Update Delly v1.1.3 in Dockerfile

## [1.0.3] - 2022-06-27

### Added

- Add 'bldocker' as user in the Dockerfile to avoid using root as default

### Changed

- Upgrade Delly version from 0.9.1 to 1.0.3

## [0.9.1] - 2021-12-06

### Added

- Add docker PR template
- Add GPL2

### Changed

- Upgrade Delly version from 0.8.7 to 0.9.1
- Upgrade blcdsdockerregistry/bl-base from 1.0.0 to 1.1.0

## [0.8.7] - 2021-04-29

### Added

- Migrate Delly dockerfile to its own repository

[0.8.7]: https://github.com/TheBoutrosLab/docker-Delly/releases/tag/v0.8.7
[0.9.1]: https://github.com/TheBoutrosLab/docker-Delly/compare/v0.8.7...v0.9.1
[1.0.3]: https://github.com/TheBoutrosLab/docker-Delly/compare/v0.9.1...v1.0.3
[1.1.3]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.0.3...v1.1.3
[1.1.5]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.1.3...v1.1.5
[1.1.7]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.1.5...v1.1.7
[1.2.6]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.1.7...v1.2.6
[1.2.8]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.2.6...v1.2.8
[1.2.9]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.2.8...v1.2.9
[1.3.1]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.2.9...v1.3.1
[1.3.2]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.3.1...v1.3.2
[1.3.3]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.3.2...v1.3.3
[1.5.0]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.3.3...v1.5.0
[1.7.3]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.5.0...v1.7.3
[2.0.0]: https://github.com/TheBoutrosLab/docker-Delly/compare/v1.7.3...v2.0.0
