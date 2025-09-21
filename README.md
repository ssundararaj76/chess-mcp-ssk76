Install this MCP server by adding the following JSON to your MCP JSON config.

Example (valid JSON):

```json
{
    "mcpServers": {
        "server": {
          "command": "uv",
          "args": [
            "--from",
            "git+https://github.com/ssundararaj76/chess-mcp-ssk76.git",
            "chess"
          ]
        }
    }
}
```
Notes:
- Replace "chess-server" with the name you prefer.
- The `--from` argument tells `uv` to install the package from the given Git URL and run the `chess` entrypoint defined in the package.
- After adding this to your MCP configuration, start the server with your MCP runtime (for example, using `uv` or your workspace tooling).