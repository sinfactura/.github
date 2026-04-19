<div align="center">

# SINFACTURA

**E-commerce and electronic invoicing platform for Argentine businesses**

[sinfactura.com](https://sinfactura.com) · [soporte@sinfactura.com](mailto:soporte@sinfactura.com)

</div>

---

We build tools that help Argentine businesses manage their operations, issue AFIP-compliant electronic invoices, and sell B2B online — all from a single platform.

### What we build

- **B2B E-Commerce** — Online marketplace for wholesale and business-to-business sales
- **Electronic Invoicing** — AFIP/ARCA compliant document issuance with QR codes
- **Business Management** — Inventory, sales, CRM, and operations dashboard
- **Cloud Printing** — Seamless document printing from the cloud to local printers

### Tech stack

React · TypeScript · Material UI · AWS Lambda · DynamoDB · Electron

---

> 📡 **Cockpit** → [Project board](https://github.com/orgs/sinfactura/projects/1) · [Label taxonomy](https://github.com/sinfactura/.github/blob/main/.github/labels.yml)

<!-- cockpit:start -->
<!-- This block is auto-generated daily by .github/workflows/update-profile-readme.yml -->
<!-- Last updated: 2026-04-19T23:12:04Z -->

## State of the org

| Signal | Count |
|---|---|
| 🔴 Open P0 (launch blockers) | `0` |
| 🟠 Open P1 (this sprint) | `0` |
| 🏃 In Progress | `0` |
| 📂 Active epics | `0` |
| 🚀 Shipped (last 7 days) | `1` |
| 🚀 Shipped (last 30 days) | `1` |
| 🐛 Open bugs | `0` |
| 🎧 Customer-reported open | `0` |

### 🔴 On fire

_None._

### 🏃 In flight

_None._

### 🚀 Recently shipped (last 7 days)

- [.github#1](https://github.com/sinfactura/.github/pull/1) feat(cockpit): org-wide labels, auto README, daily refresh

### 📂 Active epics

_None._

<!-- cockpit:end -->

---

### Repositories

| Repo | What it is | Stack |
|---|---|---|
| [app](https://github.com/sinfactura/app) | B2B admin / operations dashboard | React 19, MUI 7, Vite 8 |
| [web](https://github.com/sinfactura/web) | E-commerce storefront (TodoInsumos) | React 19, MUI 7, Vite 8 |
| [api](https://github.com/sinfactura/api) | Serverless backend | AWS CDK, Lambda, DynamoDB |
| [landing](https://github.com/sinfactura/landing) | Marketing site (sinfactura.com) | React 19, Vite 6 |
| [print](https://github.com/sinfactura/print) | Print agent v1 (legacy) | Electron |
| [cloudprint](https://github.com/sinfactura/cloudprint) | Cloud print agent v2 | Electron |
| [types](https://github.com/sinfactura/types) | Shared TypeScript types | TS |
| [mobile](https://github.com/sinfactura/mobile) | Mobile companion (planned) | — |

### Workflow

- GitHub Issues is the **single source of truth** for all work
- Every issue needs one `type:*`, one `P0-P3`, and one or more `area:*` labels — see [labels.yml](https://github.com/sinfactura/.github/blob/main/.github/labels.yml)
- Every "In Progress" board item has a linked draft PR
- PRs close issues with `Closes #NNN` and auto-deploy via Amplify (app/web/landing) or CDK (api)

<sub>Buenos Aires, Argentina</sub>
