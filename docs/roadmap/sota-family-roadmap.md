# SOTA Family Roadmap

Status: archived adoption plan
Owner: Linear MCP
Scope: repo-local future plan and its role in the SylphxAI MCP family
Decision record: `docs/adr/ADR-25-mcp-family-sota-roadmap.md`

## Family Role

Linear MCP is a connector MCP. It gives agents access to Linear issues,
projects, teams, users, statuses, labels, comments, and milestones. It is not a
core family substrate like Reader, CodeRAG, Architecture Reader, Filesystem, or
Consultant MCP.

Because the repository is archived, its current family role is reference and
possible future reactivation, not active distribution.

## Family Fit

| Project | Relationship |
| --- | --- |
| Consultant MCP | May use connector outputs as evidence for delivery review only if reactivated. |
| Architecture Reader MCP | May link Linear project metadata to ownership or roadmap context only through explicit integration. |
| Filesystem MCP | No direct dependency; file operations stay separate from SaaS connector behavior. |
| CodeRAG and Reader MCPs | No direct dependency. |

## SOTA End State

If this connector is reactivated, it should be a secure, least-privilege,
auditable Linear connector with clear auth, pagination, rate-limit, write
policy, and operation evidence. If not reactivated, it should remain archived
and clearly point users to the current supported connector path.

## Roadmap

### Phase 0: Archive Clarity

- Keep the archived status explicit.
- Document that active flagship MCP work lives in the evidence, code
  intelligence, filesystem, and consultant repos.
- Do not publish new package versions while archived.

### Phase 1: Reactivation Bar

- Add project manifest and ADR before any code changes.
- Add auth, scope, pagination, rate-limit, retry, idempotency, and audit-policy
  tests.
- Add clear read vs write tool boundaries and dry-run mode for write tools.

### Phase 2: Family Integration

- If reactivated, emit evidence envelopes for issue/project operations.
- Allow Consultant MCP to review delivery state from Linear evidence without
  embedding Linear-specific policy in Consultant MCP.

## Validation Gates

- No package release while archived.
- Reactivation requires CI, package smoke, auth-scope tests, and write-policy
  tests.
- Every write-capable tool exposes operation evidence and failure semantics.
