# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Model Context Protocol (MCP) servers — the open standard for connecting AI models to tools, data, and services.

## Contents

- [Official / Reference Implementations](#official--reference-implementations)
- [File System & Storage](#file-system--storage)
- [Databases](#databases)
- [Web & Browser](#web--browser)
- [Developer Tools](#developer-tools)
- [Communication](#communication)
- [Marketing](#marketing)
- [AI & ML](#ai--ml)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Productivity](#productivity)
- [Search](#search)
- [Contributing](#contributing)

---

## Official / Reference Implementations

- [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) - Official reference implementations by Anthropic: filesystem, Git, GitHub, Google Drive, PostgreSQL, Slack, and more.

## File System & Storage

- [filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Secure file operations with configurable access controls.
- [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - File access and search for Google Drive.

## Databases

- [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - Read-only database access with schema inspection.
- [SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - Database interaction and business intelligence with SQLite.

## Web & Browser

- [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Browser automation and web scraping.
- [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Web content fetching and conversion for efficient LLM usage.

## Developer Tools

- [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Tools to read, search, and manipulate Git repositories.
- [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Repository management, file operations, and GitHub API integration.
- [GitLab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab API integration enabling project management.

## Communication

- [Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Channel management and messaging capabilities for Slack.

## Marketing

- [NotFair](https://notfair.co/api/mcp/google_ads) - Hosted Google Ads MCP server. Diagnose campaigns, recommend bid/budget/keyword changes, and execute approved updates via the Google Ads API with a human-approval gate.

## AI & ML

- [EverArt](https://github.com/modelcontextprotocol/servers/tree/main/src/everart) - AI image generation using various models.

## Cloud & Infrastructure

- [AWS KB Retrieval](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval-server) - Retrieval from AWS Knowledge Base using Bedrock Agent Runtime.

## Productivity

- [Google Maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) - Location services, directions, and place details.
- [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Knowledge graph-based persistent memory system.

## Search

- [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Web and local search using Brave's Search API.

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add an MCP server:
1. Fork this repository
2. Add your server to the relevant category in alphabetical order
3. Use the format: `- [Name](link) - Brief description.`
4. Submit a pull request

Please ensure your server:
- Is publicly accessible
- Has a clear description
- Implements the MCP specification
- Has documentation or a README

## License

[CC0 1.0](LICENSE)
