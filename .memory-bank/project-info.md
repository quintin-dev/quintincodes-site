# Project Information: quintincodes website

## Overview
- **Project Name**: quintincodes website
- **Project Type**: development
- **Tech Stack**: I'll add these later
- **Description**: I'll add these later
- **Created**: 2025-06-28

## Architecture
This project has its own isolated memory system while maintaining access to the global knowledge base:

### Local Memory System (Project-Specific)
- **Memory Bank**: $ProjectPath\.memory-bank\
- **Chroma Database**: $ProjectPath\.chroma-data\
- **MCP Configuration**: $ProjectPath\.vscode\mcp.json

### Global Memory System (Cross-Project)
- **Global Memory Bank**: C:\Users\eddki\Code\MCP\memory-banks\global\
- **Global Chroma**: C:\Users\eddki\Code\MCP\chroma_data\global\
- **Global MCP**: VS Code User Settings

## Development Context
This project is part of Edd's (Edwardking) development ecosystem:
- Company: Qeyon Labs ("Start with an Idea, unlock Innovation")
- Learning Goal: FreeCodeCamp Full Stack Certification by 2026
- Focus: British English, clean code, comprehensive documentation

## Quick Start
1. Context is automatically loaded via .github/copilot-instructions.md
2. Project memory accessible via MCP memory-bank-project server
3. Semantic search enabled via chroma-project server
4. Global context remains accessible alongside project context
