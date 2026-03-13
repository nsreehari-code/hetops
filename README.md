# HET Skilling OS — hetops

**Execution Map — Operations & Batch Lifecycle**

The operational half of the HET Skilling Operating System. This repo is where batches get run, defended, and proven.

## What Lives Here

- **Execution Stages** — OS Stages 4–8 (Package, Launch, Deliver, Certify, Outcome Track)
- **Batch Lifecycle** — 7-stage operational backbone (Pre-Auth → Mobilize → Kick-Off → Delivery → Assessment → Certification → Livelihood)
- **Templates** — CCF sections D–I, batch runbook
- **Checklists** — 7 micro-packs (one per batch lifecycle stage)
- **Evidence Spines** — Per-course evidence artifact definitions
- **Operational Adapters** — Govt / CSR / Paid operational checklists
- **Roles** — Ownership matrix per stage
- **Decision Records** — Operational decisions (append-only, semantic)

## Architecture

- Pure HTML + JS + Markdown — no build tools
- Markdown rendered client-side via [marked.js](https://marked.js.org/)
- GitHub Pages on `gh-pages` branch
- Content is edited as `.md` files, rendered in the browser

## Companion Repos

| Repo | Purpose |
|------|---------|
| [hetexecs](https://github.com/nsreehari-code/hetexecs) | CEO map — Stages 1–3, portfolio, pinboard, doctrine, funding strategy |
| [hetweb](https://github.com/nsreehari-code/hetweb) | Public-facing website |
| [hetlms](https://github.com/nsreehari-code/hetlms) | LMS application code |

## Part of H8 Society

Bridge agent: `bridge-hetops` — relays ops/template questions to this repo's Copilot via H8-Theater.
