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

Glama listing:

```text
https://glama.ai/mcp/servers/akramyaslam/partglyph-mcp
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

Glama ownership metadata is in `glama.json`.

## Legal And License

The files in this public discovery and setup repository are licensed under the MIT License. See `LICENSE`.

This repository license applies only to this repository's public metadata, documentation, and example configuration files. It does not grant rights to the Partglyph name, trademarks, brand assets, hosted service, API access, private gateway implementation, matching engine, product data, official catalog evidence, datasets, or customer data.

Use of the hosted Partglyph service is governed by the Partglyph legal terms:

- Terms of Service: `https://partglyph.com/legal/terms/`
- Privacy Policy: `https://partglyph.com/legal/privacy/`
- Engineering Disclaimer: `https://partglyph.com/legal/engineering-disclaimer/`
- Limit of Liability: `https://partglyph.com/legal/liability/`

## Security Contact

For sensitive security concerns, see `SECURITY.md` or contact:

```text
hello@partglyph.com
```

Do not open public GitHub issues containing API keys, customer data, or vulnerability details.
