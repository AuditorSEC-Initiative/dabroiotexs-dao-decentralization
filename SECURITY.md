# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| main (latest) | :white_check_mark: |
| Older tags | :x: |

## Reporting a Vulnerability

**Please do NOT open a public GitHub issue for security vulnerabilities.**

Instead, report security issues via one of the following channels:

1. **GitHub Private Security Advisory** (preferred):
   - Go to [Security Advisories](https://github.com/AuditorSEC-Initiative/dabroiotexs-dao-decentralization/security/advisories/new)
   - Click "New draft security advisory"
   - Provide a detailed description

2. **Email:** security@auditorsec.org  
   - Subject: `[SECURITY] dabroiotexs-dao-decentralization - <brief title>`
   - Include: affected version, steps to reproduce, potential impact
   - PGP key available at [auditorsec.org/pgp](https://auditorsec.org/pgp)

## Response Timeline

| Step | Target Time |
|------|-------------|
| Initial acknowledgement | 48 hours |
| Triage & severity assessment | 5 business days |
| Fix development | 14–30 days (severity dependent) |
| Coordinated disclosure | 90 days after report |

## Smart Contract Security

This repository contains IoTeX smart contracts. Additional security considerations:

- All contracts should be audited before mainnet deployment.
- Known audits are listed in `docs/audits/` (once available).
- Bug bounty program details: TBD (will be published at launch).

## Scope

**In scope:**
- Smart contract vulnerabilities (reentrancy, integer overflow, access control)
- Governance attack vectors (flash loan attacks, proposal manipulation)
- Treasury draining exploits
- On-chain oracle manipulation

**Out of scope:**
- Third-party dependencies (report directly to upstream maintainers)
- Issues in test/example code not deployed on mainnet
- Social engineering attacks

## Disclosure Policy

We follow responsible disclosure. We will:
- Acknowledge your report promptly.
- Keep you informed throughout the fix process.
- Credit you in the security advisory (unless you prefer anonymity).
- Not take legal action against good-faith security researchers.

---

*Security policy maintained by AuditorSEC Initiative. Last updated: 2025.*
