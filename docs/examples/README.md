# Example MCP servers (test)

`mcp-servers.json` lists benign reference MCP servers from the official
Model Context Protocol project, for testing MCP discovery and governance.
It is an example only: it is not loaded by Terraform or any bootstrap script.

| Server | Purpose |
|---|---|
| filesystem | File access limited to `./sandbox` |
| memory | Knowledge-graph memory |
| sequential-thinking | Step-by-step reasoning helper |
| everything | Protocol test server exercising all MCP features |
| git | Read-only-style git inspection of this repo |
| time | Time and timezone conversion |
| fetch | Fetches web pages and converts them to markdown |
| playwright | Browser automation via Playwright |
| context7 | Up-to-date library documentation lookup |
| github | GitHub API access; token is read from the GITHUB_PERSONAL_ACCESS_TOKEN env var (placeholder only) |

No credentials or tokens are included; the github entry only references an environment variable.