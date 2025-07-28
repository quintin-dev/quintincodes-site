# Project Methodology & Approach

## Project Structure
`
quintincodes website/
├── .memory-bank/           # Project-specific knowledge base
│   ├── project-info.md    # This file
│   ├── methodology.md     # Project approach and methods
│   ├── project-progress.md # Project progress and status
│   └── insights-learnings.md # Key insights and lessons
├── .chroma-data/          # Project-specific semantic search
├── .vscode/               # VS Code workspace configuration
│   └── mcp.json          # MCP server configuration
├── .github/               # GitHub configuration
│   └── copilot-instructions.md  # Copilot context
└── [project files...]
`

## Project Approach
- **Methodology**: I'll add these later
- **Work Environment**: VS Code with Copilot
- **AI Context System**: Multi-layer MCP architecture
- **Knowledge Management**: Local memory bank + Chroma vector database

## Decision Log
| Date | Decision | Reasoning |
|------|----------|-----------|
| 2025-06-28 | Project memory system created | Isolated context with global access |

## Integration Points
- **Global Context**: Accessible via global MCP servers
- **Project Context**: Isolated in local memory system
- **Copilot**: Configured via .github/copilot-instructions.md
- **Vector Search**: Local chroma instance for project-specific semantic search
