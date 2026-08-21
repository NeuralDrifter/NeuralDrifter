<div align="center">

# Michael P. Burgus

### Agent infrastructure, retrieval systems, and tools that connect AI to real environments

</div>

I build practical systems around language models: controlled coding agents, local retrieval, multi-provider infrastructure, and bridges into environments that modern tooling usually leaves behind.

My work tends to sit at the boundary between an AI model and the real system it needs to use. I care about making that boundary explicit, inspectable, and dependable.

## Selected work

### [DOSBox-X Agent86](https://github.com/NeuralDrifter/dosbox-x-Agent86)

An Agent86-focused DOSBox-X fork that gives MCP-capable agents a controlled path into an authentic emulated DOS environment. Its loopback-only `CTTY BRIDGE` supports serialized DOS commands, bounded CP437 file writes, and console release, with integrations for Codex, Claude Code, and Gemini.

`C` · `C++` · `Python` · `MCP` · `MS-DOS`

### [StandardIssue](https://github.com/NeuralDrifter/StandardIssue)

A Tauri desktop application for browsing, enriching, and downloading the Standard Ebooks catalog. It works from the project's published GitHub sources, combines repository data with OPF metadata and covers, and can build EPUBs locally with cancellable concurrent jobs.

`Rust` · `Tauri` · `Tokio` · `JavaScript`

### [Foreman CLI](https://github.com/NeuralDrifter/foreman-cli)

A Windows terminal workspace for agent-assisted coding with an integrated editor and explicit tool controls. It combines workspace-confined file operations, selectable shell policies, read-only delegated agents, and reviewed remote skills in one TUI.

`Rust` · `Ratatui` · `Tokio`

### [RAG Narock](https://github.com/NeuralDrifter/rag-narock)

A local-first retrieval system for technical books, documents, and source code. It includes multiple storage backends, OCR and media ingestion, content-integrity tracking, a terminal editor, and MCP access while keeping indexed material on the machine.

`Python` · `SQLite` · `FAISS` · `MCP`

### Prism Relay · private project

A Go MCP server for querying and comparing responses across multiple language-model providers. It packages provider routing, operating-system keychain integration, and root-confined codebase bundles into a single binary for use from AI coding assistants.

`Go` · `MCP` · `Multi-provider LLMs`

## How I build

- Give powerful tools clear authority boundaries and visible controls.
- Prefer local-first processing when the work involves personal source material or documents.
- Use source-native integrations and published interfaces instead of fighting the systems that provide the data.
- Treat tests, failure paths, and operational documentation as part of the product.
- Keep older environments authentic while giving modern agents a narrow, deliberate bridge into them.

## Current toolkit

Rust, Go, Python, C/C++, TypeScript and JavaScript, MCP, terminal interfaces, local AI, retrieval systems, Windows, Linux, and MS-DOS.

If one of these projects overlaps with something you are building, open an issue in the relevant repository or reach me through GitHub.
