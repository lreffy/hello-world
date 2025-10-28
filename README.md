# hello-world


服务配置如下

```
# MacOS/Linux
code ~/Library/Application\ Support/Claude/claude_desktop_config.json

# Windows
code $env:AppData\Claude\claude_desktop_config.json
```
```
{
  "mcpServers": {
    "weather": {
      "command": "npx",
        "args": [
            "-y",
            "@h1deya/mcp-server-weather"
        ],
    }
  }
}
```
