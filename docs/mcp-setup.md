# MCP Setup Documentation

## IDE Used
- Operating System: Linux
- Laptop: HP ProBook 640 G2
- IDE: Visual Studio Code (latest version)
- AI Tools: GitHub Copilot and GitHub Copilot Chat

## Steps Followed
1. Created a new project folder for the MCP challenge.
2. Installed GitHub Copilot and GitHub Copilot Chat extensions in VS Code.
3. Created a `.vscode` folder and added `mcp.json`.
4. Added the Tenx MCP server configuration with the correct Linux headers.
5. Reloaded the VS Code window multiple times.
6. Verified the existence of `mcp.json` using the terminal.
7. Ensured VS Code workspace was trusted.
8. Confirmed GitHub authentication in Copilot Chat.

## Errors / Issues Encountered
- The MCP server (`tenxfeedbackanalytics`) did not appear in the MCP Servers panel in VS Code.
- No visible “Start” button appeared for the MCP server.

## Troubleshooting and Fix Attempts
- Verified the file path: `.vscode/mcp.json`
- Verified JSON syntax and header values (`X-Device: linux`)
- Reloaded VS Code window using Command Palette
- Restarted VS Code completely
- Confirmed Copilot and Copilot Chat were enabled and logged in
- Checked the file using terminal:
  ```bash
  ls .vscode
