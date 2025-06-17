[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/twodoorsdev-react-native-debugger-mcp-badge.png)](https://mseep.ai/app/twodoorsdev-react-native-debugger-mcp)

# React Native Debugger MCP

An MCP server that connects to your React Native application debugger.

## ✨ Key Features

- Can retrieve console logs from Metro

## 🚀 Quick Start

Add the following to your Claude Desktop/Cursor MCP config:

```json
{
  "mcpServers": {
    "react-native-debugger-mcp": {
      "command": "npx",
      "args": ["-y", "@twodoorsdev/react-native-debugger-mcp"]
    }
  }
}
```
