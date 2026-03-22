# 🤝 sharingOracle

**DORA Execution MCP Server** — 8 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-8-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)
![Bus](https://img.shields.io/badge/Oracle_Bus-Connected-00C853?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/sharing/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "sharingoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/sharing/mcp/"]
    }
  }
}
```

## Tools (8)

| Tool | Description |
|------|-------------|
| `register_community` | Register membership in a threat sharing community. |
| `share_ioc` | Share an indicator of compromise. |
| `ioc_feed` | View IoC feed — shared and received. |
| `stix_export` | Export IoCs in STIX 2.1 format. |
| `sharing_log` | Audit log of sharing activity. |
| `community_status` | Community membership dashboard. |
| `sharing_evidence` | Evidence bundle for Art. 45 compliance. |
| `health_check` | Server status. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

sharingOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.

### DORA Coverage

**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/sharing/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
