# Falcon MCP

Falcon MCP connects Claude Code or Codex to the local Falcon MCP server at `http://localhost:32526`, making Falcon tools available in-agent as `mcp__falcon__*`.

Before installing, make sure the Falcon app is running and its MCP server is enabled.

## Claude Code

From inside Claude Code:

```text
/plugin marketplace add designcompute/agent-plugins
/plugin install falcon-mcp
```

## Codex

Use the GitHub-hosted marketplace:

```text
https://github.com/designcompute/agent-plugins/tree/main
```

Then install `falcon-mcp` from the Falcon marketplace in Codex.
