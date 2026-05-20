[![Sevalla](https://github.com/user-attachments/assets/02ab5e4e-cdc3-4567-bbcb-5418a0088cf1)](https://sevalla.com)

<p align="center">
  <a href="https://sevalla.com/signup">Get Started</a> ·
  <a href="https://docs.sevalla.com">Docs</a> ·
  <a href="https://api-docs.sevalla.com">API Reference</a> ·
  <a href="https://mcp.sevalla.com/mcp">MCP Server</a> ·
  <a href="https://status.sevalla.com">Status</a>
</p>

## What is Sevalla?

Sevalla is a PaaS built on **Kubernetes** and **Cloudflare's edge network**. You push code, we handle builds, scaling, networking, TLS, CDN, and monitoring.

No YAML. No Terraform required. No cluster management. Just `git push` and deploy — or hand it off to your coding agent.

## Products

### ⚡ Application Hosting

Deploy from GitHub, GitLab, Bitbucket, or any Docker registry. If it runs in a container, it runs on Sevalla.

- Buildpacks, Nixpacks, or your own Dockerfile
- Cloudflare CDN and edge caching
- Custom domains with automatic TLS
- Environment variables and secrets management
- Real-time logs, web terminal, and analytics
- Preview environments on every pull request
- Deployment pipelines and one-click rollbacks
- 25 data center regions worldwide

### 🗄️ Database Hosting

Managed databases with automated backups, real-time monitoring, and built-in tooling.

| Engine | Description |
|--------|-------------|
| PostgreSQL | Production-ready relational database |
| MySQL | Widely adopted, battle-tested |
| MariaDB | MySQL-compatible, community-driven |
| Redis | In-memory data store and cache |
| Valkey | Open-source Redis alternative |

Every database includes **Database Studio** for in-browser queries, import/export tooling, and automated backup scheduling.

### 🌐 Static Site Hosting

Deploy to **Cloudflare's edge network**. Blogs, portfolios, docs sites, landing pages — all deployed globally and fast. First-class support for Astro, Next.js, Nuxt, SvelteKit, Remix, TanStack, and friends.

### 📦 Object Storage

S3-compatible bucket storage for static assets, media, and files. Works with any S3 client or SDK.

### 🔀 Load Balancers

Route traffic across multiple applications behind a single domain. Built-in analytics, custom domains, and zero-config TLS.

## 🤖 Coding Agents & MCP

Sevalla ships an official **Model Context Protocol (MCP) server** so AI coding agents can deploy apps, query logs, provision databases, and manage infrastructure through natural conversation.

**Endpoint:** `https://mcp.sevalla.com/mcp` (OAuth — no API keys to paste)

The server uses the [Code Mode MCP pattern](https://github.com/sevalla-hosting/mcp): two general-purpose tools (`search` + `execute`) instead of hundreds of endpoint-specific ones, cutting context-window usage by ~99% versus traditional MCP servers.

**Supported clients:**

```bash
# Claude Code
claude mcp add --transport http sevalla https://mcp.sevalla.com/mcp
```

Also works with **Cursor**, **Codex**, **Windsurf**, and **OpenCode** — see the [coding agents quick starts](https://docs.sevalla.com/quick-starts/coding-agents/overview).

## 🛠️ Developer Tools

| Tool | Description |
|------|-------------|
| [**CLI**](https://github.com/sevalla-hosting/cli) | `brew install sevalla-hosting/tap/sevalla` — deploy, manage databases, tail logs, run terminals |
| [**MCP Server**](https://github.com/sevalla-hosting/mcp) | Official remote MCP server for the public API |
| [**Terraform Provider**](https://github.com/sevalla-hosting/terraform-provider-sevalla) | Manage Sevalla infrastructure as code |
| [**GitHub Action**](https://github.com/sevalla-hosting/sevalla-deploy) | Deploy and promote apps and static sites from CI |
| [**REST API**](https://api-docs.sevalla.com) | Automate deploys, rollbacks, scaling, and provisioning |
| [**Webhooks**](https://docs.sevalla.com) | Plug into your existing CI/CD tooling |

## Developer Experience

- **Git-native deployments** — push to a branch, trigger a build
- **Preview environments** — every PR gets its own URL
- **Deployment pipelines** — promote builds across Dev, QA, and Prod
- **Full API + CLI + Terraform + MCP** — script anything, from anywhere

## Security & Compliance

- **SOC 2 Type II** certified
- **SAML SSO** with Google Workspace, Microsoft Entra, Okta, OneLogin, Ping Identity
- Team-based access control and project organization
- Uptime SLAs with real-time [status monitoring](https://status.sevalla.com)
- Responsible disclosure: [security.sevalla.com](https://docs.sevalla.com/service-information/disclose-a-vulnerability)

## Quick Start

1. [Sign up](https://sevalla.com/signup) for an account
2. Connect your Git provider — or point your AI agent at `https://mcp.sevalla.com/mcp`
3. Select a repo and deploy

## Links

🔗 [sevalla.com](https://sevalla.com) — Main site
📖 [docs.sevalla.com](https://docs.sevalla.com) — Documentation
🛠️ [api-docs.sevalla.com](https://api-docs.sevalla.com) — API reference
🤖 [mcp.sevalla.com](https://mcp.sevalla.com/mcp) — MCP server
💬 [Discord](https://discord.gg/gfSRfCvz) — Community
🐦 [X / Twitter](https://x.com/sevalla_hosting) — Updates
💰 [Pricing](https://sevalla.com/pricing) — Plans & pricing
