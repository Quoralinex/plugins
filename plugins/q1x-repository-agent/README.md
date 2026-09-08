# Q1X Repository Agent

Dual-format repository agent package for Agent Plugins 1.0 and current OpenAI plugin clients.

Portable surfaces live at `plugin.json`, `mcp.json` and `skills/`. OpenAI compatibility is provided by `.codex-plugin/plugin.json`, `.mcp.json` and `.app.json`.

The remote MCP endpoint is `https://agents.q1x.xyz/mcp`. Version 0.2.0 exposes a deliberately cloud-safe read surface for authority, continuity, task and requirements context. Repository mutation is performed through separately approved repository tooling and remains subject to Q1X Control Plane authority.

The MCP endpoint contains no embedded credentials. `REPLACE_WITH_Q1X_AGENT_APP_ID` in `.app.json` must be replaced after the MCP-backed Q1X ChatGPT app is registered.
