# Compatibility

SoloCorp AI OS is framework-agnostic.

## Why it works across tools
The system is built on portable components:
- Role specs (`/employees`)
- Workflow docs (`/workflows`)
- Prompt starters (inside each role/workflow)
- Handoff conventions (`/os/handoff-rules.md`)
- Simple schemas (`/os/*.json`)

## Claude Code
1. Open this repo as workspace context.
2. Ask Claude Code to act as a specific employee file.
3. Execute a workflow step-by-step with approvals.
4. Store outputs in markdown artifacts.

## OpenClaw
1. Load role and workflow files as prompt context.
2. Use approval policy as system constraint.
3. Run handoffs by passing structured packets.
4. Persist memory updates after milestones.

## Codex
1. Provide employee + workflow docs in task prompt.
2. Request outputs using template formats.
3. Keep founder approvals for external or irreversible actions.
4. Update shared memory and task objects.

## Other frameworks
Any system that can read markdown instructions and output structured text can run this repo.
