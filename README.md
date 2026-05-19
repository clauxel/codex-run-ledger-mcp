# CodexRun Ledger MCP

Codex run receipts your reviewer can trust.

Paid remote MCP for Codex run ledgers, changed-file evidence, scope summaries, missing proof checks, and client-ready handoff receipts.

## Public Endpoints

- Website: https://codexrunledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://codexrunledger.clauxel.com/mcp
- Server card: https://codexrunledger.clauxel.com/server-card.json
- Registry name: `com.clauxel.codexrunledger/codexrunledger-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `create_run_receipt`
- `summarize_scope`
- `list_missing_evidence`
- `export_client_handoff`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- [OpenHuman Online](https://openhuman.online/?utm_source=github&utm_medium=readme&utm_campaign=openhuman_public_repos&utm_content=codex_run_ledger_mcp) helps teams keep MCP rollout notes, source context, and approval memory inspectable for human-reviewed workflows.
- Product page: https://codexrunledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://codexrunledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://codexrunledger.clauxel.com/server-card.json
- MCP endpoint: https://codexrunledger.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
