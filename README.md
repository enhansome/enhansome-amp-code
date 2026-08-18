<!--lint ignore awesome-toc-->

<div align='center'>

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Amp Code with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- subtitle -->

An **unofficial** curated list of resources for Amp, an AI coding agent by Sourcegraph

<!-- image -->

<img width=60% src='https://github.com/user-attachments/assets/00c0b998-0c2c-4b7b-bed7-913039bf00b5' />

<!-- description -->

</div>

<!-- TOC -->

<!--lint disable awesome-toc-->

## Contents

* [Official Resources](#official-resources)
* [Agent Files & Context](#agent-files--context)
* [MCP Servers](#mcp-servers)
* [Projects & Tools](#projects--tools)
* [Editor & IDE Integrations](#editor--ide-integrations)
* [CLI Usage](#cli-usage)
* [Security & Best Practices](#security--best-practices)
* [Community](#community)
* [Contributing](#contributing)

<!-- CONTENT -->

### Official Resources

* [Amp](https://ampcode.com) - Main Amp website.
* [Amp Owner's Manual](https://ampcode.com/manual) - Comprehensive official documentation covering installation, usage, and best practices.
* [Amp CLI](https://www.npmjs.com/package/@sourcegraph/amp) - Official CLI package on npm.
* [Amp for VS Code](https://marketplace.visualstudio.com/items?itemName=sourcegraph.amp) - Official VS Code extension.
* [Amp SDK](https://ampcode.com/manual/sdk) - Official SDK documentation for building on Amp.
* [Raising an Agent Podcast](https://ampcode.com/podcast) - Podcast featuring insights from the Amp team.
* [Amp 101 YouTube Playlist](https://www.youtube.com/playlist?list=PL6zLuuRVa1_hLpciEULtzC3g3u4NJ6TVz) - Official video tutorials.
* [How to Build an Agent](https://ampcode.com/how-to-build-an-agent) - Guide to building AI agents.
* [Amp Chronicle](https://ampcode.com/chronicle) - Official news and announcements.
* [Amp Status](https://ampcodestatus.com) - Service status page.
* [Amp on X](https://x.com/ampcode) - Official Twitter/X account.

### Agent Files & Context

AGENTS.md files provide context and instructions to AI coding agents about your codebase. They help agents understand project structure, coding standards, and specific requirements.

**Examples of AGENTS.md in open source projects:**

* [LangGraph](https://sourcegraph.com/github.com/langchain-ai/langgraph/-/blob/AGENTS.md) - LangChain's graph-based agent framework.
* [Zoekt](https://sourcegraph.com/github.com/sourcegraph/zoekt/-/blob/AGENT.md) - Fast code search by Sourcegraph.
* [Ultimate MCP Client](https://github.com/Dicklesworthstone/ultimate_mcp_client/blob/main/AGENT.md) ⭐ 149 | 🐛 0 | 🌐 Python | 📅 2026-03-22 - Comprehensive MCP client implementation.
* [MCP Advisor](https://sourcegraph.com/github.com/istarwyh/mcpadvisor/-/blob/AGENT.md) - MCP server advisor tool.
* [Use MCP](https://sourcegraph.com/github.com/modelcontextprotocol/use-mcp/-/blob/AGENT.md) - Official MCP usage examples.

### MCP Servers

Model Context Protocol (MCP) enables AI agents to interact with external tools and services. These MCP servers extend Amp's capabilities:

* [Use MCP](https://github.com/modelcontextprotocol/use-mcp) ⚠️ Archived - Official examples and utilities for MCP usage.
* [Ultimate MCP Client](https://github.com/Dicklesworthstone/ultimate_mcp_client) ⭐ 149 | 🐛 0 | 🌐 Python | 📅 2026-03-22 - Comprehensive MCP client for testing and debugging servers.
* [MCP Advisor](https://github.com/istarwyh/mcpadvisor) ⭐ 89 | 🐛 7 | 🌐 TypeScript | 📅 2026-03-07 - Tool to help discover and configure MCP servers.
* [CleanShot MCP](https://github.com/jdorfman/cleanshot-mcp) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2025-07-06 - MCP server for CleanShot X screenshot and recording integration.
* [llm-rules MCP](https://www.npmjs.com/package/llm-rules) - Access Cursor rules dynamically via MCP.

### Projects & Tools

**Documentation & Guides:**

* [Unofficial Amp CLI Documentation](https://github.com/lfglabs-dev/awesome-amp-code/blob/main/docs/amp_cli_docs.md) ⭐ 76 | 🐛 1 | 📅 2026-02-09 - Comprehensive documentation for Amp CLI with examples and best practices.
* [File-Based Amp Prompting Workflows](https://github.com/PriNova/amp-prompting-workflows) ⭐ 27 | 🐛 0 | 📅 2025-07-27 - Collection of file-based sub-agent orchestration workflows for Amp.

**Development Tools:**

* [Tokscale](https://github.com/junhoyeo/tokscale) ⭐ 5,033 | 🐛 59 | 🌐 Rust | 📅 2026-08-18 - CLI tool for tracking token usage from AmpCode and other coding agents.
* [Sandboxed.sh](https://github.com/Th0rgal/sandboxed.sh) ⭐ 485 | 🐛 15 | 🌐 Rust | 📅 2026-08-18 - Self-hosted cloud orchestrator for AI coding agents with isolated Linux environments.
* [Sniff](https://github.com/conikeec/sniff) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2025-07-30 - Misalignment detection in Vibe Coding loops.
* [CodeForge](https://github.com/entrepeneur4lyf/CodeForge) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2025-08-14 - Golang Development tool built with Amp.
* [Unofficial Amp Supervisor](https://github.com/ctrl-cheeb-del/manager) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-28 - TUI control panel for managing multiple Amp CLI instances in parallel.
* [Amp Code Review CI](https://github.com/madhukarkumar/amp-code-review-ci) ⭐ 3 | 🐛 0 | 📅 2025-07-01 - Continuous integration tool for automated code reviews using Amp.
* [Conductor](https://x.com/charliebholtz/status/1963345520543633742) - Run a bunch of Amps in parallel.

**Applications Built with Amp:**

* [Jazzberry AI](https://jazzberry.ai/) - The AI Bug Finder.
* [0.email](https://0.email/) - AI-native email client that manages your inbox.
* [Remote Code](https://remote-code.com/) - Mobile coding platform that brings AI coding agents to your iPhone.
* [SageMap](https://sagemap.netlify.app/) - Interactive belief mapping tool for journal entries.
* [VT Chat](https://vtchat.io.vn/) - Privacy-first AI chat application.
* [HTTPie Collection Viewer](https://httpie.bolaji.de/) - Upload and explore your HTTPie collections.
* [Quad Ops](https://trly.github.io/quad-ops/) - Lightweight GitOps framework for podman containers.
* [PromptVault](https://hex.pm/packages/prompt_vault) - Library for managing prompts and templates in Elixir.
* [CircuitPython Deploy](https://github.com/shantanugoel/circuitpython-deploy) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-06-29 - CircuitPython deployment tool.

**Browser & Misc:**

* [Sourcegraph Chrome Extension](https://chromewebstore.google.com/detail/sourcegraph/dgjhfomjieaadpoljlnidmbg) - Chrome extension for code search and navigation.
* [Sourcegraph Amp AUR](https://github.com/AnirudhKonduru/sourcegraph-amp-aur) ⚠️ Archived - Arch Linux AUR package for Sourcegraph Amp.

### Editor & IDE Integrations

* [amp.nvim](https://github.com/sourcegraph/amp.nvim) ⭐ 200 | 🐛 6 | 🌐 Lua | 📅 2026-08-03 - Official Neovim plugin for Amp coding agent.
* [Amp ACP](https://github.com/tao12345666333/amp-acp) ⭐ 85 | 🐛 9 | 🌐 TypeScript | 📅 2026-07-31 - ACP adapter for Amp Code, enabling Amp to work in the Zed editor.
* [amp.el](https://github.com/shaneikennedy/amp.el) ⭐ 20 | 🐛 1 | 🌐 Emacs Lisp | 📅 2025-06-15 - Emacs integration for Amp coding agent.
* [nvim-amp](https://github.com/aliou/nvim-amp) ⚠️ Archived - Neovim plugin providing syntax highlighting and support for Amp permission and agent files.
* [MyScratchpad VS Code Extension](https://marketplace.visualstudio.com/items?itemName=jccoder.myscratchpad) - VS Code extension for global and workspace-specific scratch files.
* [Amp Dash X](https://www.raycast.com/jdorfman/sourcegraph-amp-dash-x) - Raycast extension for organizing and executing Amp Code prompts.
* [VibeKanban](https://www.vibekanban.com/) - CLI tool for managing your Kanban boards.

### CLI Usage

Amp CLI can be integrated with other command-line tools. Use the `-x` flag for execute mode or pipe input directly:

```bash
# Analyze processes
ps aux > processes.txt | amp -x 'identify processes consuming the most resources in processes.txt'

# Parse whois data
whois example.com | amp -x 'organize and condense this whois information'

# Analyze HTTP headers
curl -Is https://github.com > headers.txt && amp -x 'analyze the http headers in headers.txt and determine the tech stack'

# Check npm dependencies
npm list --json | amp -x 'identify outdated or vulnerable dependencies'
```

### Security & Best Practices

When using AI coding agents, consider these security aspects:

* [Amp Security Reference](https://ampcode.com/security) - Official security documentation and guidelines.
* [Amp Permissions](https://ampcode.com/manual/permissions) - Control what actions the agent can perform.

**Key recommendations:**

* Always review AI-generated code before committing
* Never include API keys or secrets in prompts or AGENTS.md files
* Consider running agents in isolated environments for sensitive projects
* Vet MCP servers before installation

### Community

* 💬 [Relens Community](https://relens.ai/community) - Join the AI coding agents community to share tips, tricks, and workflows.

### Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

#### Contributors

[Thanks goes to these contributors](https://github.com/lfglabs-dev/awesome-amp-code/graphs/contributors) ⭐ 76 | 🐛 1 | 📅 2026-02-09!

***

### Credits

Originally created and maintained by [Justin Dorfman](https://www.justindorfman.com/).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
