# Groundskeeper

**Self-hosted IT operations intelligence for UK schools and Multi-Academy Trusts.**

Groundskeeper runs on your own Windows Server, pulls data from 26 connectors covering the tools schools already use, and surfaces what needs attention — without anything leaving your network.

🔗 **[groundskeeper.ejjsoftware.com](https://groundskeeper.ejjsoftware.com)**

---

## What it does

- **Single event feed** — infrastructure health, security events, and school system status in one place. Issues only, no noise.
- **Domain Security** — SPF, DMARC, DKIM, MX, TLS, HTTPS headers, change detection. Replaces NCSC Mail Check and Web Check (retired 31 March 2026).
- **Cyber Essentials dashboard** — RAG status across all five CE controls, populated from live connector data.
- **GKAgent** — lightweight PowerShell agent deployed via GPO or Action1 for Windows client visibility: BitLocker, Defender, Windows Update compliance, local admin audit, SMART disk health, and more.
- **SLT view** — read-only traffic-light dashboard for senior leadership. No jargon.
- **AI assistant** — morning briefings, alert explanations, and plain-English summaries. Runs locally via Ollama (no data leaves your network) or via a cloud provider of your choice.

## 26 connectors

**Cloud & SaaS:** Meraki, Action1, M365 Service Health, M365 Licences, Veeam, MIS Status (Bromcom/Arbor/SIMS/SEEMiS), School Services (16 UK services)

**Security:** Domain Security, WatchGuard Firebox, WatchGuard Endpoint, SSL Cert Monitor

**Infrastructure:** Windows Server, Windows Clients (GKAgent), Hyper-V, Active Directory, AD Account Health, Windows Event Log, DNS/DHCP, Internet Health, Endpoint Reports, Devices Left On Overnight, Exam Marking Software

**Hardware:** HP/Aruba Switches (SNMP), UPS (SNMP), Dell iDRAC, Printers/MFDs (SNMP)

---

## Why self-hosted

- **Your data stays on your network.** No cloud subscription, no third party seeing your infrastructure details.
- **Read-only by design** — Groundskeeper observes and reports. It never modifies anything on connected systems.
- **GDPR-friendly by default** — nothing leaves school unless you choose a cloud AI provider.

---

## Getting started

- **Download** the Windows installer from the [Releases](../../releases) page — bundles everything, no Python required
- **Documentation** — [Wiki](../../wiki) for setup guides, connector configuration, and FAQs
- **Community key** — request a free Community key through the dashboard on first run
- **Website** — [groundskeeper.ejjsoftware.com](https://groundskeeper.ejjsoftware.com)
- **Discussions** — questions and community support in [Discussions](../../discussions)

## Pricing

| Edition | Price | Connectors |
|---|---|---|
| Community | Free | 5 (your choice) |
| Pro | £249/yr per school | Unlimited |
| Central | £499/yr per group | Unlimited + group hub-and-spoke dashboard |

Community keys are free and renewed annually. Request one through the dashboard.

---

## About

Groundskeeper is built by **EJJ Software**, founded by two school IT professionals, for the school IT community.

- Privacy notice: [groundskeeper.ejjsoftware.com/privacy](https://groundskeeper.ejjsoftware.com/privacy)
- Website: [ejjsoftware.com](https://ejjsoftware.com)
- Reporting security issues: see [SECURITY.md](SECURITY.md)

## Licence

© EJJ Software. All rights reserved.

This repository is provided for transparency, release distribution, and community support. No licence is granted for reuse, modification, or redistribution of the source code.
