# Groundskeeper

**Self-hosted IT monitoring for UK schools and multi-academy trusts.**

Groundskeeper runs on a Windows Server in your school. It connects to the systems you
already use -- your network, servers, backups, Microsoft 365, security tools and school
services -- and shows you what needs attention in one feed. Nothing leaves your network
unless you choose a cloud AI provider.

**Website:** [groundskeeper.rsjsoftware.com](https://groundskeeper.rsjsoftware.com)

---

## What it does

- **One feed of what needs attention.** Problems only: a quiet feed means everything is
  healthy. Each issue says what changed, when, and how long it has been going on.
- **Connectors for the tools schools use** -- Meraki, HP/Aruba and other SNMP switches,
  Windows servers and Active Directory, Hyper-V, Veeam, DNS and DHCP, WatchGuard, Dell
  iDRAC, UPSes and printers, Microsoft 365, Action1, and the online services the school
  depends on. The full list is on the [Connectors](../../wiki/Connectors) page of the wiki.
- **The RSJ Agent** on your Windows PCs and servers reports BitLocker, Defender, updates,
  disk health, local admins and more. Deploy it by Group Policy, your RMM, or
  Groundskeeper's own push-deploy; it keeps itself up to date.
- **Switches, understood.** Groundskeeper tells uplinks from device ports, so a PC being
  switched off is not treated like a link to another switch going down, and keeps a
  history of each port's traffic.
- **Readiness reports** for Cyber Essentials and the DfE filtering and monitoring
  standards, built from live data and exportable as a PDF.
- **A traffic-light view for senior leaders**, in plain English.
- **An AI assistant** for morning briefings and "why is this happening?" -- running
  locally with Ollama by default, so no data leaves the school.
- **Built for groups:** Central brings every school in a trust into one view, while each
  school keeps its own Groundskeeper server.
- **The essentials:** email, Teams and Slack alerts with quiet hours and maintenance
  windows, two-factor sign-in, nightly database backups with one-click restore.

## Why self-hosted

- **Your data stays on your network.** No monitoring cloud, no third party holding a
  map of your infrastructure.
- **Read-only by design.** Groundskeeper observes and reports; it never changes anything
  on the systems it monitors.
- **GDPR-friendly by default.** Nothing leaves the school unless you choose to send it.

---

## Getting started

1. **Download** the installer from the [Releases](../../releases) page. It includes
   everything it needs; there is nothing else to install first.
2. **Install** on a Windows Server and open the dashboard. The setup wizard walks you
   through your first connectors.
3. **Request a free Community key** from the dashboard.

The [wiki](../../wiki) has the setup guide ([Getting Started](../../wiki/Getting-Started)),
connector configuration and troubleshooting. System requirements are in each release's
notes and on the website.

## Editions

- **Community** -- free, up to five connectors of your choice, with a key renewed each
  year.
- **Pro** -- every connector, priced per school by phase.
- **Central** -- for groups of schools: one view across the group.

Prices are on the website: [groundskeeper.rsjsoftware.com/#pricing](https://groundskeeper.rsjsoftware.com/#pricing).

## Support

- **Questions and ideas:** [Discussions](../../discussions).
- **Bugs:** [Issues](../../issues) on this repository.
- **Paid editions:** email support as well.

There is no helpdesk with opening hours. Groundskeeper is built to be installed and run
by a school's own IT.

---

## About

Groundskeeper is built by **RSJ Software** -- a school IT professional who built it for
himself first -- for the school IT community.

- Privacy notice: [groundskeeper.rsjsoftware.com/privacy](https://groundskeeper.rsjsoftware.com/privacy)
- Website: [rsjsoftware.com](https://rsjsoftware.com)
- Reporting a security issue: see [SECURITY.md](SECURITY.md)

## Licence

Copyright RSJ Software. All rights reserved.

This repository is provided for transparency, release distribution and community
support. No licence is granted for reuse, modification or redistribution of the
source code.
