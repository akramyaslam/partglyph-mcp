# Partglyph MCP Gateway

Partglyph MCP Gateway connects AI coding assistants and agents to Partglyph's deterministic industrial replacement engine.

Use it from MCP-capable clients such as Codex, Claude Code, and other agent workflows to request replacement options, technical comparisons, source-backed matches, and previous match history without leaving the tools your team already uses.

Partglyph uses validated product inputs, official catalog evidence, expert accuracy checks, match history, and source tracking so your AI agent can use a governed replacement engine instead of guessing from general web research.

## Hosted Service

Partglyph MCP Gateway is a hosted remote MCP service.

```text
https://app.partglyph.com/api-mcp/mcp
```

This repository is a public discovery and setup repository. It contains metadata and examples only. The production gateway implementation source code is private.

## Documentation

Full setup instructions:

```text
https://docs.partglyph.com/integrations/mcp/
```

Official MCP Registry listing:

```text
https://registry.modelcontextprotocol.io/v0.1/servers?search=com.partglyph/mcp-gateway
```

## Authentication

Create a Partglyph MCP Access API key in the Partglyph app:

```text
https://app.partglyph.com/settings/api-keys
```

Use the key as a bearer token:

```text
Authorization: Bearer <PARTGLYPH_API_KEY>
```

Do not share API keys or commit them to repositories.

## Client Examples

Example configuration files are in `examples/`:

- `examples/codex-config.toml`
- `examples/claude-code-http.json`
- `examples/claude-desktop-connectors.md`

All examples use placeholders only.

## Server Metadata

The public server metadata is in `server.json`.

It mirrors the Official MCP Registry metadata for:

```text
com.partglyph/mcp-gateway
```

## Security Contact

For sensitive security concerns, see `SECURITY.md` or contact:

```text
hello@partglyph.com
```

Do not open public GitHub issues containing API keys, customer data, or vulnerability details.
