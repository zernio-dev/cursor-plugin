# Zernio Plugin for Cursor

The Zernio plugin for [Cursor](https://cursor.com) gives Cursor the tools and skills needed to work effectively with the Zernio Social Media Scheduling API.

## What's Included

- **MCP Server** - Connection to the [Zernio MCP server](https://docs.zernio.com/resources/mcp) for scheduling posts, managing accounts, uploading media, and more across 14 social platforms
- **Skills** - Agent skills from [zernio-api](https://github.com/zernio-dev/zernio-api) (API reference, authentication, endpoints, platform-specific features)

## Prerequisites

- A [Zernio API key](https://zernio.com) (free tier available)
- Set `ZERNIO_API_KEY` in your environment
- Python 3.10+ (for the MCP server via `uvx`)

## Development

This repo uses git submodules for shared agent skills.

After cloning, initialize the submodules:

```bash
git submodule update --init --recursive
```

To update the submodules:

```bash
git submodule update --remote submodules/zernio-api
git add submodules/
git commit -m "chore: update skill submodules"
```

## Links

- [Zernio Documentation](https://docs.zernio.com)
- [Zernio Python SDK](https://github.com/zernio-dev/zernio-python)
- [Zernio Dashboard](https://zernio.com/dashboard)

## License

Apache-2.0
