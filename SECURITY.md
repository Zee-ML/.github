# Security & Privacy Policy

## Local-First & Deterministic Security Architecture

All open-source extensions, IDE plugins, CLI packages, and web utilities maintained by **ZeeML** ([https://zeeml.com](https://zeeml.com)) are engineered around strict least-privilege and local-first execution principles:

- **Browser Extensions (Manifest V3 / WebExtension):** Request only minimal active-tab or context-menu scopes required for user-triggered actions (`activeTab`, `contextMenus`, `clipboardWrite`). No background browsing history collection or third-party ad-tracker injection is ever permitted.
- **Zero-Dependency SDKs & CLI Utilities:** Core packages (`@zeeml/*`, `zeeml-*`) operate deterministically on local memory buffers without unsolicited telemetry calls.
- **Web Workbenches (`zeeml.com`):** Full details on our browser-local and ephemeral processing guarantees are published at [https://zeeml.com/privacy](https://zeeml.com/privacy) and [https://zeeml.com/about](https://zeeml.com/about).

## Supported Versions

| Release Track | Security Updates |
| :--- | :--- |
| `1.x` (Current Stable) | ✅ Actively supported |
| `< 1.0` (Pre-release) | ❌ Upgrade to latest `1.x` release |

## Reporting a Vulnerability

If you discover a security vulnerability in any `@Zee-ML` repository, extension, or web utility:

1. **Do not open a public GitHub issue** containing live exploit payloads.
2. Submit a private report via GitHub Security Advisories on the respective repository or reach out through the official contact channels listed on [https://zeeml.com/about](https://zeeml.com/about).
3. Include minimal reproduction steps, affected package/extension version, and environment details. We acknowledge valid reports within 48 hours.
