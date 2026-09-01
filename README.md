# AledaMail MCP Server

MCP server for [AledaMail](https://aledamail.com) — email marketing and automation platform.

Connect Claude, ChatGPT, or any MCP-compatible AI assistant to your AledaMail account and manage email marketing through natural language.

## What you can do

- Create, schedule, and analyze newsletter campaigns
- Manage automation journeys and event-driven triggers
- Import and manage subscriber lists and segments
- Review campaign performance (open rates, click rates, bounces, top openers)
- Send transactional email via REST API
- Manage landing pages and opt-in forms
- Configure sending infrastructure and account settings

## Connect

**MCP endpoint:** `https://mxa.aledamail.com/mcp`

### Claude Desktop

Add to your `claude_desktop_config.json`:

```json
{
  "mcpServers": {
    "aledamail": {
      "type": "http",
      "url": "https://mxa.aledamail.com/mcp"
    }
  }
}
```

### Claude.ai

Go to **Settings → Integrations** and add `https://mxa.aledamail.com/mcp` as a custom MCP server.

## Key tools

| Tool | Description |
|---|---|
| `campaigns` | Create, schedule, and analyze email campaigns |
| `automations` | Manage journey workflows and triggers |
| `subscribers` | Import, segment, and manage contacts |
| `lists` | Manage mailing lists |
| `analytics` | Open rates, click rates, automation performance |
| `configure` | Account settings, signature, send windows |
| `landing_page` | Manage landing pages and opt-in forms |

## Infrastructure

AledaMail supports bring-your-own sending infrastructure (BYOS). Connect your own Amazon SES, SendGrid, Mailgun, Postmark, SparkPost, or any SMTP server. Agency plans include managed sending.

## Requirements

- An [AledaMail](https://aledamail.com) account
- Free plan available — no credit card required

## Links

- [AledaMail](https://aledamail.com)
- [Sign up free](https://mxa.aledamail.com/users/register)
- [Support](mailto:hello@aledamail.com)
