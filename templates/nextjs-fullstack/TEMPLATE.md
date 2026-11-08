# Next.js Full-Stack Template

Use for a web product needing server rendering, authenticated workflows, and persistent data.

## Suggested structure
- `app/`: routes and layouts
- `components/`: reusable UI
- `lib/`: auth, validation, database, integrations
- `server/`: server-only application logic
- `prisma/` or `db/`: schema and migrations
- `tests/`: unit and integration tests

## Build order
1. Define domain entities and authorization rules.
2. Configure database and migrations.
3. Implement server-side validation and service layer.
4. Add authentication and protected routes.
5. Build accessible UI states.
6. Add integration tests and deployment checks.

Keep secrets server-side. Do not expose database clients or privileged tokens to browser bundles.
