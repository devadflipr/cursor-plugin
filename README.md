# Adflipr for Cursor

Remote [MCP](https://modelcontextprotocol.io) plugin for [Adflipr](https://adflipr.com/) ecommerce email marketing (Shopify & WooCommerce).

**MCP URL:** `https://mcp.adflipr.com/mcp`  
**Auth:** OAuth 2.1 (PKCE) when you connect in Cursor — sign in with your Adflipr account.

## What you can do

- Search campaigns, automations, popups, and landing pages  
- Read performance and cart-recovery summaries  
- Create draft templates, campaigns, popups, and landing pages  
- Manage sending-domain setup  
- With confirmation: schedule/send campaigns, publish popups, pause/activate automations  

Does not change contacts or billing.

## Docs

- Product docs: https://adflipr.com/docs/help-docs/app-integrations/claude-connector/  
- Privacy: https://adflipr.com/privacy-policy/  
- Claude directory listing: https://claude.ai/directory/adflipr  

## Local install (without Marketplace)

Add to Cursor MCP settings / `mcp.json`:

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

## License

MIT
