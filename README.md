# Semgrep Cursor Plugin

 This repo is where the Semgrep Cursor Plugin lives. The Semgrep Plugin includes a MCP server, hooks, and skills, which
 are used to scan agent-generated code for security vulnerabilities and provide recommendations for fixing them.

 To use the Semgrep plugin:
 1. Install the plugin from the Cursor Plugin Marketplace

 1. Run the `/setup-semgrep-plugin` skill.

 1. Connect the [Semgrep MCP server](https://docs.semgrep.dev/mcp/overview) (`https://semgrep.dev/api/mcp`): in
    Cursor's MCP settings, sign in to the `semgrep` server through your browser with OAuth.
