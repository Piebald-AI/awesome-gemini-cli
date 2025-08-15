# Awesome Gemini CLI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, extensions, and resources for Gemini CLI.

<!--**Developed something cool for Gemini CLI?**  Add it to this list!  See [Contributing.](#contributing)-->

> We'll create a new release highlighting **new entries** each week. Star this repository to receive **release notifications** for the new entries in your GitHub dashboard!

## Contents

- [**🎉 New Entries**](#-new-entries)
- [Official](#official)
- [Interfaces](#interfaces)
- [Forks](#forks)
- [Fun](#fun)
- [Development Tools & Utilities](#development-tools--utilities)
- [API Bridges & Proxies](#api-bridges--proxies)
- [Commands & Extensions](#commands--extensions)
- [MCP Servers](#mcp-servers)
- [Neovim Plugins](#neovim-plugins)
- [GitHub Actions & Automation](#github-actions--automation)
- [Development Frameworks & Orchestration](#development-frameworks--orchestration)
- [Documentation & Learning Resources](#documentation--learning-resources)
- [Demo Collections & Examples](#demo-collections--examples)

## 🎉 New Entries

- [ai-sdk-provider-gemini-cli](https://github.com/ben-vargas/ai-sdk-provider-gemini-cli) - A community provider for the Vercel AI SDK that enables using Google's Gemini models through the Gemini CLI library.
- [solar-code](https://github.com/serithemage/solar-code) - Solar Pro2 powered code assistant based on Gemini CLI.
- [claude-squad](https://github.com/smtg-ai/claude-squad) - Manage multiple AI terminal agents like Gemini CLI, Claude Code, Codex CLI, Aider, OpenCode, Amp, etc.
- [gemini-openai-proxy](https://github.com/Brioch/gemini-openai-proxy) - Gemini CLI wrapper that can serve Google Gemini 2.5 Pro (or Flash) through an OpenAI-compatible API. Plug-and-play with clients that already speak OpenAI like SillyTavern, llama.cpp, LangChain, the VS Code Cline extension, etc.
- [oh-my-logo](https://github.com/shinshin86/oh-my-logo) - Display giant ASCII-art logos with colorful gradients in your terminal — like Claude Code or Gemini CLI.
- [nix-ai-tools](https://github.com/numtide/nix-ai-tools) - Exploring the integration between Nix and AI coding agents.  Easily install Gemini CLI and many other tools with Nix.
- [Terminal Jarvis](https://github.com/BA-CalderonMorales/terminal-jarvis) - A unified command center for AI coding tools. Manage and run Claude Code, Gemini CLI, Qwen Code, OpenCode, LLxprt, and Codex CLI from one beautiful terminal interface.

## Official

- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - An open-source AI agent that brings the power of Gemini directly into your terminal.
- [Gemini CLI cookbook](https://github.com/google-gemini/cookbook) - Examples and guides for using the Gemini API (https://ai.google.dev/gemini-api/docs)
- [run-gemini-cli](https://github.com/google-github-actions/run-gemini-cli) - GitHub Action that integrates Gemini into your development workflow via the Gemini CLI.

## Interfaces

- [Gemini Desktop](https://github.com/Piebald-AI/gemini-desktop) - Desktop/web UI for Gemini CLI.

## Forks

- [LLxprt Code](https://github.com/acoliver/llxprt-code) - Multi-provider fork of Gemini CLI that keeps up with main. Supports local models as well.
- [Qwen Code](https://github.com/QwenLM/qwen-code/) - Fork by the team behind Qwen LLM. Uses Qwen instead of Gemini.

## Fun

## Development Tools & Utilities
- [Splitrail](https://github.com/Piebald-AI/splitrail) - Usage analyzer tool + cloud for agentic development tools including Gemini CLI.
- [ccmanager](https://github.com/kbwo/ccmanager) - Session manager for Gemini CLI (and Claude Code / Codex CLI).
- [Gemini CLI Logs Prettifier](https://github.com/Manamama/Puzzles_for_AIs/tree/main/code/Gemini%20CLI%20logs%20prettifier) - Renders the logs human readable (prettifies them) and browsable as interlinked HTML, with thoughtful explanations and clickable links.
- [gemini-commit-assistant](https://github.com/C17AN/gemini-commit-assistant) - AI-based commit message generator, powered by Gemini CLI.
- [Gemini-CLI-Git-Ask](https://github.com/ihainan/Gemini-CLI-Git-Ask) - A code analysis tool that enables natural language queries about Git repositories using Google's Gemini CLI.
- [Gemini-CLI-Context-Engineer](https://github.com/rickscode/Gemini-CLI-Context-Engineer) - A comprehensive template for Context Engineering with Gemini CLI, designed to help AI coding assistants generate more accurate code.
- [gemini-cli-ntfy](https://github.com/nakkulla/gemini-cli-ntfy) - A transparent wrapper for Gemini CLI that sends a notification when Gemini needs your attention.
- [gcli-hotkey](https://github.com/hexcreator/gcli-hotkey) - Creates an awesome hotkey to open up Gemini CLI in whichever window you used the hotkey in.
- [gemini-cli-container](https://github.com/samhann/gemini-cli-container) - A comprehensive DevContainer setup for Google's Gemini CLI, designed to provide a secure, fully-featured development environment.

## API Bridges & Proxies

- [gemini-cli-openai](https://github.com/GewoonJaap/gemini-cli-openai) - Transform Google's Gemini models into OpenAI-compatible endpoints using Cloudflare Workers, powered the same infrastructure that drives the official Gemini CLI.
- [gemini-cli-proxy](https://github.com/nettee/gemini-cli-proxy) - OpenAI-compatible API wrapper for Gemini CLI as an OpenAI-compatible API service, allowing you to enjoy the free Gemini 2.5 Pro model through API!
- [CLIProxyAPI](https://github.com/luispater/CLIProxyAPI) - Wrap Gemini CLI as an OpenAI/Gemini/Claude compatible API service, allowing you to enjoy the free Gemini 2.5 Pro model through API.
- [gemini-cli-mcp-openai-bridge](https://github.com/Intelligent-Internet/gemini-cli-mcp-openai-bridge) - Server application that extends the Google Gemini CLI with MCP toolkit and OpenAI-compatible API bridge.
- [gemini-cli-api](https://github.com/JasonGuoo/gemini-cli-api) - Expose the Gemini CLI ablility to REST ful API.
- [gemini-cli-router](https://github.com/Jasonzhangf/gemini-cli-router) - Routing your Gemini CLI to openai 3rd party providers.

## Commands & Extensions

- [gemini-flow](https://github.com/clduab11/gemini-flow) - rUv's Claude-Flow, translated to the new Gemini CLI; transforming it into an autonomous AI development team.
- [C.O.R.E.](https://github.com/RedPlanetHQ/core) - Your unified, shareable memory layer for coding agents. Compatible with Cursor, Claude Desktop, Claude Code, Gemini CLI, Windsurf, AWS's Kiro, VSCode, Cline.

## MCP Servers

- [ToolsForMCPServer](https://github.com/tanaikech/ToolsForMCPServer) - The Gemini CLI with MCP Server project enables interaction between the Gemini CLI and Google Apps Script for automating Google Workspace tasks.
- [gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) - MCP server that enables AI assistants to interact with Google Gemini CLI, leveraging Gemini's massive token window for large file analysis.
- [mcp-gemini-cli](https://github.com/choplin/mcp-gemini-cli) - A simple MCP (Model Context Protocol) server wrapper for Google's Gemini CLI.
- [gemini-cli-mcp](https://github.com/InfolabAI/gemini-cli-mcp) - Tool that enables using Gemini AI as an MCP server within Claude Code with large file analysis and token savings.
- [gemini-mcp](https://github.com/neriousy/gemini-mcp) - A simple MCP server for using the Gemini CLI.
- [gemini-cli-mcp](https://github.com/0xmountaintop/gemini-cli-mcp) - A Model Context Protocol (MCP) wrapper for Google Gemini CLI that enables AI development tools to interact with Gemini.

## Neovim Plugins

- [gemini-cli.nvim](https://github.com/JonRoosevelt/gemini-cli.nvim) - A Neovim plugin that seamlessly integrates the Gemini CLI into the Neovim environment.
- [gemini-nvim](https://github.com/JunYang-tes/gemini-nvim) - Gemini CLI in neovim - An unofficial Neovim plugin for interacting with Google Gemini CLI.

## Development Frameworks & Orchestration

- [gemini-code-flow](https://github.com/Theopsguide/gemini-code-flow) - AI-powered development orchestration for Gemini CLI - adapted from Claude Code Flow by ruvnet.
- [gemini-cli-commands-demo](https://github.com/pauldatta/gemini-cli-commands-demo) - A proof-of-concept demonstrating a sub-agent orchestration system built within the Gemini CLI.

## Documentation & Learning Resources

- [gemini-cli-extension](https://github.com/philschmid/gemini-cli-extension) - Collection of helpful Gemini CLI extensions and commands.
- [gemini-docs-ext](https://github.com/markmcd/gemini-docs-ext) - Gemini CLI extension that adds Gemini API docs and MCP.

## Demo Collections & Examples

- [gemini-cli-demos](https://github.com/palladius/gemini-cli-demos) - Demos-in-a-box for Gemini CLI.
- [cli-demo-cookbook](https://github.com/ptone/cli-demo-cookbook) - Collection of demo scenario and casts for Gemini CLI.
- [Google-Gemini-CLI](https://github.com/nDimensions-AI/Google-Gemini-CLI) - Master the Gemini CLI: A Live, Interactive Webinar.

## Contributing

Contributions are highly valued!  See [CONTRIBUTING.md](CONTRIBUTING.md).
