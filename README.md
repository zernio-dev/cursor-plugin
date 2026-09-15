# Zernio Plugin for Cursor

The Zernio plugin for [Cursor](https://cursor.com) connects Cursor to the Zernio Social Media Scheduling API via MCP.

## What's Included

- **MCP Server** - Full access to the [Zernio API](https://docs.zernio.com) for scheduling posts, managing accounts, uploading media, running ads, managing contacts, and more across 16 social platforms

## Authentication

The plugin connects to the hosted server at `https://mcp.zernio.com/mcp` and uses OAuth with your Zernio account.

1. Install the plugin and enable its Zernio MCP server in Cursor's **Customize** page.
2. Ask Cursor to list your connected Zernio accounts. The server requests authentication when an account tool is called.
3. Complete the browser sign-in when Cursor prompts you, then retry the request.

If authentication is missing, confirm that Cursor has loaded the latest plugin and that the Zernio MCP server appears in Customize. The plugin's root `mcp.json` must contain an `mcpServers` object. Reload Cursor after updating the plugin.

See [Zernio MCP setup](https://docs.zernio.com/mcp/setup) and [Cursor MCP configuration](https://cursor.com/docs/mcp).

## Links

- [Zernio Documentation](https://docs.zernio.com)
- [Zernio Dashboard](https://zernio.com/dashboard)

## License

Apache-2.0
