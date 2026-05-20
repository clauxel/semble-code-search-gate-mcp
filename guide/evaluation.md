# Evaluation Guide

Use this page to evaluate whether Semble Code Search Gate fits a real workflow.

## What To Test

- agent code search routing MCP
- Semble Code Search Gate
- Semble Code Search Gate documentation
- Semble Code Search Gate remote MCP
- semblecodesearchgate server card

## Expected Evidence

- Open Semble Code Search Gate and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://semblecodesearchgate.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call route_code_search with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://semblecodesearchgate.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=semblecodesearchgate_public_docs&utm_content=evaluation_checkout
