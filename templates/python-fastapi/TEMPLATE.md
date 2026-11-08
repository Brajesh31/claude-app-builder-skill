# Python FastAPI Template

Use for typed Python APIs and async I/O workloads.

## Structure
- `app/main.py`: application creation
- `app/api/`: routers
- `app/schemas/`: request/response models
- `app/services/`: application logic
- `app/repositories/`: persistence adapters
- `app/core/`: configuration and security
- `tests/`: pytest suite

Use Pydantic validation, dependency injection, explicit transaction boundaries, async libraries for async routes, and bounded background work. Add health checks, migrations, and production server configuration.
