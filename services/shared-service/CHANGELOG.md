# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0](https://github.com/Techie-Tenka/elonaire-axum-rs/releases/tag/v0.1.0) - 2026-10-11

### Added

- crate upgrades + new CI workflow

### Fixed

- fix ratecard bug + update billing rate table view
- fix Service Request submission
- fix blog post query
- fix a little typo
- Share and bookmarks
- Share and bookmarks
- Reaction count and current user reaction
- fix status_code in errors to be a string to fit GraphQL Hashmap
- fix bug on get_blog_posts query
- fix update blog post resolver
- fix resolver errors
- fix blog comments

### Other

- Fix blog reaction bug
- Fix request service bug
- Support non-browser clients, upgrade crates, add argocd
- Fix transaction update-related bugs
- Remove some code smell
- Fix blog posts query bug
- Enhance full-text search and filters
- rectify blog creation bug
- Remove migrations
- Rename conflicting 'type' props
- Surreal upgrades - to v3
- Remove redundant privilege check
- service request logic + new hardened Traefik middlewares
- sort resume on backend
- Tighten permission handling
- Improve error handling
- Search feature for blog posts
- Update broker and surrealist manifest + liveness and readiness
- Configurable burst sizes
- Manage crates centrally
- React to blog comment
- Share and bookmarks
- Reaction count and current user reaction
- complete working syntax highlighting
- Basic syntax highlighting
- Read minutes
- Safe to say MVP done
- Harmonize API response structure - working for GraphQL
- Fetch service requests
- Fix ratecard creation query bug
- fetch service rates resolver
- Normalize rates
- Add description to skills
- rectify resume submission issue and in the UI achievements field
- create service requests, create ratecard, fetch billing rates, create service rate
- Some good progress on Service Rates and Service Request
- Debug middlware due to the context object AuthStatus
- Tighten permission constraints
- rectify fetch resolvers for public resources
- refactor DB to make public resources independent of user and add auth
- refactor DB to remove ambiguos relationships + simplify metadata addition
- refactor to seperate input objects for GraphQL + conform to GRPC standards
- update content file logic for blog post creation + database update
- remove other_files from blog_post
- include Resume Item achievements
- Rename resolvers
- API return values updates + enforce_single_true debug
- Rectify Reaction type enum
- refactor blog content logic to own resolver and enforce thumbnails as urls
- Do away with OVERWRITES in DB schema
- Cross check any probable panics that may cause broken pipes
- rectify schema date types and improve error handling
- getting rid of unwraps in my code
- rename gRPC methods
- rectify longstanding gRPC OUT_DIR issue
- improve error handling
- simplify UserResources query and remove some redundant resolvers
- rectify some naming conventions
- Improve table relationships using appropriate models, fix blog content fetch; now using internal files service
- Improve table relationships - use recommended conventions
- Improve schema definitions - remove any unintended flexible types
- Improve schema definitions and also, assertions and also use internal files
- Add gRPC support for external reusable services
- Crate upgrades
- optimize SurrealDB queries and update RELATION tables
- update SurrealDB
- upgrade to SurrealV2 and also latest Axum
- Fix typo in SQL query for updating blog post flags
- add featured and premium blogs
- some serious mistake I did
- link skills to portfolio
- get message endpoint
- remove blank id quickfix
- actually add to docker compose, my bad
- hope it works
- make id optional
- trick Nginx
- oh no another edge case
- add suggestion to message
- code cleanup + remove AWS
- don't commit posts
- prod configs
- stable backend
- Finished frontend major needs including optimization
- some more features - sorry I did a lot can't remember which
- Refactor edge tables to have generic records to simplify complex queries for related data
- Finished basic CRUD
- CRUD for shared service + refactor for DRY code
- add professional details
- update pipelines and rustc
- services updates
