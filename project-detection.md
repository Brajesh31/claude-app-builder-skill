# Project Type Detection

Classify the request before choosing a stack. Ask only for missing information that changes the architecture.

## Signals
- Content site, docs, marketing pages: static or hybrid web.
- Authenticated product with workflows and persistence: full-stack application.
- Data ingestion, model inference, automation: backend service or worker.
- Offline-first or device-native capabilities: mobile or desktop application.
- Small repeatable task with CLI inputs/outputs: command-line tool.
- Browser interaction or page augmentation: browser extension.

## Discovery checklist
Identify users, primary workflows, data sensitivity, integrations, expected scale, latency, availability, deployment target, team experience, budget, and deadline.

## Output
State the project type, key assumptions, non-goals, and the reason the chosen architecture fits. Do not infer payment, analytics, authentication, or admin features unless requested or required.
