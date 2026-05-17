---
name: incident-debugging
description: Debug incidents, outages, regressions, production errors, and urgent operational problems. Use for triage, logs, reproduction, hypothesis testing, mitigation, root cause analysis, and post-incident summaries.
---

# Incident Debugging

Stabilize first, explain second, prevent recurrence third.

## Workflow

1. Establish impact, severity, timeline, affected users, and current state.
2. Preserve evidence before making risky changes.
3. Check recent deploys, config changes, dependencies, traffic shifts, and alerts.
4. Form one hypothesis at a time and test it with evidence.
5. Prefer mitigations that reduce user impact while preserving diagnostic signal.
6. After recovery, document root cause, contributing factors, detection gaps, and follow-up actions.

## Guardrails

Be explicit about uncertainty. Do not present a root cause until the evidence supports it.
