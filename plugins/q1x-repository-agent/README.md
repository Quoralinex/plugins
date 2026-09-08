# Q1X Repository Agent

Dual-format repository agent package for Agent Plugins 1.0 and current OpenAI plugin clients.

Portable surfaces live at `plugin.json`, `mcp.json` and `skills/`. OpenAI compatibility is provided by `.codex-plugin/plugin.json`, `.mcp.json` and `.app.json`.

The MCP endpoint is intentionally remote and contains no embedded credentials. Write, merge, deployment and destructive authority remain governed by the Q1X control plane.

`REPLACE_WITH_Q1X_AGENT_APP_ID` must be replaced with the ChatGPT app/connector id when the MCP-backed Q1X app is registered.
