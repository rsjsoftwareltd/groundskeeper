# Security Policy

## Supported versions

Groundskeeper is a self-hosted, single-release-line product -- there is
no long-term-support branch. Security fixes are made against the current
release line only. Please always run the latest published release
(check General Settings -> About, or `GET /api/version`, inside the app)
before reporting an issue, in case it is already fixed.

## Reporting a vulnerability

If you believe you have found a security vulnerability in Groundskeeper
(the server application, the GKAgent endpoint agent, the Cloudflare
Worker licensing backend, or the installer), please report it privately
rather than opening a public GitHub issue or discussing it publicly.

**Email: security@rsjsoftware.com**

Please include as much of the following as you can:

- A description of the vulnerability and its potential impact.
- Steps to reproduce, or a proof of concept.
- The affected version (`GET /api/version`, or General Settings -> About).
- Any suggested mitigation, if you have one.

### What to expect

- We aim to acknowledge your report within **3 working days**.
- We will keep you informed as we investigate and work on a fix.
- We ask that you give us a reasonable window to develop and release a
  fix before any public disclosure, and that you avoid accessing,
  modifying, or exfiltrating data beyond what is strictly necessary to
  demonstrate the issue.
- Good-faith security research conducted under this policy will not
  result in legal action from us.

### Scope

In scope: the Groundskeeper server application, the GKAgent endpoint
agent, the Cloudflare Worker that issues and verifies licence keys
(`api.rsjsoftware.com`), and the Windows installer.

Out of scope: third-party services Groundskeeper integrates with (e.g.
Microsoft 365, Meraki, individual school infrastructure) -- please
report those to the relevant vendor.

### Bug bounty

We do not currently operate a paid bug bounty programme. We are
genuinely grateful for responsible disclosures and will credit
reporters (with permission) in release notes where appropriate, but we
want to be upfront that there is no monetary reward on offer at this
time, so there's no unstated expectation either way.

---

RSJ Software -- Groundskeeper is a self-hosted, GDPR-friendly IT
operations platform for UK schools and Multi-Academy Trusts. School
data never leaves the school network without explicit configuration.
