# Compatibility

SoloCorp AI OS is deliberately framework-agnostic.

## Portable design primitives
It works across tools because everything is plain-text and modular:
- Role specs (`/employees`)
- Workflow playbooks (`/workflows`)
- Prompt starters (inside each role/workflow)
- Handoff contract (`/os/handoff-rules.md`)
- Approval policy (`/os/approval-policy.md`)
- Optional schemas (`/os/*.json`)

## Claude Code
Best when you want repo-native execution with file-aware context.

**Recommended flow**
1. Open the repository as workspace context.
2. Ask Claude Code to operate as one employee file at a time.
3. Execute workflow steps in order.
4. Stop at founder approval gates before external action.
5. Save artifacts back into markdown files.

## OpenClaw
Best when you want structured multi-role orchestration with explicit routing.

**Recommended flow**
1. Load one workflow plus participating employee files.
2. Use `os/handoff-rules.md` as the routing contract between roles.
3. Use `os/approval-policy.md` as a hard safety constraint.
4. Persist major decisions and outcomes into shared memory.

## Codex
Best when you want fast prompt-first execution and artifact generation.

**Recommended flow**
1. Paste role + workflow docs into task context.
2. Ask Codex for output in a template format (`/templates`).
3. Require a "decisions needing founder approval" section in every run.
4. Record approved outcomes in memory and task records.

## Other frameworks
If a tool can read markdown context and produce structured text, it can run SoloCorp AI OS.
