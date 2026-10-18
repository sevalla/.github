<!-- From sevalla-design's snippets/github/profile-README.md, with screenshots added. Every image is
     linked from assets.sevalla.com, so it changes when the brand and the app do. -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://assets.sevalla.com/brand/social/github/profile-banner-dark.png" />
  <img src="https://assets.sevalla.com/brand/social/github/profile-banner-light.png" alt="Sevalla. From prompt to production. Deploy applications, databases and static sites, without managing the infrastructure underneath." />
</picture>

Sevalla is the platform for deploying applications, databases and static sites, without managing the infrastructure underneath. You push code; Sevalla builds it, deploys it and keeps it up.

[Sign up](https://sevalla.com/signup) · [Docs](https://docs.sevalla.com) · [API reference](https://api-docs.sevalla.com) · [Status](https://status.sevalla.com) · [Discord](https://discord.gg/sevalla) · [X](https://x.com/sevalla_hosting)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://assets.sevalla.com/screenshots/dark/app-overview.png" />
  <img src="https://assets.sevalla.com/screenshots/light/app-overview.png" alt="An application's overview in the Sevalla dashboard: Cloudflare's CDN and DDoS protection in front, a web server, a worker, a cron job and a job running from acme/storefront, and the database and API it connects to." />
</picture>

## What you can run on Sevalla

| Product | What it is |
| ------- | ---------- |
| **Application hosting** | From GitHub, GitLab, Bitbucket or any Docker registry: if it runs in a container, it runs on Sevalla. |
| **Database hosting** | PostgreSQL, MySQL, MariaDB, Redis and Valkey, with automated backups and Database Studio. |
| **Static site hosting** | Blogs, docs and landing pages, served from Cloudflare's edge network. |
| **Object storage** | S3-compatible buckets for assets, media and files, for any S3 client or SDK. |
| **Pipelines** | Preview environments for pull requests, and promotion from one stage to the next. |

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets.sevalla.com/screenshots/dark/pipeline-board-production-apps.png" />
    <img src="https://assets.sevalla.com/screenshots/light/pipeline-board-production-apps.png" width="49%" alt="A pipeline in Sevalla: preview apps for pull requests, a staging app ready to promote, and production apps." />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://assets.sevalla.com/screenshots/dark/database-studio-sql-console.png" />
    <img src="https://assets.sevalla.com/screenshots/light/database-studio-sql-console.png" width="49%" alt="Database Studio's SQL console: a query on a products table and its result as JSON." />
  </picture>
</p>

Sevalla is SOC 2 Type II certified, with SAML single sign-on and team-based access control.

## Open source

| Repository | What it does |
| ---------- | ------------ |
| [`mcp`](https://github.com/sevalla/mcp) | Sevalla's remote MCP server: deploy, debug and manage Sevalla from any AI agent. |
| [`cli`](https://github.com/sevalla/cli) | Deploy and manage applications, databases and static sites on Sevalla from your terminal. |
| [`sevalla-deploy`](https://github.com/sevalla/sevalla-deploy) | Deploy and promote Sevalla applications and static sites from GitHub Actions. |
| [`terraform-provider-sevalla`](https://github.com/sevalla/terraform-provider-sevalla) | Manage Sevalla applications, databases, static sites and more with Terraform. |
| [`skills`](https://github.com/sevalla/skills) | Agent skills that teach coding agents to deploy and run applications on Sevalla. |

## Get started

1. [Sign up](https://sevalla.com/signup).
2. Connect GitHub, GitLab or Bitbucket, or use an image from any Docker registry.
3. Pick a repository and deploy.
