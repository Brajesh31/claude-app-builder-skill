# Electron Desktop Template

Use for desktop applications requiring web UI with native operating-system integration.

## Process boundaries
- Main process owns privileged APIs and lifecycle.
- Renderer process owns UI.
- Preload exposes a narrow, typed bridge.
- Never expose unrestricted Node.js APIs to untrusted renderer content.

Enable context isolation and sandboxing, validate IPC payloads, restrict navigation and remote content, sign packages, and test auto-update and installer behavior.
