# Publish the Swift SDK from the main Optimization monorepo

- Status: Accepted
- Scope: Optimization Swift SDK

## Context

The public Swift package must be consumable through Swift Package Manager while remaining synchronized with the cross-platform SDK suite.

## Decision

Treat this repository as a generated release destination and keep authoritative source changes in contentful/optimization.

## Consequences

Contributors validate the generated package here but make feature fixes in the source monorepo and allow the release workflow to update this repository.

