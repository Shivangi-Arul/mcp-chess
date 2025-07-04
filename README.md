Install this MCP server by adding the following JSON code to your JSON config  file 

'''json
{
    "mcpServers": {
        "Chess": {
            "command": "uvx",
            "args": [
                "--from",
                "git+https://github.com/Shivangi-Arul/mcp-chess.git",
                "chess"
                    ]
                }
    }
}

'''
