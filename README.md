# CONSENT.md

> *Defines the user consent lifecycle for AI agent actions — GDPR, CCPA, EU AI Act*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/consent.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

> **Canonical Source:** This spec is maintained in the main
> [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs) repository.
> This repo is an auto-synced mirror for easy discovery and download.
> To report issues or submit changes, please open a PR or issue on the
> [main repository](https://github.com/totalmarkdown/agent-md-specs).

## What is CONSENT.md?

CONSENT.md ensures AI agents operate with explicit, informed, and revocable user permission. It defines how consent is collected, recorded with structured evidence, verified before every consented action, and revoked at any time.

Required for any agent processing personal data under GDPR Article 7, CCPA, or EU AI Act Article 13. Organizational authority (DELEGATION.md) and user consent (CONSENT.md) are separate requirements — both must be satisfied for lawful operation.

Create a CONSENT.md for any agent that processes personal data, interacts with end users in privacy-regulated jurisdictions, or shares user data across multi-agent systems.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/consent.md/main/CONSENT.md
```

Add to your project root and customize for your agent.

---

## When to use CONSENT.md

- Agents processing personal data in any jurisdiction with privacy laws
- Healthcare agents handling patient information (HIPAA authorization)
- Multi-agent systems where user data flows between agents via shared context

---

## Where it fits

Works alongside DELEGATION.md (organizational authority — separate from user consent), PRIVACY.md and PII.md (data handling after consent), AUDITTRAIL.md (consent changes logged), SHAREDCONTEXT.md (consent scope must cover all agents sharing data), and GDPR.md / CCPA.md / EUAIACT.md (regulatory requirements).

---

## The Full Spec

→ [CONSENT.md](./CONSENT.md)

---

## Part of agent-md-specs

One of 178 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
