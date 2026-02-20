# Aion Theorycraft MCP

Simple AI companion for Aion players.

This server gives AI assistants structured game knowledge so they can answer practical questions faster and with better consistency.

## MCP Endpoint

- `https://mcp.theorycraft.workers.dev/mcp`

## What You Can Ask

- Build and class guidance
- Skill understanding and comparisons
- Progression and gearing decisions
- Quick lookup questions during gameplay

## Connect It To Major AI Apps

The exact UI can change over time, but the connection model is always the same:
- Add a remote MCP server
- Use URL: `https://mcp.theorycraft.workers.dev/mcp`
- Save and enable the server/tools

### ChatGPT

1. Open ChatGPT MCP/Connectors settings.
2. Add a custom remote MCP server.
3. Set server URL to `https://mcp.theorycraft.workers.dev/mcp`.
4. Enable the tools in your chat/workspace.

### Claude

1. Open Claude integrations/connectors settings.
2. Add a custom remote MCP server.
3. Use `https://mcp.theorycraft.workers.dev/mcp`.
4. Enable it for your conversations/projects.

### Cursor

1. Open MCP settings (or MCP config file).
2. Add a remote MCP server pointing to `https://mcp.theorycraft.workers.dev/mcp`.
3. Reload tools and start using it in chat/agent mode.

### VS Code / GitHub Copilot

1. Open MCP server configuration in VS Code.
2. Add the remote server URL: `https://mcp.theorycraft.workers.dev/mcp`.
3. Enable the server in agent/chat mode.

## Quick Prompt Examples

- "I play Ranger. Give me a simple PvE skill priority."
- "What is the best beginner progression path for my class?"
- "Compare two skill options for sustained damage."

## Product Goal

Make Aion theorycrafting easier, faster, and more accessible for real players.

## Official References

- OpenAI MCP docs: `https://platform.openai.com/docs/mcp`
- OpenAI Apps + Connectors: `https://platform.openai.com/docs/guides/tools-connectors-mcp`
- Anthropic MCP docs: `https://docs.anthropic.com/en/docs/agents-and-tools/mcp`
