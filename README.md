# SecureLend Market (MCP)

Public listing wrapper for SecureLend's **remote** Market / placement MCP.

This repository does **not** run the server. The hosted Streamable HTTP endpoint is:

**https://mcp.securelend.ai/mcp**

## What it does

Compare US loans, cards, banking, and savings, then open a lender enquiry after the user confirms. SecureLend is a comparison and introduction platform, not a lender. No tool approves a loan.

## Connect

| | |
|---|---|
| MCP URL | `https://mcp.securelend.ai/mcp` |
| Docs | https://docs.securelend.ai/mcp/marketplace |
| Homepage | https://securelend.ai |
| Privacy | https://securelend.ai/legal/privacy |
| Terms | https://securelend.ai/legal/terms |
| Support | sales@securelend.ai |

Comparison tools work without auth. Enquiry tools require user-confirmed name and email.

## Official registry metadata

See [`server.json`](./server.json) (namespace `ai.securelend/market` after domain verification).

## Related

- Schema / OSS comparison infra: [SecureLend/mcp-financial-services](https://github.com/SecureLend/mcp-financial-services)
- **Underwriting MCP** (lender file → cited memo): [mcp-underwriting](https://github.com/orgtom78/mcp-underwriting)

## License

MIT
