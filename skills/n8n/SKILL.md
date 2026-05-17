---
name: n8n
description: Design, build, debug, and document n8n workflows. Use for triggers, nodes, credentials, expressions, webhook workflows, data mapping, retries, error handling, integrations, and automation handoff.
---

# n8n

Build n8n workflows that are understandable, testable, and safe to operate.

## Workflow

1. Identify trigger, inputs, outputs, credentials, and target systems.
2. Keep node names descriptive and map fields explicitly.
3. Use expressions carefully and test with representative sample data.
4. Add error paths for external API calls and partial failures.
5. Avoid storing secrets in plain text nodes.
6. Document activation requirements, webhook URLs, schedules, and retry behavior.

## Validation

Test each branch with known inputs before relying on the full workflow.
