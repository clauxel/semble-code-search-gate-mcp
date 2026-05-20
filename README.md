# Semble Code Search Gate

Semble Code Search Gate is a hosted remote MCP for agent code search routing MCP.

This repository is a public documentation project for Semble Code Search Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://semblecodesearchgate.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=semblecodesearchgate_public_docs&utm_content=readme_home
- Pricing: https://semblecodesearchgate.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=semblecodesearchgate_public_docs&utm_content=readme_pricing
- Checkout: https://semblecodesearchgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=semblecodesearchgate_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://semblecodesearchgate.clauxel.com/mcp
- Server card: https://semblecodesearchgate.clauxel.com/server-card.json
- Registry name: `com.clauxel.semblecodesearchgate/semblecodesearchgate-mcp`
- Tools: `route_code_search`, `explain_context_choice`, `issue_search_receipt`, `log_search_route`, `export_search_audit`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: route_code_search
- MCP tool: explain_context_choice
- MCP tool: issue_search_receipt
- MCP tool: log_search_route
- MCP tool: export_search_audit

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
