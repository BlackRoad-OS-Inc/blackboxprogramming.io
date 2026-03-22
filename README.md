# blackboxprogramming.io

> BlackBox — an AI coding assistant that runs on your hardware.

**Live at [https://blackboxprogramming.io](https://blackboxprogramming.io)**

## What BlackBox Is

BlackBox is a browser-based IDE with AI code completion powered by models running on your own machines. No cloud APIs. No telemetry. Your code stays on your device.

## Features

- **CodeMirror 6 editor** — fast, extensible, syntax highlighting for 30+ languages
- **LSP integration** — real language server completions, diagnostics, go-to-definition
- **Ollama-powered AI** — code completion and chat from local models (no external API calls)
- **WASM plugins** — extend the editor with WebAssembly modules
- **Git built in** — commit, push, diff without leaving the editor
- **Multi-file workspaces** — project tree, tabs, split panes

## How AI Completion Works

BlackBox connects to Ollama running on your local machine or your Pi fleet. Models like CodeLlama, DeepSeek Coder, and Starcoder run inference locally. Completions come from hardware you control — not from OpenAI, not from GitHub, not from anyone else.

## Pricing

| Plan | Price | What You Get |
|------|-------|-------------|
| BlackBox Pro | $29/mo | Full IDE, AI completion, LSP, WASM plugins |

## Architecture

- Frontend: HTML/CSS/JS + CodeMirror 6
- Served from Gematria (Caddy TLS + Let's Encrypt)
- AI backend: Ollama on Pi fleet (52 TOPS, 16 models)
- Your device, your data, your agents

## Part of BlackRoad OS

BlackRoad OS, Inc. (Delaware C-Corp, est. November 2025)
See [blackroad.io](https://blackroad.io) for the full platform.

## License

**PROPRIETARY** — BlackRoad OS, Inc. All rights reserved.

---

*BlackRoad OS — Remember the Road. Pave Tomorrow.*
