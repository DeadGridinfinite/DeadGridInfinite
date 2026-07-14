# Security Policy

## Supported Versions

This project is a single static HTML file with no server-side component and
no external runtime dependencies. The latest commit on `main` is always the
supported version.

| Version | Supported |
| ------- | --------- |
| main    | ✅ |

## Reporting a Vulnerability

Since Dead Grid: Infinite Night runs entirely client-side in the browser with
no backend, no user accounts, and no data collection beyond a local high
score stored in `localStorage`, the attack surface is minimal. If you still
discover a security issue (e.g. a way to inject malicious content through the
game), please:

1. Open a [private security advisory](../../security/advisories/new) if enabled, **or**
2. Open an issue with the `security` label, avoiding public disclosure of exploit details until it's addressed.

We'll do our best to respond within a few days.
