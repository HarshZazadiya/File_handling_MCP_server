# File Handling MCP Server

An MCP server for file operations with PDF support.

## Setup

1. Create virtual environment:
```bash
python -m venv .venv
.venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run server:
```bash
python file_handle/file_handling_server.py
```

## Features
- Create/read/update/delete files
- PDF creation with reportlab
- Base64 decoding
- File listing with details

## API
Server runs on SSE transport at
```bash
 http://127.0.0.1:8001/sse
```