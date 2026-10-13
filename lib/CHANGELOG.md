# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.1](https://github.com/Techie-Tenka/elonaire-axum-rs/compare/v0.2.0...v0.2.1) - 2026-10-13

### Fixed

- Rollout tweaks ([#277](https://github.com/Techie-Tenka/elonaire-axum-rs/pull/277))

## [0.2.0](https://github.com/Techie-Tenka/elonaire-axum-rs/compare/v0.1.2...v0.2.0) - 2026-10-11

### Added

- [**breaking**] bump feature version ([#274](https://github.com/Techie-Tenka/elonaire-axum-rs/pull/274))

## [0.1.2](https://github.com/Techie-Tenka/elonaire-axum-rs/compare/v0.1.1...v0.1.2) - 2026-10-11

### Added

- bump feature version

## [0.1.1](https://github.com/Techie-Tenka/elonaire-axum-rs/compare/v0.1.0...v0.1.1) - 2026-10-11

### Other

- Rollout tweaks ([#268](https://github.com/Techie-Tenka/elonaire-axum-rs/pull/268))
- Rollout tweaks ([#266](https://github.com/Techie-Tenka/elonaire-axum-rs/pull/266))
- Rollout tweaks ([#264](https://github.com/Techie-Tenka/elonaire-axum-rs/pull/264))
- Rollout tweaks ([#262](https://github.com/Techie-Tenka/elonaire-axum-rs/pull/262))

## [0.1.0](https://github.com/Techie-Tenka/elonaire-axum-rs/releases/tag/v0.1.0) - 2026-10-11

### Added

- crate upgrades + new CI workflow

### Fixed

- fix status_code in errors to be a string to fit GraphQL Hashmap

### Other

- rectify blog creation bug
- Update email protobuf - but...
- Surreal upgrades - to v3
- Remove redundant privilege check
- traefik tweaks
- harmonize errors
- service request logic + new hardened Traefik middlewares
- rebuild
- Tighten permission handling
- Manage crates centrally
- Harmonize API response structure - working for GraphQL
- fetch service rates resolver
- Some good progress on Service Rates and Service Request
- Debug middlware due to the context object AuthStatus
- Tighten permission constraints
- refactor DB to make public resources independent of user and add auth
- refactor DB to remove ambiguos relationships + simplify metadata addition
- refactor to seperate input objects for GraphQL + conform to GRPC standards
- update protos
- Cross check any probable panics that may cause broken pipes
- getting rid of unwraps in my code
- rename gRPC methods
- rectify longstanding gRPC OUT_DIR issue
- improve error handling
- Improve table relationships - use recommended conventions
- Add gRPC support for external reusable services
- Crate upgrades
- update SurrealDB
- upgrade to SurrealV2 and also latest Axum
- update pipelines and rustc
- services updates
