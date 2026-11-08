# Agent Coordination

Use agents only when work can be divided into clear, independently verifiable responsibilities.

## Suggested sequence
1. Planner: requirements, acceptance criteria, dependencies.
2. Architect: system boundaries, data model, interfaces.
3. Specialists: frontend, backend, database, integrations.
4. Reviewer: correctness, security, accessibility, maintainability.
5. Tester: run relevant checks and report failures.
6. Integrator: reconcile changes and verify end-to-end behavior.

## Rules
- Assign file or module ownership to avoid concurrent edits.
- Provide each agent with context, constraints, expected output, and validation commands.
- Do not let multiple agents independently redesign the same interface.
- Require evidence for completion, including changed files and test results.
- The orchestrator owns integration and final verification.
