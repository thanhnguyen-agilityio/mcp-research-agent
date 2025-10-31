
### Guide
- Setup virtual env and active it:
```bash
uv sync
uv .venv/bin/activate
```
- Run MCP Inspector for server: (to test MCP server via MCP Inspector)
```bash
npx @modelcontextprotocol/inspector uv run research_server.py
```
- Run client:
```bash
uv run mcp_chatbot.py
```
