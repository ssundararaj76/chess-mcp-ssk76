Install this MCP server by addin the 
following JSON code to your JSON config 
file

''' json
{
    "mcpServers": {
        "server": {
          "command": uvx",
          "args": [
            "--from",
            "git+https://github.com/ssundararaj76/chess-mcp-ssk76.git",
            "chess"
          ]
        }
    }
}

'''