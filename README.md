# SourcingSignal

**China sourcing decisions, inside your AI agent.**

SourcingSignal is an MCP server for overseas sellers and product researchers.
Give it a product keyword and your target selling price, and it returns a
decision-ready sourcing brief built from 1688 supplier listings.

## What you get

- Supplier offers with price, MOQ, and supplier risk
- Landed cost: product + domestic shipping + international freight + duty estimate
- Margin at your target selling price
- A red / yellow / green sourcing verdict with the reasoning

## Tools

- `sourcing_report` — keyword + target price → offers, landed cost, margin, verdict
- `calc_margin` — free landed-cost and margin calculator

## Connect

```json
{
  "mcpServers": {
    "sourcing-signal": {
      "url": "https://api.YOUR-DOMAIN/mcp",
      "headers": { "Authorization": "Bearer YOUR_API_KEY" }
    }
  }
}
```

Works with any MCP-compatible client (Claude, Cursor, VS Code, and others).

## Pricing

- Free: 3 sourcing reports per month
- Pro: $15 / month — 100 reports per month

Checkout and API credentials are being finalized. Watch this repository for
the launch link.

## Contact

YOUR-SUPPORT-EMAIL
