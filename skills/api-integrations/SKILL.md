---
name: api-integrations
description: Design, implement, debug, and document API integrations. Use for REST, GraphQL, webhooks, auth flows, pagination, retries, rate limits, SDK usage, request signing, error handling, and integration runbooks.
---

# API Integrations

Build integrations that are observable, repeatable, and resilient to partial failure.

## Workflow

1. Identify the provider, API version, authentication method, rate limits, and required scopes.
2. Read official API docs before implementing unstable or provider-specific behavior.
3. Model request and response schemas explicitly.
4. Handle pagination, retries, idempotency, timeouts, and provider error codes.
5. Avoid logging secrets, tokens, or sensitive payloads.
6. Add verification steps with sample requests or mocked responses.

## Output

Include setup steps, required environment variables, failure modes, and test commands when useful.
