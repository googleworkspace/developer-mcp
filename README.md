# @googleworkspace/developer-mcp

[![npm version](https://img.shields.io/npm/v/%40googleworkspace%2Fdeveloper-mcp)](https://www.npmjs.com/package/@googleworkspace/developer-mcp)
![NPM Downloads](https://img.shields.io/npm/dm/%40googleworkspace%2Fdeveloper-mcp)
![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/googleworkspace/developer-mcp)
![GitHub last commit](https://img.shields.io/github/last-commit/googleworkspace/developer-mcp)
![GitHub License](https://img.shields.io/github/license/googleworkspace/developer-mcp)
[![Test](https://github.com/googleworkspace/developer-mcp/actions/workflows/test.yml/badge.svg)](https://github.com/googleworkspace/developer-mcp/actions/workflows/test.yml)
[![Release](https://github.com/googleworkspace/developer-mcp/actions/workflows/release.yml/badge.svg)](https://github.com/googleworkspace/developer-mcp/actions/workflows/release.yml)

A [Model Context Protocol](https://modelcontextprotocol.io/), server that provides tools for accessing and searching Google Workspace documentation.

> The Model Context Protocol (MCP) is a standard that enables AI assistants to access external tools and data through a network of specialized servers.

This server enables AI assistants and other tools to:

- Retrieve up-to-date information about Google Workspace APIs and services
- Fetch official Google Workspace documentation and snippets

To get started, you can add this server to your MCP client configuration.

```json
{
  "type": "stdio",
  "command": "npx",
  "args": ["-y", "@googleworkspace/developer-mcp"]
}
```

## Development

Contributions are welcome! Please see our [Contributing Guide](CONTRIBUTING.md) for more information.

```bash
pnpm install
pnpm build
pnpm test
pnpm check
pnpm lint
```

To add a new version for a pull request, run:

```bash
pnpm changeset add
```

If changes are made to the documentation, you can update the documentation by running:

```bash
pnpm readme
```

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This is not an official Google product.
