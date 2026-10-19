# Adflipr for Cursor

Official [Cursor](https://cursor.com) plugin for [Adflipr](https://adflipr.com/) — ecommerce email marketing for Shopify and WooCommerce via remote MCP.

| | |
|---|---|
| **MCP URL** | `https://mcp.adflipr.com/mcp` |
| **Auth** | OAuth 2.1 (PKCE) — sign in with your Adflipr account |
| **Marketplace** | Submitted to [Cursor Marketplace](https://cursor.com/marketplace) |

## What you can do

- Search campaigns, automations, popups, and landing pages
- Read performance and cart-recovery summaries
- Create draft templates, campaigns, popups, and landing pages
- Manage sending-domain setup
- With confirmation: schedule/send campaigns, publish popups, pause/activate automations

Does not change contacts or billing.

## Install

**Marketplace (when listed):** Customize → Plugins → search **Adflipr** → Install.

**Manual MCP config:**

```json
{
  "mcpServers": {
    "adflipr": {
      "type": "http",
      "url": "https://mcp.adflipr.com/mcp"
    }
  }
}
```

## Docs & privacy

- Help: https://adflipr.com/docs/help-docs/app-integrations/claude-connector/
- Privacy: https://adflipr.com/privacy-policy/
- Also on Claude: https://claude.ai/directory/adflipr

## License

MIT
