# Turborepo Monorepo Template

Use when multiple applications and packages share code and coordinated tooling.

## Suggested structure
- `apps/`: deployable applications
- `packages/`: shared libraries and configuration
- `turbo.json`: task graph and cache configuration
- Root package manifest and lockfile

Define package ownership, dependency direction, task inputs/outputs, environment variable passthrough, and CI caching. Keep shared packages focused and avoid coupling every app to a common runtime package.
