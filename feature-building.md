# Feature Building

Implement features as complete user workflows, not disconnected UI fragments.

## Process
1. Clarify user value and acceptance criteria.
2. Trace the existing architecture and reuse established patterns.
3. Define data, API, validation, authorization, and error states.
4. Implement the smallest vertical slice.
5. Add tests for success, invalid input, permission failures, and edge cases.
6. Verify responsive behavior, accessibility, and loading/empty/error states.
7. Update documentation and migration notes.

## Existing projects
Inspect before editing. Avoid replacing frameworks, routing, state management, or styling systems without an explicit reason. Keep changes scoped and backward-compatible where possible.
