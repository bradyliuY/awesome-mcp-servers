# Awesome MCP Servers

> 精心整理的 Model Context Protocol (MCP) 服务器资源列表 — 适用于 Claude、Cursor、Windsurf、Cline、Continue.dev、GitHub Copilot 等所有 MCP 兼容的 AI 智能体。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## 📋 目录

- [Awesome MCP Servers](#awesome-mcp-servers)
  - [📋 目录](#-目录)
  - [什么是 MCP？](#什么是-mcp)
  - [🔨 开发者工具 \& 代码](#-开发者工具--代码)
  - [📁 文件系统 \& 版本控制](#-文件系统--版本控制)
  - [🌐 浏览器自动化 \& Web 抓取](#-浏览器自动化--web-抓取)
  - [🗄️ 数据库 \& 数据存储](#️-数据库--数据存储)
  - [☁️ 云平台 \& DevOps](#️-云平台--devops)
  - [🔍 搜索 \& 文档](#-搜索--文档)
  - [🧠 AI \& 记忆 \& 推理](#-ai--记忆--推理)
  - [🧑‍💼 生产力 \& 协作](#-生产力--协作)
  - [🏦 金融 \& 支付](#-金融--支付)
  - [🔒 安全 \& 合规扫描](#-安全--合规扫描)
  - [🎨 设计 \& 创意 \& 多媒体](#-设计--创意--多媒体)
  - [📡 通信 \& 消息](#-通信--消息)
  - [🧪 测试 \& 质量保证](#-测试--质量保证)
  - [📊 可观测性 \& 监控](#-可观测性--监控)
  - [🛠️ 基础设施 \& 容器](#️-基础设施--容器)
  - [🧩 MCP 客户端支持矩阵](#-mcp-客户端支持矩阵)
  - [📚 权威汇总列表](#-权威汇总列表)
  - [🔧 MCP 安全扫描工具](#-mcp-安全扫描工具)
  - [🚀 快速开始推荐](#-快速开始推荐)
  - [📖 延伸阅读](#-延伸阅读)
  - [🤝 贡献](#-贡献)

## 什么是 MCP？

[Model Context Protocol (MCP)](https://modelcontextprotocol.io) 是一种开放标准，定义了 AI 智能体与外部工具、数据源和服务的交互方式。MCP 服务器是轻量级服务，为 AI 智能体提供结构化的工具、资源和提示，类似于 AI 界的 **USB-C 接口**——一个标准连接所有 AI 工具。

**MCP 的核心优势：**
- 🔌 **标准化** — 统一的协议，所有兼容客户端即插即用
- 🔒 **安全** — 细粒度的权限控制，沙箱运行
- 🌍 **生态丰富** — 数千个社区和官方服务器
- 🤖 **跨平台** — 支持所有主流 AI 编码智能体和桌面应用

**兼容 MCP 的客户端/智能体（2025-2026）：**
| 客户端 | 类型 | MCP 支持 |
|--------|------|----------|
| Claude Code / Claude Desktop | 桌面 + CLI | ✅ 原生支持 |
| Cursor | IDE | ✅ `.cursor/mcp.json` |
| Windsurf | IDE | ✅ `mcp_config.json` |
| Continue.dev | IDE 插件 | ✅ `config.json` |
| GitHub Copilot | IDE | ✅ 原生支持 |
| Cline (VS Code) | IDE 插件 | ✅ 原生支持 |
| Zed | IDE | ✅ 原生支持 |
| Replit Agent | 云端 IDE | ✅ 原生支持 |
| OpenAI Codex CLI | CLI | ✅ 原生支持 |
| Cherry Studio | 桌面 | ✅ 原生支持 |

---

## 🔨 开发者工具 & 代码

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[github-mcp-server](https://github.com/github/github-mcp-server)** | 完整的 GitHub API — 仓库管理、PR、Issues、代码搜索、分支操作 | 31k+ | GitHub 官方 |
| **[github-mcp-server](https://github.com/github/github-mcp-server)** | GitHub MCP 注册中心 — 发现、安装 MCP 服务器 | — | GitHub 官方 |
| **[gitlab-mcp](https://gitlab.com/gitlab-org/gitlab-mcp)** | GitLab 集成 — MR、Issues、CI/CD 流水线 | — | GitLab 官方 |
| **[linear-mcp](https://github.com/linear/linear-mcp)** | Linear 项目管理 — Issue 跟踪、周期、项目 | — | Linear 官方 |
| **[atlassian-mcp](https://github.com/...)** | Jira + Confluence + Compass — 46 个工具 | 5.5k | Atlassian 社区 |
| **[asana-mcp](https://github.com/...)** | Asana 任务管理 — 项目、任务、时间线 | — | 社区 |
| **[clickup-mcp](https://github.com/...)** | ClickUp 项目协作 — 任务、文档、目标 | — | 社区 |
| **[pulumi-mcp](https://github.com/...)** | Pulumi 基础设施即代码 | — | Pulumi 官方 |
| **[terraform-mcp](https://github.com/hashicorp/terraform-mcp)** | Terraform — Provider 发现、计划、应用 | 1.4k | HashiCorp 官方 |
| **[ansible-mcp](https://github.com/...)** | Ansible 自动化 — playbook 执行、编排 | — | Red Hat 社区 |
| **[crossplane-mcp](https://github.com/...)** | Crossplane 控制平面 — 云资源编排 | — | 社区 |

## 📁 文件系统 & 版本控制

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[filesystem-mcp](https://github.com/modelcontextprotocol/servers)** | 安全的文件系统读写 — 受限目录访问 | 87.7k | Anthropic 官方 |
| **[git-mcp](https://github.com/modelcontextprotocol/servers)** | Git 仓库管理 — 提交、日志、分支、diff | 87.7k | Anthropic 官方 |
| **[gitlab-mcp](https://github.com/...)** | GitLab 仓库 + CI/CD 管理 | — | GitLab 官方 |
| **[bitbucket-mcp](https://github.com/...)** | Bitbucket 仓库和 Pipelines 管理 | — | 社区 |
| **[gitee-mcp](https://github.com/...)** | Gitee（码云）仓库和项目管理 | — | 社区 |

## 🌐 浏览器自动化 & Web 抓取

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[playwright-mcp](https://github.com/microsoft/playwright-mcp)** | 浏览器自动化 — 通过可访问性树进行无头浏览器操作 | 34.7k | **Microsoft 官方** |
| **[chrome-devtools-mcp](https://github.com/...)** | Chrome DevTools 协议 — Console、Network、Performance | 45.8k | 社区 |
| **[puppeteer-mcp](https://github.com/...)** | Puppeteer 浏览器自动化 | — | Google 社区 |
| **[firecrawl-mcp](https://github.com/nicholasgriffintn/firecrawl-mcp)** | Web 抓取 → 干净 Markdown | 6.8k | Firecrawl 官方 |
| **[browserbase-mcp](https://github.com/browserbase/mcp-server)** | 云端无头浏览器 — 隐身代理、验证码绕过 | — | Browserbase 官方 |
| **[brightdata-mcp](https://github.com/...)** | Bright Data Web 解锁 — ~70 个工具，代理网络 | — | Bright Data 官方 |
| **[jina-reader-mcp](https://github.com/...)** | Jina AI Reader — URL 转 LLM 友好格式 | — | Jina AI 官方 |
| **[markdown-down](https://github.com/...)** | Markdown 转换 — URL/HTML 内容转 Markdown | — | 社区 |

## 🗄️ 数据库 & 数据存储

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[postgres-mcp](https://github.com/modelcontextprotocol/servers)** | PostgreSQL — 只读 Schema 和查询 | 87.7k | Anthropic 官方 |
| **[sqlite-mcp](https://github.com/modelcontextprotocol/servers)** | SQLite — 本地优先，适合原型开发 | 87.7k | Anthropic 官方 |
| **[mysql-mcp](https://github.com/...)** | MySQL/MariaDB — Schema 探索、SQL 执行 | — | 社区 |
| **[mongodb-mcp](https://github.com/...)** | MongoDB — Schema 检查、JSON 查询 | — | 社区 |
| **[supabase-mcp](https://github.com/...)** | Supabase 全管理 — 表、Auth、函数、Edge Functions | — | Supabase 官方 |
| **[redis-mcp](https://github.com/...)** | Redis — 键值操作、缓存管理 | — | 社区 |
| **[elasticsearch-mcp](https://github.com/elastic/elasticsearch-mcp)** | Elasticsearch — 自然语言转 ES 查询 | — | **Elastic 官方** |
| **[bigquery-mcp](https://github.com/...)** | Google BigQuery — 企业数据仓库查询 | — | Google 社区 |
| **[snowflake-mcp](https://github.com/...)** | Snowflake — 数据仓库查询和 Schema 管理 | — | 社区 |
| **[dynamodb-mcp](https://github.com/...)** | AWS DynamoDB — 表操作、查询 | — | AWS 社区 |
| **[clickhouse-mcp](https://github.com/...)** | ClickHouse — 列式数据库查询 | — | 社区 |
| **[couchbase-mcp](https://github.com/...)** | Couchbase — NoSQL 文档操作 | — | 社区 |
| **[neo4j-mcp](https://github.com/...)** | Neo4j 图数据库 — Cypher 查询生成、知识图谱 | — | 社区 |
| **[qdrant-mcp](https://github.com/...)** | Qdrant 向量数据库 — 语义搜索、向量存储 | 1.4k | Qdrant 社区 |

## ☁️ 云平台 & DevOps

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[aws-mcp](https://github.com/awslabs/mcp)** | AWS 服务套件 — Docs、CDK、Cost、DynamoDB、S3、Bedrock 等 | 9.3k | **AWS Labs 官方** |
| **[s3-mcp](https://github.com/...)** | AWS S3 — 对象存储操作 | — | 社区 |
| **[cloudflare-mcp](https://github.com/cloudflare/mcp-server-cloudflare)** | Cloudflare — Workers、KV、R2、D1、AI | 3.9k | **Cloudflare 官方** |
| **[google-cloud-mcp](https://github.com/...)** | Google Cloud — GCS、GKE、Cloud Run 等 | — | Google 社区 |
| **[azure-mcp](https://github.com/...)** | Azure 资源管理 | — | Microsoft 社区 |
| **[digitalocean-mcp](https://github.com/...)** | DigitalOcean — Droplets、K8s、数据库 | — | 社区 |
| **[vercel-mcp](https://github.com/...)** | Vercel — 部署、环境变量、日志 | — | Vercel 官方 |
| **[netlify-mcp](https://github.com/...)** | Netlify — 站点部署、函数、表单 | — | 社区 |
| **[heroku-mcp](https://github.com/...)** | Heroku — 应用管理、日志、扩展 | — | 社区 |
| **[render-mcp](https://github.com/...)** | Render — 服务部署、数据库管理 | — | 社区 |
| **[flyio-mcp](https://github.com/...)** | Fly.io — 应用部署、Volume 管理 | — | 社区 |
| **[instanode-mcp](https://github.com/InstaNode-dev/mcp)** | 即时开发基础设施 — Postgres/Redis/MongoDB/S3 即时创建 | — | InstaNode 官方 |

## 🔍 搜索 & 文档

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[context7](https://github.com/upstash/context7)** | ⭐ 库文档注入 — 版本特定的框架/Library 文档 | 58.6k | **Upstash 官方** |
| **[fetch-mcp](https://github.com/modelcontextprotocol/servers)** | URL → Markdown 内容获取 | 87.7k | Anthropic 官方 |
| **[brave-search-mcp](https://github.com/modelcontextprotocol/servers)** | Brave 网页搜索 — 无需 API Key | 87.7k | Anthropic 官方 |
| **[perplexity-mcp](https://github.com/...)** | Perplexity AI 搜索 — 带来源的合成答案 | 2.3k | Perplexity 官方 |
| **[exa-mcp](https://github.com/...)** | Exa AI 搜索 — 语义搜索引擎 | — | Exa 官方 |
| **[tavily-mcp](https://github.com/...)** | Tavily 搜索 — AI 优化的搜索引擎 | — | Tavily 官方 |
| **[markitdown-mcp](https://github.com/microsoft/markitdown)** | 文件转 Markdown — 支持 Office、PDF、HTML、CSV 等 | 159k | **Microsoft 官方** |
| **[meilisearch-mcp](https://github.com/...)** | Meilisearch — 搜索索引管理 | — | 社区 |
| **[typesense-mcp](https://github.com/...)** | Typesense — 搜索服务管理 | — | 社区 |
| **[algolia-mcp](https://github.com/...)** | Algolia — 搜索索引和 API 管理 | — | 社区 |

## 🧠 AI & 记忆 & 推理

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[memory-mcp](https://github.com/modelcontextprotocol/servers)** | 持久化知识图谱记忆 — 实体和关系存储 | 87.7k | Anthropic 官方 |
| **[sequential-thinking-mcp](https://github.com/modelcontextprotocol/servers)** | 结构化推理 — 多步推理步骤和分支 | — | Anthropic 官方 |
| **[codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp)** | 代码库 → 知识图谱 — 158 种语言 | 26.3k | DeusData |
| **[mem0-mcp-server](https://github.com/odin2-hash/mem0-mcp-server)** | 多数据库记忆管理 — PostgreSQL+pgvector、Neo4j、Redis | — | 社区 |
| **[rag-memory-mcp](https://github.com/ttommyth/rag-memory-mcp)** | RAG 记忆系统 — SQLite + sqlite-vec、混合搜索 | — | 社区 |
| **[mcp-memory-libsql](https://github.com/joleyline/mcp-memory-libsql)** | 高性能记忆 — libSQL、向量搜索、关系管理 | — | 社区 |
| **[velixar-mcp-server](https://github.com/VelixarAi/velixar-mcp-server)** | 持久 AI 记忆 — 知识图谱、信念追踪、矛盾检测 | — | Velixar AI |
| **[mcp-neo4j-memory](https://github.com/...)** | Neo4j 知识图谱记忆 — Python、384-dim 嵌入 | — | 社区 |
| **[memory-wiki](https://github.com/...)** | Rust 高性能记忆 — BM25 + 向量 + GraphRAG | — | 社区 |
| **[huggingface-mcp](https://github.com/...)** | HuggingFace — 模型搜索、推理、数据集访问 | — | 社区 |
| **[openai-mcp](https://github.com/...)** | OpenAI API — 模型列表、推理、Embeddings | — | 社区 |
| **[anthropic-mcp](https://github.com/...)** | Anthropic API — Claude 模型调用 | — | 社区 |

## 🧑‍💼 生产力 & 协作

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[notion-mcp](https://github.com/...)** | Notion — 页面、数据库、块级操作 | — | Notion 社区 |
| **[google-drive-mcp](https://github.com/modelcontextprotocol/servers)** | Google 云端硬盘 — Docs、Sheets、Slides | 87.7k | Anthropic 官方 |
| **[google-calendar-mcp](https://github.com/...)** | Google 日历 — 日程查询、创建、更新 | — | 社区 |
| **[google-mail-mcp](https://github.com/...)** | Gmail — 邮件搜索、发送、管理 | — | 社区 |
| **[microsoft-teams-mcp](https://github.com/...)** | Microsoft Teams — 消息、频道、会议 | — | Microsoft 社区 |
| **[outlook-mcp](https://github.com/...)** | Outlook 邮件和日历 | — | 社区 |
| **[office365-mcp](https://github.com/...)** | Office 365 全面集成 | — | 社区 |
| **[obsidian-mcp](https://github.com/...)** | Obsidian 笔记 — Vault 读写、搜索 | 4k | 社区 |
| **[miro-mcp](https://github.com/...)** | Miro 白板 — 看板、图表、协作 | — | Miro 官方 |
| **[figjam-mcp](https://github.com/...)** | FigJam — 白板协作 | — | Figma 官方 |
| **[slack-mcp](https://github.com/modelcontextprotocol/servers)** | Slack — 消息读写、频道搜索、文件分享 | 87.7k | Anthropic 官方 |
| **[discord-mcp](https://github.com/...)** | Discord — 消息、频道、语音频道管理 | — | 社区 |
| **[telegram-mcp](https://github.com/...)** | Telegram — 消息发送、群组管理 | — | 社区 |
| **[trello-mcp](https://github.com/...)** | Trello — 看板、列表、卡片 | — | 社区 |
| **[todoist-mcp](https://github.com/...)** | Todoist — 任务和项目管理 | — | 社区 |
| **[locus-mcp](https://github.com/jonybur-oc/locus)** | 用户故事上下文 — stories.yaml AI 上下文规范 | — | Locus 官方 |

## 🏦 金融 & 支付

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[stripe-mcp](https://github.com/Methods-Lab/MCP-Server-Stripe)** | Stripe 支付 — 客户、支付、订阅、发票、产品（含安全护栏） | — | Methods-Lab |
| **[shopify-mcp](https://github.com/...)** | Shopify 电商 — 商品、订单、库存、分析 | — | Shopify 社区 |
| **[paypal-mcp](https://github.com/...)** | PayPal 支付 — Agent Toolkit 集成 | — | PayPal 社区 |
| **[square-mcp](https://github.com/...)** | Square 支付 — 交易、客户、目录 | — | 社区 |
| **[coinbase-mcp](https://github.com/...)** | Coinbase — 钱包、交易、x402 支付 | — | Coinbase 社区 |
| **[agentic-payments](https://github.com/...)** | 智能体支付基础设施 — AP2 + ACP 双协议 | — | 社区 |
| **[plaid-mcp](https://github.com/...)** | Plaid 金融数据 — 账户、交易、身份验证 | — | 社区 |
| **[quickbooks-mcp](https://github.com/...)** | QuickBooks 会计 — 发票、费用、账户 | — | 社区 |
| **[xero-mcp](https://github.com/...)** | Xero 会计 — 账单、银行交易、对账 | — | 社区 |
| **[yahoo-finance-mcp](https://github.com/...)** | Yahoo Finance — 股票行情、市场数据 | — | 社区 |
| **[coingecko-mcp](https://github.com/...)** | CoinGecko — 加密货币数据和价格 | — | 社区 |

## 🔒 安全 & 合规扫描

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[mcpshield](https://github.com/mcpshield/mcpshield)** | MCP 供应链安全 — 检测拼写错误、CVE、凭据泄露 | — | MCPShield |
| **[mcpshield](https://github.com/mcpshield/mcpshield)** | 安全扫描 — CI/CD 集成、自动发现配置 | — | MCPShield |
| **[security-mcp-suite](https://github.com/...)** | 自主安全扫描 — nmap、nuclei、trivy、sqlmap、gitleaks | — | 社区 |
| **[snyk-mcp](https://github.com/...)** | Snyk 漏洞扫描 — 依赖、容器、代码 | — | Snyk 官方 |
| **[semgrep-mcp](https://github.com/...)** | Semgrep 代码分析 — SAST、策略即代码 | — | Semgrep 社区 |
| **[trivy-mcp](https://github.com/...)** | Trivy 安全扫描 — 容器、K8s、依赖 | — | 社区 |
| **[burpsuite-mcp](https://github.com/...)** | Burp Suite — 渗透测试集成 | — | 社区 |
| **[sonarqube-mcp](https://github.com/...)** | SonarQube — 代码质量和安全分析 | — | 社区 |
| **[hashicorp-vault-mcp](https://github.com/...)** | HashiCorp Vault — 密钥管理、动态 Secret | — | 社区 |

## 🎨 设计 & 创意 & 多媒体

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[figma-mcp](https://github.com/...)** | Figma — 设计文件读写、组件库、评论 | — | **Figma 官方** |
| **[penpot-mcp](https://github.com/...)** | Penpot — 开源设计工具集成 | — | 社区 |
| **[blender-mcp](https://github.com/ahujasid/blender-mcp)** | Blender 3D — 提示词辅助建模和场景创建 | 23.2k | 社区 |
| **[canva-mcp](https://github.com/...)** | Canva — 设计创建、编辑、导出 | — | Canva 官方 |
| **[excalidraw-mcp](https://github.com/...)** | Excalidraw — 白板和图表创建 | — | 社区 |
| **[diagrams-mcp](https://github.com/...)** | Diagrams.net — 架构图创建 | — | 社区 |
| **[midjourney-mcp](https://github.com/...)** | Midjourney — AI 图像生成 | — | 社区 |
| **[dalle-mcp](https://github.com/...)** | DALL-E — OpenAI 图像生成 | — | 社区 |
| **[stable-diffusion-mcp](https://github.com/...)** | Stable Diffusion — 本地图像生成 | — | 社区 |
| **[ffmpeg-mcp](https://github.com/...)** | FFmpeg — 音视频处理 | — | 社区 |

## 📡 通信 & 消息

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[slack-mcp](https://github.com/modelcontextprotocol/servers)** | Slack 消息 — 搜索、发送、管理频道 | 87.7k | Anthropic 官方 |
| **[discord-mcp](https://github.com/...)** | Discord — 消息、频道管理、语音 | — | 社区 |
| **[telegram-mcp](https://github.com/...)** | Telegram Bot — 消息发送、接收 | — | 社区 |
| **[whatsapp-mcp](https://github.com/...)** | WhatsApp Business — 消息、模板 | — | 社区 |
| **[twilio-mcp](https://github.com/...)** | Twilio — SMS、语音、WhatsApp API | — | 社区 |
| **[sendgrid-mcp](https://github.com/...)** | SendGrid — 邮件发送、模板管理 | — | 社区 |
| **[resend-mcp](https://github.com/...)** | Resend — 邮件 API | — | 社区 |
| **[mailgun-mcp](https://github.com/...)** | Mailgun — 邮件服务管理 | — | 社区 |
| **[postmark-mcp](https://github.com/...)** | Postmark — 事务邮件 | — | 社区 |
| **[ses-mcp](https://github.com/...)** | AWS SES — 邮件发送 | — | 社区 |

## 🧪 测试 & 质量保证

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[playwright-mcp](https://github.com/microsoft/playwright-mcp)** | E2E 测试 — 浏览器自动化测试 | 34.7k | **Microsoft 官方** |
| **[cypress-mcp](https://github.com/...)** | Cypress — 组件和 E2E 测试 | — | 社区 |
| **[jest-mcp](https://github.com/...)** | Jest — 单元测试和快照测试 | — | 社区 |
| **[vitest-mcp](https://github.com/...)** | Vitest — 快速单元测试 | — | 社区 |
| **[selenium-mcp](https://github.com/...)** | Selenium — 跨浏览器测试 | — | 社区 |
| **[postman-mcp](https://github.com/...)** | Postman — API 测试和集合管理 | — | Postman 官方 |
| **[k6-mcp](https://github.com/...)** | Grafana k6 — 性能/负载测试 | — | 社区 |
| **[locust-mcp](https://github.com/...)** | Locust — 分布式负载测试 | — | 社区 |
| **[artillery-mcp](https://github.com/...)** | Artillery — 性能和压力测试 | — | 社区 |

## 📊 可观测性 & 监控

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[sentry-mcp](https://github.com/modelcontextprotocol/servers)** | Sentry — 错误和性能问题检索 | 87.7k | Anthropic 官方 |
| **[grafana-mcp](https://github.com/...)** | Grafana — Dashboard 查询、Prometheus、Loki | — | Grafana 官方 |
| **[datadog-mcp](https://github.com/...)** | Datadog — 指标、日志、APM、Dashboard | — | Datadog 官方 |
| **[newrelic-mcp](https://github.com/...)** | New Relic — APM、浏览器监控、日志 | — | 社区 |
| **[prometheus-mcp](https://github.com/...)** | Prometheus — 指标查询、告警管理 | — | 社区 |
| **[loki-mcp](https://github.com/...)** | Grafana Loki — 日志查询和分析 | — | 社区 |
| **[elastic-observer-mcp](https://github.com/...)** | Elastic Observability — 日志、APM、安全 | — | Elastic 官方 |
| **[uptime-mcp](https://github.com/...)** | UptimeRobot — 监控状态管理 | — | 社区 |
| **[statuspage-mcp](https://github.com/...)** | Atlassian Statuspage — 事件管理 | — | 社区 |
| **[pagerduty-mcp](https://github.com/...)** | PagerDuty — 事件响应和排班 | — | 社区 |
| **[opsgenie-mcp](https://github.com/...)** | Opsgenie — 告警管理和排班表 | — | 社区 |

## 🛠️ 基础设施 & 容器

| MCP 服务器 | 描述 | ⭐ Stars | 维护方 |
|-----------|------|----------|--------|
| **[docker-mcp](https://github.com/...)** | Docker — 容器管理、镜像、Compose | — | Docker 官方 |
| **[kubernetes-mcp](https://github.com/...)** | Kubernetes — CRUD 资源、Helm、Tekton | 1.7k | 社区 |
| **[terraform-mcp](https://github.com/hashicorp/terraform-mcp)** | Terraform — Provider 发现、计划、应用 | 1.4k | **HashiCorp 官方** |
| **[pulumi-mcp](https://github.com/...)** | Pulumi — IaC 跨云管理 | — | Pulumi 官方 |
| **[ansible-mcp](https://github.com/...)** | Ansible — Playbook 执行和 CMDB | — | Ansible 社区 |
| **[nix-mcp](https://github.com/...)** | Nix/NixOS — 包管理、配置 | — | 社区 |
| **[helm-mcp](https://github.com/...)** | Helm — K8s Chart 管理、部署 | — | 社区 |
| **[kubectl-mcp](https://github.com/...)** | kubectl — K8s 集群管理 | — | 社区 |
| **[vagrant-mcp](https://github.com/...)** | Vagrant — 虚拟机管理 | — | HashiCorp 社区 |
| **[proxmox-mcp](https://github.com/...)** | Proxmox VE — 虚拟化管理 | — | 社区 |
| **[vsphere-mcp](https://github.com/...)** | VMware vSphere — 虚拟机、ESXi 管理 | — | 社区 |

## 🧩 MCP 客户端支持矩阵

以下 MCP 服务器明确支持多客户端（不仅仅是 Claude）：

| MCP 服务器 | Claude | Cursor | Windsurf | Continue | Copilot | Cline | Zed | 配置方式 |
|-----------|--------|--------|----------|----------|---------|-------|-----|----------|
| **[instanode-mcp](https://github.com/InstaNode-dev/mcp)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | `npx -y @instanode/mcp@latest` |
| **[locus-mcp](https://github.com/jonybur-oc/locus)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | `npx -y @locus-dev/mcp-server` |
| **[velixar-mcp](https://github.com/VelixarAi/velixar-mcp-server)** | ✅ | ✅ | ✅ | ✅ | — | ✅ | ✅ | Python/pip |
| **[clawresearch-mcp](https://github.com/...)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | `pip install clawresearch-mcp` |
| **[buywhere-mcp](https://github.com/...)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | `npx -y @buywhere/mcp-server` |
| **[zui-mcp](https://github.com/...)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | `npx -y @zui.react/mcp` |
| **[decantr-mcp](https://github.com/...)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | `npx @decantr/mcp-server` |
| **[clayton-forge-mcp](https://github.com/...)** | ✅ | ✅ | ✅ | ✅ | — | ✅ | — | `npx clayton-forge-mcp` |

**各客户端配置方式：**
- **Cursor**: `.cursor/mcp.json`
- **Windsurf**: `~/.codeium/windsurf/mcp_config.json`
- **Continue.dev**: `~/.continue/config.json`
- **Claude Desktop**: `claude_desktop_config.json`
- **Cline (VS Code)**: VS Code 设置 → Cline → MCP Servers

## 📚 权威汇总列表

以下是不需要自己收集整理、直接可用的优质汇总资源：

| 资源名 | 描述 | 服务器数量 | 更新频率 |
|--------|------|-----------|----------|
| **[Awesome-MCP](https://github.com/AlexMili/Awesome-MCP)** | 按场景分类，自动刷新活动和星标 | 1000+ | 持续更新 |
| **[best-of-mcp-servers](https://github.com/tolkonepiu/best-of-mcp-servers)** | 🏆 按质量评分排名的 MCP 服务器，34 个分类 | **400 个** | **每周更新** |
| **[awesome-mcp-registry](https://github.com/sunnamed434/awesome-mcp-registry)** | AI 策划 + 评分（GPT-4.1-mini），自动更新 | 数千 | **每周更新** |
| **[awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers)** | 广泛覆盖 + 安全警告标注 | 大量 | 持续更新 |
| **[awesome-secure-mcp-servers](https://github.com/fuzzylabs/awesome-secure-mcp-servers)** | 🔒 安全验证的服务器（mcp-scan 评分） | 精选 | 持续更新 |
| **[bgizdov/awesome-mcp-servers](https://github.com/bgizdov/awesome-mcp-servers)** | **自动生成**，51 种语言 | **7,273 个** | **每日更新** |
| **[awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)** | MCP 客户端汇总（非服务器） | 大量 | 持续更新 |
| **[MCPCorpus 数据集](https://huggingface.co/papers/2506.23474)** | 学术研究用数据集，~14K 个服务器 | ~14,000 | 定期同步 |
| **[PulseMCP 目录](https://www.pulsemcp.com/servers)** | 在线 MCP 服务器目录 | **20,000+** | **每日更新** |
| **[GitHub MCP 注册中心](https://github.com/marketplace?type=mcp)** | GitHub 官方 MCP 市场 | — | 持续更新 |

## 🔧 MCP 安全扫描工具

在引入 MCP 服务器之前，建议使用以下工具进行安全审计：

| 工具 | 描述 | 特点 |
|------|------|------|
| **[MCPSec](https://github.com/mcp-shark/MCPSec)** | 最全面的安全审计 — 34 个安全发现，6 个审计器 | CI/CD 门控、CVSS 阈值、SARIF 输出 |
| **[MCPShield](https://github.com/mcpshield/mcpshield)** | 供应链安全 — 检测拼写错误、CVE、凭据泄露 | 自动发现 10+ 客户端配置 |
| **[mcp-server-security-scanner](https://www.npmjs.com/package/mcp-server-security-scanner)** | 生产级扫描 — 5 个核心工具 | CVE 数据库、SOC 2 合规检查 |
| **[ghostprobe](https://github.com/...)** | 红队探测 — 工具投毒、隐藏指令检测 | 离线分析、随时间变化快照 diff |
| **[mcp-security-scan](https://www.npmjs.com/package/mcp-security-scan)** | 零配置 CLI — `npx` 即刻运行 | 自动发现 10+ 客户端配置 |

## 🚀 快速开始推荐

### 对于大多数开发者（入门组合）

```
1. Filesystem MCP     — 安全的文件读写
2. GitHub MCP         — 仓库 + PR + Issues
3. Fetch MCP          — Web 内容获取
4. Context7           — 实时库文档（58k+ ⭐）
5. Playwright MCP     — 浏览器自动化（Microsoft 维护）
```

### 对于开发团队（生产环境）

```
1. PostgreSQL/MongoDB MCP   — 数据库访问
2. Sentry MCP               — 错误监控
3. Grafana MCP              — 可观测性
4. Slack MCP                — 团队通信
5. Docker/K8s MCP           — 容器/编排管理
6. Sequential Thinking MCP  — 复杂推理
```

### 全栈项目推荐组合

```json
{
  "mcpServers": {
    "filesystem": { "command": "npx", "args": ["-y", "@modelcontextprotocol/server-filesystem", "<path>"] },
    "github": { "command": "npx", "args": ["-y", "@modelcontextprotocol/server-github"] },
    "fetch": { "command": "npx", "args": ["-y", "@modelcontextprotocol/server-fetch"] },
    "context7": { "command": "npx", "args": ["-y", "@upstash/context7"] },
    "playwright": { "command": "npx", "args": ["-y", "@playwright/mcp"] },
    "postgres": { "command": "npx", "args": ["-y", "@modelcontextprotocol/server-postgres", "<connection-string>"] }
  }
}
```

## 📖 延伸阅读

- [MCP 官方文档](https://modelcontextprotocol.io) — 协议规范、快速开始、最佳实践
- [MCP 规范 (GitHub)](https://github.com/modelcontextprotocol/specification) — 协议实现细节
- [Anthropic MCP 博客](https://www.anthropic.com/news/model-context-protocol) — MCP 介绍文章
- [MCP 注册中心](https://registry.modelcontextprotocol.io) — 官方 MCP 服务器注册中心
- [MCP 服务器基准测试](https://github.com/OrrisTech/agent-eval) — 各 MCP 服务器性能对比

## 🤝 贡献

欢迎提交 PR 添加新的 MCP 服务器或更新现有信息！请确保：

1. 服务器是公开可用的
2. 提供准确的描述和分类
3. 注明维护方（官方/社区）
4. 如果可能，标注 MCP 客户端兼容性

---

> **注意**: 星标数（⭐）可能随时间变化，数据采集于 2026 年 7 月。使用任何 MCP 服务器前，请通过安全扫描工具验证其安全性。
>
> *本列表定期更新，欢迎 Star 和 Fork！*
