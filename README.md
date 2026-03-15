# SoloCorp AI OS

**Build and run a one-person AI company with a full team of AI employees — using Claude Code, OpenClaw, Codex, or any modern agent stack.**

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE)
[![Prompt-First](https://img.shields.io/badge/design-prompt--first-blue.svg)](#)
[![Framework Agnostic](https://img.shields.io/badge/framework-agnostic-purple.svg)](#)

SoloCorp AI OS is a framework-agnostic, markdown-first operating system for solo founders who want structured execution, reusable workflows, and strict founder-controlled approvals.

## What you get in this repo
- **AI employees by business function** (executive, growth, sales, product, engineering, operations)
- **Founder-safe workflows** with explicit approval gates and handoff steps
- **Shared memory + schemas** for continuity across tasks and tools
- **Reusable templates** for proposals, PRDs, outreach, support, and weekly reporting

## Why it is not a generic agent list
Most repositories stop at role prompts. SoloCorp AI OS goes further with:
- operating constraints in `/company`
- execution systems in `/workflows`
- governance in `/os`
- production-ready templates in `/templates`

This makes it usable on day one, even without a custom runtime.

## Compatibility
Works with:
- **Claude Code**
- **OpenClaw**
- **Codex**
- **Any framework that can read markdown instructions**

Read the implementation details in [`docs/compatibility.md`](./docs/compatibility.md).

## Quickstart (5 steps)
1. Fill [`templates/company-profile.md`](./templates/company-profile.md).
2. Copy key decisions into [`company/`](./company/).
3. Choose one workflow from [`workflows/`](./workflows/).
4. Run the participating employee Prompt Starters in your tool.
5. Pause at founder approvals (`/os/approval-policy.md`) and log outcomes in shared memory.

If you want a fuller setup path, use [`docs/quickstart.md`](./docs/quickstart.md).

## Repo structure
```text
/company      Strategy, ICP, offers, pricing, KPIs, policies
/employees    Role operating guides for AI employees
/workflows    Repeatable execution playbooks
/templates    Reusable artifact templates
/os           Approval policy, handoffs, memory, schemas
/examples     Realistic starter scenarios
/docs         Onboarding, compatibility, usage, FAQ, roadmap
```

## Core workflows
- [Launch a product](./workflows/launch-a-product.md)
- [Get first 10 customers](./workflows/get-first-10-customers.md)
- [Create content engine](./workflows/create-content-engine.md)
- [Ship a feature](./workflows/ship-a-feature.md)
- [Resolve support ticket](./workflows/resolve-support-ticket.md)
- [Weekly founder review](./workflows/weekly-founder-review.md)

## Example use cases
- **Solo SaaS founder:** product launch + first customers + weekly review
- **AI consultant:** lead gen + proposal pipeline + delivery operations
- **Creator business:** content engine + audience capture + offer iteration

See [`examples/`](./examples/) for realistic walkthroughs.

## Founder control and approvals
AI employees can draft, analyze, and coordinate.
The founder approves any external send, legal/financial commitment, production release, or strategic pivot.

Policy: [`os/approval-policy.md`](./os/approval-policy.md)

## Shared memory and handoffs
Execution quality depends on continuity.
Use shared memory to store decisions, customer signals, experiments, and open risks.
Use handoff packets so each role receives context, constraints, and expected output format.

References:
- [`os/shared-memory.md`](./os/shared-memory.md)
- [`os/handoff-rules.md`](./os/handoff-rules.md)

## FAQ
See [`docs/faq.md`](./docs/faq.md).

## Roadmap
See [`docs/roadmap.md`](./docs/roadmap.md).

## Contributing
Read [`CONTRIBUTING.md`](./CONTRIBUTING.md) before opening a PR.
