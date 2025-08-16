# MCP Filesystem Server

This is a **Model Context Protocol (MCP) server** implementation that exposes a **local filesystem** as a knowledge base provider.  
It allows MCP clients (like AI assistants) to read files from your system in a controlled manner and use them as context.

---

## 📂 Features
- Exposes selected directories as a **knowledge base**.
- Supports **read-only access** to text-based files (e.g., `.md`, `.txt`, `.pdf`, `.docx` after parsing).
- Compatible with **MCP-compatible clients**.
- Configurable root directory for safe sandboxing.

---

## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mcp-filesystem-server.git
   cd mcp-filesystem-server
