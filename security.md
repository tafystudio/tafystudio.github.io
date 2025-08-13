---
title: Security
layout: default
permalink: /security/
---

# Security

- **Auth:** OIDC (JWT). Local accounts optional for labs.
- **Device creds:** NATS **NKey/JWT** per device; `.creds` files with nonce-signed auth.
- **Transport:** TLS everywhere. mTLS mesh added post-MVP.
- **Scopes/Roles:** admin, operator, viewer. Workspaces isolate projects.
- **Report a vulnerability:** security@tafy.studio (PGP: pending)
