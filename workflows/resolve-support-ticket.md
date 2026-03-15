# Workflow: Resolve Support Ticket

## Goal
Resolve customer issues quickly while preserving trust and capturing product insights.

## Best For
Technical issues, account confusion, billing disputes, and incident follow-ups.

## Required Inputs
Ticket details, account context, SLA policy, known issue log, product docs.

## Participating AI Employees
Support, Debugger, Fullstack, Success, Legal Ops (if policy-sensitive).

## Step-by-Step Execution
1. Triage severity and classify issue type.
2. Send acknowledgement with expected timeline.
3. Diagnose root cause and define fix path.
4. Deliver resolution or workaround.
5. Confirm customer outcome and close loop.
6. Log insight for product/process improvements.

## Founder Approval Gates
- Approve refunds/credits/policy exceptions.
- Approve legally sensitive responses.

## Expected Outputs
Resolved ticket response, root-cause note, escalation summary, prevention action.

## Common Failure Modes
Slow acknowledgment, vague communication, poor escalation, no root-cause capture.

## Success Metrics
First response time, resolution time, CSAT, repeat ticket rate.

## Copy/Paste Kickoff Prompt
"""
Run the `resolve-support-ticket` workflow using this repository.
Start by validating required inputs, assign owners from listed AI employees, and execute each step in order.
Pause at every founder approval gate before external action.
Return outputs in reusable markdown artifacts.
"""
