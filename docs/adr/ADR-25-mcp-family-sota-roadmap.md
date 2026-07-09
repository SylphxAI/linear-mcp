# ADR-25: Adopt Linear MCP Family SOTA Roadmap

Date: 2026-07-09
Status: Proposed in PR #25
Slug: mcp-family-sota-roadmap

## Context

Linear MCP is an archived connector MCP. It should have a clear future state so
it does not blur the family boundary between flagship MCP products and archived
connector references.

## Decision

Adopt `docs/roadmap/sota-family-roadmap.md` as the repo-local roadmap.

Linear MCP remains archived unless a future ADR reactivates it with auth,
scope, pagination, rate-limit, write-policy, audit, and package gates.

## Consequences

- No package release should occur while archived.
- The core family roadmap should not depend on this connector.
- If reactivated, write-capable Linear operations need operation evidence,
  idempotency, and failure semantics.

## Verification

- Roadmap added at `docs/roadmap/sota-family-roadmap.md`.
- PROJECT and README link to the roadmap.
- Docs-only validation: `git diff --check`.
