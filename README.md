# SoloCorp AI Operating System

> Build and run a one-person AI company with a full team of AI employees — compatible with Claude Code, OpenClaw, Codex, and modern agent frameworks.

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE)
[![Prompt-First](https://img.shields.io/badge/design-prompt--first-blue.svg)](#)
[![Framework Agnostic](https://img.shields.io/badge/framework-agnostic-purple.svg)](#)

SoloCorp AI OS is a markdown-first operating system for solo operators who want to run a real business with AI employees, structured workflows, and founder-controlled approvals.

## Why this is different
Most "agent" repos are role lists. This repo is an **operating model**:
- role specs define accountable AI employees
- workflows define repeatable execution paths
- founder controls define approvals and risk boundaries
- shared memory keeps context across tasks
- templates produce usable artifacts quickly

No custom runtime is required. You can run it in any agent environment or manually.

## Key features
- **Company operating layer** (`/company`) for strategy, offers, voice, metrics, and policy.
- **AI employee system** (`/employees`) grouped by core business functions.
- **Execution workflows** (`/workflows`) for product, growth, sales, support, and founder cadence.
- **OS controls** (`/os`) for approvals, handoffs, memory, and simple portable schemas.
- **Reusable templates** (`/templates`) for PRDs, outreach, proposals, support replies, and reports.
- **Real examples** (`/examples`) for SaaS, consulting, and creator businesses.
- **Practical docs** (`/docs`) for quickstart, compatibility, usage patterns, FAQ, and roadmap.

## Compatibility
This system is framework-agnostic. It works with:
- **Claude Code**
- **OpenClaw**
- **Codex**
- **Other agent frameworks** that can read markdown prompts and structured docs

See full details in [`docs/compatibility.md`](./docs/compatibility.md).

## Quickstart (10 minutes)
1. Duplicate this repo.
2. Fill out [`templates/company-profile.md`](./templates/company-profile.md).
3. Update files in [`company/`](./company/) using that profile.
4. Pick one workflow from [`workflows/`](./workflows/).
5. Run the listed employee prompt starters in your chosen framework.
6. Enforce approvals from [`os/approval-policy.md`](./os/approval-policy.md).
7. Save outputs and decisions in shared memory.

Full setup: [`docs/quickstart.md`](./docs/quickstart.md).

## Repo structure
```text
/company      Business strategy and operating constraints
/employees    Role-specific AI employee operating guides
/workflows    Repeatable execution plans with approval gates
/templates    Reusable business artifact templates
/os           Founder controls, handoffs, shared memory, schemas
/examples     Reference implementations for common solo business models
/docs         Onboarding, compatibility, patterns, roadmap
```

## AI org chart
```text
Founder
├── Executive (CEO, Chief of Staff, Strategy)
├── Growth (Content, SEO, Social, Ads)
├── Sales (Lead Research, Outreach, Closer, Proposal)
├── Product (PM, UX, User Research, QA)
├── Engineering (Architect, Fullstack, Automation, Debugger, DevOps)
└── Operations (Support, Success, Finance, Legal Ops)
```

## Core workflows
- [Launch a product](./workflows/launch-a-product.md)
- [Get first 10 customers](./workflows/get-first-10-customers.md)
- [Create content engine](./workflows/create-content-engine.md)
- [Ship a feature](./workflows/ship-a-feature.md)
- [Resolve support ticket](./workflows/resolve-support-ticket.md)
- [Weekly founder review](./workflows/weekly-founder-review.md)

## Choose your starting path
- **Solo SaaS founder:** start with [Launch a product](./workflows/launch-a-product.md) then [Get first 10 customers](./workflows/get-first-10-customers.md).
- **Consultant:** start with [Get first 10 customers](./workflows/get-first-10-customers.md) plus [`templates/proposal.md`](./templates/proposal.md).
- **Creator:** start with [Create content engine](./workflows/create-content-engine.md) and [`templates/landing-page-copy.md`](./templates/landing-page-copy.md).

## Founder control philosophy
AI employees can draft, analyze, and prepare recommendations. The founder controls:
- external sends
- legal/financial commitments
- irreversible actions
- strategic pivots

Policy reference: [`os/approval-policy.md`](./os/approval-policy.md).

## Shared memory and handoffs
Every workflow should update a shared operating memory:
- company context
- active priorities
- customer insights
- open decisions
- handoff notes between employees

See [`os/shared-memory.md`](./os/shared-memory.md) and [`os/handoff-rules.md`](./os/handoff-rules.md).

## Example kickoff prompts
- “Act as `employees/executive/chief-of-staff-agent.md`. Build this week’s execution plan from `company/kpis.md` and `workflows/weekly-founder-review.md`.”
- “Act as `employees/growth/content-agent.md`. Use `workflows/create-content-engine.md` and produce outputs in `templates/weekly-report.md` format.”

## FAQ
Quick answers are in [`docs/faq.md`](./docs/faq.md), including:
- Do I need a custom app runtime?
- Can I use this manually without any framework?
- How do I keep outputs consistent across agents?

## Roadmap
See [`docs/roadmap.md`](./docs/roadmap.md).

## Contributing
Please read [`CONTRIBUTING.md`](./CONTRIBUTING.md) before opening a PR.

## Suggested GitHub topics
`ai-agents`, `agent-framework`, `multi-agent`, `solo-founder`, `ai-company`, `ai-workforce`, `claude-code`, `codex`, `openclaw`, `prompt-engineering`, `workflow-automation`, `indie-hacker`
