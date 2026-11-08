# Chrome Extension Template

Use for browser extensions targeting Manifest V3.

## Components
- `manifest.json`: permissions and entry points
- Service worker: background events
- Content scripts: scoped page integration
- Popup/options pages: user interface
- Storage: minimal persisted settings

Request the smallest permissions possible. Treat page content and messages as untrusted. Validate message senders and payloads, avoid remote hosted executable code, and test lifecycle behavior when the service worker is suspended.
