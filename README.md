# Ad Library by Ryze — Cursor Plugin

Research competitor ads from the public Meta Ad Library and manage your own Google Ads and Meta Ads accounts from Cursor.

## Install

**In Cursor:**

[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20Ad%20Library%20by%20Ryze-000000?logo=cursor&logoColor=white)](cursor://anysphere.cursor-deeplink/mcp/install?name=ad-library-by-ryze&config=eyJ1cmwiOiAiaHR0cHM6Ly9hZGxpYnJhcnkuZ2V0LXJ5emUuYWkvbWNwIn0=)

Or by hand: **Cursor › Settings › MCP › Add new MCP server**, type `http`, URL:

```
https://adlibrary.get-ryze.ai/mcp
```

Or drop this into `.cursor/mcp.json` in your project (same content as [mcp.json](mcp.json)):

```json
{ "mcpServers": { "ad-library-by-ryze": { "url": "https://adlibrary.get-ryze.ai/mcp" } } }
```

Cursor opens a browser tab: sign in to Ryze and allow access. No API keys. Also works in Claude Code: `claude mcp add ad-library --transport http https://adlibrary.get-ryze.ai/mcp`.

## What you can do

- **Meta Ad Library**: search Facebook and Instagram ads by competitor domain, Facebook Page id or keyword. Results include the image or video link, ad text, call to action, landing page, start date and days running, with the longest-running ads first. No ad account connection needed.
- **Meta Ads**: account summaries, performance reports, creatives, lead forms, Graph API reads and writes, image uploads.
- **Google Ads**: account summaries and hierarchy, GAQL reports, conversion actions, recommendations, keyword ideas and historical metrics, campaign changes, custom audiences, Customer Match and image assets.

Account tools appear after you connect that platform in Ryze.

## Safety

Read tools are read-only. Tools that change an account are marked as writes, and delete tools are marked destructive. Every action runs under the permissions of the accounts you connected.

## Requirements

A Ryze AI account. Connecting accounts works before you start a plan. Ad Library search and the account tools need an active Ryze plan, which starts with a 7-day trial; the assistant gives you the link the first time a tool needs it.

## Links

- [Website](https://www.get-ryze.ai?utm_source=github&utm_content=ad-library-cursor-plugin)
- [Privacy policy](https://www.get-ryze.ai/privacy?utm_source=github&utm_content=ad-library-cursor-plugin)
- Support: hello@get-ryze.ai

Ad Library by Ryze is an independent product. It is not affiliated with or endorsed by Meta or Google.
