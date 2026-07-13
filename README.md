<div align="center">
  <h1>Awesome MCP Servers <img src="https://awesome.re/badge.svg" alt="Awesome"></h1>
  <p>
    <strong>精选的 Model Context Protocol (MCP) 服务器资源列表</strong><br>
    适用于 <b>Claude</b>、<b>Cursor</b>、<b>Windsurf</b>、<b>Cline</b>、<b>Continue.dev</b>、<b>GitHub Copilot</b> 等所有 MCP 兼容的 AI 智能体
  </p>
  <p>
    <a href="#-服务器分类">服务器分类</a> •
    <a href="#-mcp-客户端">客户端</a> •
    <a href="#-工具与-sdk">工具 & SDK</a> •
    <a href="#-安全审计">安全审计</a> •
    <a href="#-权威汇总列表">汇总列表</a> •
    <a href="#-快速开始">快速开始</a>
  </p>
  <p>
    <a href="https://github.com/bradyliuY/awesome-mcp-servers">
      <img src="https://img.shields.io/github/stars/bradyliuY/awesome-mcp-servers?style=flat-square&label=Stars" alt="Stars">
    </a>
    <a href="https://github.com/bradyliuY/awesome-mcp-servers/blob/main/CONTRIBUTING.md">
      <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
    </a>
    <a href="https://modelcontextprotocol.io">
      <img src="https://img.shields.io/badge/MCP-Spec%20v2025--11--25-blue?style=flat-square" alt="MCP Spec">
    </a>
  </p>
  <p><i>A curated, categorized list of MCP servers for every AI agent — not just Claude.</i></p>
</div>

<br>

## 📖 关于 MCP

[Model Context Protocol (MCP)](https://modelcontextprotocol.io) 是由 Anthropic 于 2024 年 11 月发布的开放协议，定义了 AI 智能体与外部工具、数据源和服务的交互方式。如果把 AI 智能体比作"大脑"，MCP 服务器就是"手脚"——让 AI 能真正操作世界。

> **🔑 核心理念：MCP 不是 Claude 的专属协议**。市面上几乎所有主流 AI 编码工具都原生支持 MCP：Cursor、Windsurf、Continue.dev、Cline、GitHub Copilot、Zed、Replit Agent、OpenAI Codex CLI 等等。这份列表收集的是**跨平台通用**的 MCP 服务器。

### 图例说明

| 符号 | 含义 |
|------|------|
| ✅ / 🏢 **官方** | 由该公司/组织官方维护 |
| 🧑‍💻 **社区** | 由社区开发者维护 |
| ⭐ Nk+ | GitHub 星标数（千） |
| 🗄️ | 归档/不再维护 |
| 🔧 | 工具类（非服务器） |

<br>

> [!WARNING]
> **安全警告**：MCP 服务器具有文件系统、Shell、数据库等敏感权限。使用前请务必：
> - 审查服务器的源代码和权限范围
> - 仅从可信来源（官方维护、高星标、活跃更新）安装
> - 使用右侧 [🔒 安全审计](#-mcp-安全扫描工具) 中的工具扫描
> - 避免使用不明来源或低质量的 MCP 服务器

---

## 🧩 MCP 客户端

所有主流 AI 编码工具均已支持 MCP 协议。以下为常见客户端的配置方式：

| 客户端 | 类型 | 配置位置 | 备注 |
|--------|------|----------|------|
| **Claude Desktop** | 桌面应用 | `claude_desktop_config.json` | Anthropic 官方，原生 MCP |
| **Claude Code** | CLI | 自动检测 | 内置 MCP 支持 |
| **Cursor** | IDE | `.cursor/mcp.json` | 项目级配置 |
| **Windsurf** | IDE | `~/.codeium/windsurf/mcp_config.json` | 全局配置 |
| **Continue.dev** | IDE 插件 | `~/.continue/config.json` | VS Code / JetBrains |
| **Cline** | VS Code 插件 | VS Code 设置 → Cline → MCP Servers | VS Code 原生 |
| **GitHub Copilot** | IDE | VS Code 设置 | 原生 MCP 支持 |
| **Zed** | IDE | `~/.config/zed/mcp.json` | 原生 MCP 支持 |
| **Replit Agent** | 云端 IDE | 内置 | 原生 MCP 支持 |
| **OpenAI Codex CLI** | CLI | `~/.codex/cli.json` | 原生 MCP 支持 |
| **Cherry Studio** | 桌面 | 应用内设置 | 多模型 LLM 客户端 |

---

## 📂 服务器分类

> **标注说明**：`🏢` = 官方维护，`🧑‍💻` = 社区维护，`🔥` = 高热度/推荐

<details open>
<summary><strong>📋 快速导航（点击展开/折叠）</strong></summary>

- [🔨 开发者工具 & 代码](#-开发者工具--代码) (11)
- [📁 文件系统 & 版本控制](#-文件系统--版本控制) (5)
- [🌐 浏览器自动化 & Web 抓取](#-浏览器自动化--web-抓取) (8)
- [🗄️ 数据库 & 数据存储](#️-数据库--数据存储) (14)
- [☁️ 云平台 & DevOps](#️-云平台--devops) (12)
- [🔍 搜索 & 文档](#-搜索--文档) (10)
- [🧠 AI & 记忆 & 推理](#-ai--记忆--推理) (12)
- [🧑‍💼 生产力 & 协作](#-生产力--协作) (16)
- [🏦 金融 & 支付](#-金融--支付) (11)
- [🔒 安全 & 合规](#-安全--合规) (9)
- [🎨 设计 & 创意 & 多媒体](#-设计--创意--多媒体) (10)
- [📡 通信 & 消息](#-通信--消息) (10)
- [🧪 测试 & 质量保证](#-测试--质量保证) (9)
- [📊 可观测性 & 监控](#-可观测性--监控) (11)
- [🛠️ 基础设施 & 容器](#️-基础设施--容器) (11)
- [🏪 电商 & 商业](#-电商--商业) (5)
- [🌍 地理位置 & 地图](#-地理位置--地图) (4)

</details>

---

### 🔨 开发者工具 & 代码

开发工作流相关工具 — 项目管理、代码托管、CI/CD、基础设施即代码。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[GitHub MCP Server](https://github.com/github/github-mcp-server)** 🏢🔥 | 完整的 GitHub API — 仓库管理、PR、Issues、代码搜索、分支、Actions | 31k+ | GitHub 官方 |
| **[Linear MCP](https://github.com/linear/linear-mcp)** 🏢 | Linear 项目管理 — Issue 跟踪、周期、项目、团队管理 | — | Linear 官方 |
| **[Atlassian MCP](https://github.com/sooperset/mcp-atlassian)** 🧑‍💻🔥 | Jira + Confluence + Compass — 46 个工具，一站式项目管理 | 5.5k | 社区 |
| **[Asana MCP](https://github.com/...)** 🧑‍💻 | Asana 任务管理 — 项目、任务、时间线、自定义字段 | — | 社区 |
| **[ClickUp MCP](https://github.com/...)** 🧑‍💻 | ClickUp 项目协作 — 任务、文档、目标、仪表盘 | — | 社区 |
| **[Terraform MCP](https://github.com/hashicorp/terraform-mcp)** 🏢🔥 | Terraform — Provider 发现、计划、应用、状态管理 | 1.4k | HashiCorp 官方 |
| **[Pulumi MCP](https://github.com/pulumi/pulumi-mcp)** 🏢 | Pulumi — 基础设施即代码，跨云编排 | — | Pulumi 官方 |
| **[Ansible MCP](https://github.com/...)** 🧑‍💻 | Ansible 自动化 — Playbook 执行、Inventory 管理、模块调用 | — | Red Hat 社区 |
| **[Crossplane MCP](https://github.com/...)** 🧑‍💻 | Crossplane — 云资源控制平面编排 | — | 社区 |
| **[Buildkite MCP](https://github.com/...)** 🧑‍💻 | Buildkite CI/CD — 流水线、构建、部署管理 | — | 社区 |
| **[CodeRabbit MCP](https://github.com/...)** 🧑‍💻 | 自动化代码审查 — AI-powered PR review | — | 社区 |

---

### 📁 文件系统 & 版本控制

本地文件操作和版本控制系统集成。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)** 🏢🔥🔥 | 安全的文件系统读写 — 受限目录访问，Search/Read/Write/Edit | 87.7k | Anthropic 官方 |
| **[Git MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/git)** 🏢🔥🔥 | Git 仓库管理 — 提交、日志、分支、diff、状态查询 | 87.7k | Anthropic 官方 |
| **[GitLab MCP](https://gitlab.com/gitlab-org/gitlab-mcp)** 🏢 | GitLab 集成 — MR、Issues、CI/CD 流水线、仓库管理 | — | GitLab 官方 |
| **[Bitbucket MCP](https://github.com/...)** 🧑‍💻 | Bitbucket 仓库和 Pipelines 管理 | — | 社区 |
| **[Gitee MCP](https://github.com/...)** 🧑‍💻 | Gitee（码云）仓库和项目管理 | — | 社区 |

---

### 🌐 浏览器自动化 & Web 抓取

浏览器控制、网页抓取和数据提取工具。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Playwright MCP](https://github.com/microsoft/playwright-mcp)** 🏢🔥🔥 | 浏览器自动化 — 通过可访问性树进行无头浏览器操作，截图、抓取 | 34.7k | **Microsoft 官方** |
| **[Chrome DevTools MCP](https://github.com/...)** 🧑‍💻🔥 | Chrome DevTools 协议 — Console、Network、Performance、DOM 调试 | 45.8k | 社区 |
| **[Puppeteer MCP](https://github.com/...)** 🧑‍💻 | Puppeteer 浏览器自动化 — Google 维护的浏览器控制库 | — | Google 社区 |
| **[Firecrawl MCP](https://github.com/nicholasgriffintn/firecrawl-mcp)** 🏢🔥 | Web 抓取 → 干净 Markdown，支持 JS 渲染、PDF、Sitemap | 6.8k | Firecrawl 官方 |
| **[Browserbase MCP](https://github.com/browserbase/mcp-server)** 🏢 | 云端无头浏览器 — 隐身代理、验证码绕过、会话录制 | — | Browserbase 官方 |
| **[Bright Data MCP](https://github.com/...)** 🏢 | Bright Data Web 解锁 — ~70 个工具，代理网络，验证码解决 | — | Bright Data 官方 |
| **[Jina Reader MCP](https://github.com/...)** 🏢 | Jina AI Reader — URL 转 LLM 友好格式（Markdown/JSON） | — | Jina AI 官方 |
| **[MarkdownDown MCP](https://github.com/...)** 🧑‍💻 | URL/HTML 内容转 Markdown — 网页内容提取 | — | 社区 |

---

### 🗄️ 数据库 & 数据存储

关系型、文档型、图数据库和向量数据库集成。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[PostgreSQL MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** 🏢🔥🔥 | PostgreSQL — 只读 Schema 和查询，表结构探索 | 87.7k | Anthropic 官方 |
| **[SQLite MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)** 🏢🔥 | SQLite — 本地优先数据库，适合原型开发和小型项目 | 87.7k | Anthropic 官方 |
| **[MySQL MCP](https://github.com/...)** 🧑‍💻 | MySQL/MariaDB — Schema 探索、SQL 执行、表管理 | — | 社区 |
| **[MongoDB MCP](https://github.com/...)** 🧑‍💻 | MongoDB — Schema 检查、JSON 查询、聚合管道 | — | 社区 |
| **[Supabase MCP](https://github.com/...)** 🏢 | Supabase 全管理 — 表、Auth、Edge Functions、Storage、Realtime | — | Supabase 官方 |
| **[Redis MCP](https://github.com/...)** 🧑‍💻 | Redis — 键值操作、缓存管理、发布订阅 | — | 社区 |
| **[Elasticsearch MCP](https://github.com/elastic/elasticsearch-mcp)** 🏢🔥 | Elasticsearch — 自然语言转 ES 查询，索引管理，搜索 | — | **Elastic 官方** |
| **[BigQuery MCP](https://github.com/...)** 🧑‍💻 | Google BigQuery — 企业数据仓库查询，数据集管理 | — | Google 社区 |
| **[Snowflake MCP](https://github.com/...)** 🧑‍💻 | Snowflake — 数据仓库查询，Schema 管理，仓库操作 | — | 社区 |
| **[DynamoDB MCP](https://github.com/...)** 🧑‍💻 | AWS DynamoDB — 表操作、查询、扫描、索引管理 | — | AWS 社区 |
| **[ClickHouse MCP](https://github.com/...)** 🧑‍💻 | ClickHouse — 列式数据库查询，表管理 | — | 社区 |
| **[Couchbase MCP](https://github.com/...)** 🧑‍💻 | Couchbase — NoSQL 文档操作，N1QL 查询 | — | 社区 |
| **[Neo4j MCP](https://github.com/...)** 🧑‍💻🔥 | Neo4j 图数据库 — Cypher 查询生成，知识图谱构建 | — | 社区 |
| **[Qdrant MCP](https://github.com/...)** 🏢🔥 | Qdrant 向量数据库 — 语义搜索，向量存储，混合检索 | 1.4k | Qdrant 官方 |

---

### ☁️ 云平台 & DevOps

主流云服务商和部署平台集成。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[AWS MCP Suite](https://github.com/awslabs/mcp)** 🏢🔥🔥 | AWS 服务套件 — Docs、CDK、Cost Explorer、DynamoDB、S3、Bedrock | 9.3k | **AWS Labs 官方** |
| **[S3 MCP](https://github.com/...)** 🧑‍💻 | AWS S3 — 对象存储操作，文件上传下载，Bucket 管理 | — | 社区 |
| **[Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare)** 🏢🔥 | Cloudflare — Workers、KV、R2、D1、AI、Pages、DNS | 3.9k | **Cloudflare 官方** |
| **[Google Cloud MCP](https://github.com/...)** 🧑‍💻 | Google Cloud — GCS、GKE、Cloud Run、Cloud Functions | — | Google 社区 |
| **[Azure MCP](https://github.com/...)** 🧑‍💻 | Azure — 资源管理、VM、Functions、Storage | — | Microsoft 社区 |
| **[DigitalOcean MCP](https://github.com/...)** 🧑‍💻 | DigitalOcean — Droplets、K8s、数据库、Spaces | — | 社区 |
| **[Vercel MCP](https://github.com/...)** 🏢🔥 | Vercel — 部署、环境变量、日志、域名、团队管理 | — | Vercel 官方 |
| **[Netlify MCP](https://github.com/...)** 🧑‍💻 | Netlify — 站点部署、函数、表单、身份验证 | — | 社区 |
| **[Fly.io MCP](https://github.com/...)** 🧑‍💻 | Fly.io — 应用部署、Volume 管理、网络配置 | — | 社区 |
| **[Render MCP](https://github.com/...)** 🧑‍💻 | Render — 服务部署、数据库管理、自定义域名 | — | 社区 |
| **[Heroku MCP](https://github.com/...)** 🧑‍💻 | Heroku — 应用管理、日志、扩展、Add-on | — | 社区 |
| **[InstaNode MCP](https://github.com/InstaNode-dev/mcp)** 🏢🔥 | 即时开发基础设施 — Postgres/Redis/MongoDB/S3 即时创建，免费层 | — | InstaNode 官方 |

---

### 🔍 搜索 & 文档

搜索引擎、文档检索和内容获取工具。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Context7](https://github.com/upstash/context7)** 🏢🔥🔥🔥 | 库文档即时注入 — 版本特定的框架/Library 文档，基准测试第一 (89分) | 58.6k | **Upstash 官方** |
| **[Fetch MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)** 🏢🔥🔥 | URL → Markdown 内容获取，支持多种格式转换 | 87.7k | Anthropic 官方 |
| **[Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)** 🏢🔥🔥 | Brave 网页搜索 — 无需 API Key，即开即用 | 87.7k | Anthropic 官方 |
| **[Perplexity MCP](https://github.com/...)** 🏢🔥 | Perplexity AI 搜索 — 带来源引用的合成答案 | 2.3k | Perplexity 官方 |
| **[Exa MCP](https://github.com/...)** 🏢 | Exa AI 搜索 — 语义搜索引擎，面向 AI 的搜索 | — | Exa 官方 |
| **[Tavily MCP](https://github.com/...)** 🏢 | Tavily 搜索 — AI 优化的实时搜索引擎 | — | Tavily 官方 |
| **[MarkItDown MCP](https://github.com/microsoft/markitdown)** 🏢🔥🔥🔥 | 文件转 Markdown — 支持 Office、PDF、HTML、CSV 等所有常见格式 | 159k | **Microsoft 官方** |
| **[Meilisearch MCP](https://github.com/...)** 🧑‍💻 | Meilisearch — 搜索索引管理、文档操作、搜索 API | — | 社区 |
| **[Typesense MCP](https://github.com/...)** 🧑‍💻 | Typesense — 搜索服务管理、集合配置 | — | 社区 |
| **[Algolia MCP](https://github.com/...)** 🧑‍💻 | Algolia — 搜索索引管理、API 操作 | — | 社区 |

---

### 🧠 AI & 记忆 & 推理

AI 辅助功能 — 持久记忆、推理框架、模型调用。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Memory MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)** 🏢🔥🔥 | 持久化知识图谱记忆 — 实体和关系存储，跨会话上下文保持 | 87.7k | Anthropic 官方 |
| **[Sequential Thinking MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking)** 🏢🔥 | 结构化推理 — 多步推理步骤和分支，复杂问题分解 | — | Anthropic 官方 |
| **[Codebase Memory MCP](https://github.com/DeusData/codebase-memory-mcp)** 🧑‍💻🔥🔥 | 代码库 → 知识图谱 — 158 种语言，代码结构语义化 | 26.3k | DeusData |
| **[Mem0 MCP Server](https://github.com/odin2-hash/mem0-mcp-server)** 🧑‍💻🔥 | 多数据库记忆管理 — PostgreSQL+pgvector、Neo4j、Redis 三合一 | — | 社区 |
| **[RAG Memory MCP](https://github.com/ttommyth/rag-memory-mcp)** 🧑‍💻🔥 | RAG 记忆系统 — SQLite + sqlite-vec，混合搜索（向量+图） | — | 社区 |
| **[MCP Memory LibSQL](https://github.com/joleyline/mcp-memory-libsql)** 🧑‍💻 | 高性能记忆 — libSQL/Turso，向量搜索，关系管理 | — | 社区 |
| **[Velixar MCP](https://github.com/VelixarAi/velixar-mcp-server)** 🧑‍💻🔥 | 持久 AI 记忆 — 知识图谱、信念追踪、矛盾检测，全客户端兼容 | — | Velixar AI |
| **[Neo4j Memory MCP](https://github.com/...)** 🧑‍💻 | Neo4j 知识图谱记忆 — 384-dim 嵌入、批量操作、多 DB 隔离 | — | 社区 |
| **[Memory Wiki](https://github.com/...)** 🧑‍💻 | Rust 高性能记忆 — BM25 + 向量搜索 + GraphRAG + Web UI | — | 社区 |
| **[HuggingFace MCP](https://github.com/...)** 🧑‍💻 | HuggingFace — 模型搜索、推理 API、数据集访问 | — | 社区 |
| **[OpenAI MCP](https://github.com/...)** 🧑‍💻 | OpenAI API — 模型列表、GPT 推理、Embeddings、文件 | — | 社区 |
| **[Anthropic MCP](https://github.com/...)** 🧑‍💻 | Anthropic API — Claude 模型调用、消息 API | — | 社区 |

---

### 🧑‍💼 生产力 & 协作

办公协作、笔记文档和日程管理工具。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Notion MCP](https://github.com/...)** 🧑‍💻🔥 | Notion — 页面、数据库、块级操作、搜索 | — | 社区 |
| **[Google Drive MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)** 🏢🔥🔥 | Google 云端硬盘 — Docs、Sheets、Slides 读写 | 87.7k | Anthropic 官方 |
| **[Google Calendar MCP](https://github.com/...)** 🧑‍💻 | Google 日历 — 日程查询、创建、更新、忙闲状态 | — | 社区 |
| **[Gmail MCP](https://github.com/...)** 🧑‍💻🔥 | Gmail — 邮件搜索、发送、管理、标签 | — | 社区 |
| **[Microsoft Teams MCP](https://github.com/...)** 🧑‍💻 | Microsoft Teams — 消息、频道、会议、团队管理 | — | Microsoft 社区 |
| **[Outlook MCP](https://github.com/...)** 🧑‍💻 | Outlook — 邮件和日历统一管理 | — | 社区 |
| **[Office 365 MCP](https://github.com/...)** 🧑‍💻 | Office 365 全面集成 — 邮件、日历、联系人、文件 | — | 社区 |
| **[Obsidian MCP](https://github.com/...)** 🧑‍💻🔥 | Obsidian 笔记 — Vault 读写、搜索、图谱查看 | 4k | 社区 |
| **[Miro MCP](https://github.com/...)** 🏢 | Miro 白板 — 看板、图表、便签、协作 | — | Miro 官方 |
| **[Figma MCP](https://github.com/...)** 🏢🔥 | Figma — 设计文件读写、组件库、评论、版本历史 | — | **Figma 官方** |
| **[FigJam MCP](https://github.com/...)** 🏢 | FigJam — 白板协作、便签、图表 | — | Figma 官方 |
| **[Trello MCP](https://github.com/...)** 🧑‍💻 | Trello — 看板、列表、卡片、自定义字段 | — | 社区 |
| **[Todoist MCP](https://github.com/...)** 🧑‍💻 | Todoist — 任务和项目管理，过滤器，标签 | — | 社区 |
| **[Notion Calendar MCP](https://github.com/...)** 🧑‍💻 | Notion Calendar — 日历事件管理 | — | 社区 |
| **[Otter.ai MCP](https://github.com/...)** 🧑‍💻 | Otter.ai — 会议记录和转录管理 | — | 社区 |
| **[Locus MCP](https://github.com/jonybur-oc/locus)** 🧑‍💻🔥 | 用户故事上下文 — `stories.yaml` AI 上下文规范，防越界操作 | — | Locus 官方 |

---

### 🏦 金融 & 支付

支付处理、财务数据和加密货币集成。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Stripe MCP](https://github.com/Methods-Lab/MCP-Server-Stripe)** 🧑‍💻🔥🔥 | Stripe 支付 — 客户、支付、订阅、发票、产品（含金额上限安全护栏） | — | Methods-Lab |
| **[Shopify MCP](https://github.com/...)** 🧑‍💻🔥 | Shopify 电商 — 商品、订单、库存、分析、客户管理 | — | Shopify 社区 |
| **[PayPal MCP](https://github.com/...)** 🧑‍💻 | PayPal 支付 — Agent Toolkit 集成，支付和退款管理 | — | PayPal 社区 |
| **[Square MCP](https://github.com/...)** 🧑‍💻 | Square 支付 — 交易、客户、目录、设备管理 | — | 社区 |
| **[Coinbase MCP](https://github.com/...)** 🧑‍💻🔥 | Coinbase — 钱包、交易、x402 稳定币支付 | — | Coinbase 社区 |
| **[Agentic Payments](https://github.com/...)** 🧑‍💻 | 智能体支付基础设施 — AP2 + ACP 双协议 | — | 社区 |
| **[Plaid MCP](https://github.com/...)** 🏢 | Plaid 金融数据 — 账户、交易、身份验证、资产报告 | — | Plaid 官方 |
| **[QuickBooks MCP](https://github.com/...)** 🧑‍💻 | QuickBooks 会计 — 发票、费用、账户、报表 | — | 社区 |
| **[Xero MCP](https://github.com/...)** 🧑‍💻 | Xero 会计 — 账单、银行交易、对账 | — | 社区 |
| **[Yahoo Finance MCP](https://github.com/...)** 🧑‍💻 | Yahoo Finance — 股票行情、市场数据、历史价格 | — | 社区 |
| **[CoinGecko MCP](https://github.com/...)** 🧑‍💻 | CoinGecko — 加密货币数据、价格、市值、趋势 | — | 社区 |

---

### 🔒 安全 & 合规

安全扫描、漏洞检测和合规审计工具。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[MCPShield](https://github.com/mcpshield/mcpshield)** 🧑‍💻🔥🔥 | 供应链安全 — 检测拼写错误、CVE、凭据泄露、危险权限 | — | MCPShield |
| **[Security MCP Suite](https://github.com/...)** 🧑‍💻🔥 | 自主安全扫描 — nmap、nuclei、trivy、sqlmap、gitleaks 五合一 | — | 社区 |
| **[Snyk MCP](https://github.com/...)** 🏢 | Snyk 漏洞扫描 — 依赖、容器、代码、IaC 全栈 | — | Snyk 官方 |
| **[Semgrep MCP](https://github.com/...)** 🧑‍💻 | Semgrep 代码分析 — SAST、策略即代码、自定义规则 | — | Semgrep 社区 |
| **[Trivy MCP](https://github.com/...)** 🧑‍💻🔥 | Trivy 安全扫描 — 容器镜像、K8s、依赖树、IaC 配置 | — | 社区 |
| **[SonarQube MCP](https://github.com/...)** 🧑‍💻 | SonarQube — 代码质量和安全分析、技术债管理 | — | 社区 |
| **[Burp Suite MCP](https://github.com/...)** 🧑‍💻 | Burp Suite — 渗透测试集成、流量捕获 | — | 社区 |
| **[HashiCorp Vault MCP](https://github.com/...)** 🏢 | HashiCorp Vault — 密钥管理、动态 Secret、策略 | — | HashiCorp 官方 |
| **[OWASP ZAP MCP](https://github.com/...)** 🧑‍💻 | OWASP ZAP — Web 应用安全扫描 | — | 社区 |

---

### 🎨 设计 & 创意 & 多媒体

设计工具、3D 建模和媒体处理。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Figma MCP](https://github.com/...)** 🏢🔥🔥 | Figma — 设计文件读写、组件库、样式、评论 | — | **Figma 官方** |
| **[Penpot MCP](https://github.com/...)** 🧑‍💻 | Penpot — 开源设计工具集成，跨平台 | — | 社区 |
| **[Blender MCP](https://github.com/ahujasid/blender-mcp)** 🧑‍💻🔥🔥 | Blender 3D — 提示词辅助建模、材质、场景创建 | 23.2k | 社区 |
| **[Canva MCP](https://github.com/...)** 🏢 | Canva — 设计创建、编辑、导出、模板 | — | Canva 官方 |
| **[Excalidraw MCP](https://github.com/...)** 🧑‍💻🔥 | Excalidraw — 白板和图表创建，手绘风格 | — | 社区 |
| **[Diagrams MCP](https://github.com/...)** 🧑‍💻 | Diagrams.net (draw.io) — 架构图、流程图创建 | — | 社区 |
| **[Midjourney MCP](https://github.com/...)** 🧑‍💻🔥 | Midjourney — AI 图像生成，参数控制 | — | 社区 |
| **[DALL-E MCP](https://github.com/...)** 🧑‍💻 | DALL-E — OpenAI 图像生成 | — | 社区 |
| **[Stable Diffusion MCP](https://github.com/...)** 🧑‍💻 | Stable Diffusion — 本地图像生成，ComfyUI 集成 | — | 社区 |
| **[FFmpeg MCP](https://github.com/...)** 🧑‍💻🔥 | FFmpeg — 音视频处理、转码、剪辑、流处理 | — | 社区 |

---

### 📡 通信 & 消息

即时消息、邮件和通信平台集成。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Slack MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)** 🏢🔥🔥 | Slack — 消息读写、频道搜索、文件分享、用户管理 | 87.7k | Anthropic 官方 |
| **[Discord MCP](https://github.com/...)** 🧑‍💻🔥 | Discord — 消息、频道管理、语音、角色管理 | — | 社区 |
| **[Telegram MCP](https://github.com/...)** 🧑‍💻🔥 | Telegram Bot — 消息发送/接收、群组管理、内联查询 | — | 社区 |
| **[WhatsApp MCP](https://github.com/...)** 🧑‍💻 | WhatsApp Business — 消息、模板、媒体 | — | 社区 |
| **[Twilio MCP](https://github.com/...)** 🧑‍💻 | Twilio — SMS、语音、WhatsApp API 统一通信 | — | 社区 |
| **[SendGrid MCP](https://github.com/...)** 🧑‍💻 | SendGrid — 邮件发送、模板管理、统计 | — | 社区 |
| **[Resend MCP](https://github.com/...)** 🏢🔥 | Resend — 邮件 API，React 邮件支持 | — | Resend 官方 |
| **[Mailgun MCP](https://github.com/...)** 🧑‍💻 | Mailgun — 邮件服务管理、域名、日志 | — | 社区 |
| **[Postmark MCP](https://github.com/...)** 🧑‍💻 | Postmark — 事务邮件、送达跟踪 | — | 社区 |
| **[AWS SES MCP](https://github.com/...)** 🧑‍💻 | AWS SES — 邮件发送、模板、配置集 | — | 社区 |

---

### 🧪 测试 & 质量保证

自动化测试、性能测试和 API 测试工具。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Playwright MCP](https://github.com/microsoft/playwright-mcp)** 🏢🔥🔥 | E2E 测试 — 浏览器自动化测试，跨浏览器支持 | 34.7k | **Microsoft 官方** |
| **[Cypress MCP](https://github.com/...)** 🧑‍💻🔥 | Cypress — 组件测试和 E2E 测试一体化 | — | 社区 |
| **[Jest MCP](https://github.com/...)** 🧑‍💻 | Jest — 单元测试、快照测试、覆盖率 | — | 社区 |
| **[Vitest MCP](https://github.com/...)** 🧑‍💻🔥 | Vitest — 快速单元测试，Vite 原生 | — | 社区 |
| **[Selenium MCP](https://github.com/...)** 🧑‍💻 | Selenium — 跨浏览器测试，多语言支持 | — | 社区 |
| **[Postman MCP](https://github.com/...)** 🏢🔥 | Postman — API 测试、集合管理、环境变量 | — | Postman 官方 |
| **[Grafana k6 MCP](https://github.com/...)** 🧑‍💻🔥 | k6 — 性能/负载测试，JavaScript 脚本 | — | 社区 |
| **[Locust MCP](https://github.com/...)** 🧑‍💻 | Locust — 分布式负载测试，Python 脚本 | — | 社区 |
| **[Artillery MCP](https://github.com/...)** 🧑‍💻 | Artillery — 性能和压力测试，YAML 配置 | — | 社区 |

---

### 📊 可观测性 & 监控

应用监控、日志管理和事件响应。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Sentry MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry)** 🏢🔥🔥 | Sentry — 错误跟踪、性能问题检索、Release 管理 | 87.7k | Anthropic 官方 |
| **[Grafana MCP](https://github.com/...)** 🏢🔥 | Grafana — Dashboard 查询、Prometheus/Loki 数据源 | — | Grafana 官方 |
| **[Datadog MCP](https://github.com/...)** 🏢🔥 | Datadog — 指标、日志、APM、Dashboard、监控 | — | Datadog 官方 |
| **[New Relic MCP](https://github.com/...)** 🧑‍💻 | New Relic — APM、浏览器监控、日志、基础设施 | — | 社区 |
| **[Prometheus MCP](https://github.com/...)** 🧑‍💻🔥 | Prometheus — 指标查询、告警管理、规则配置 | — | 社区 |
| **[Grafana Loki MCP](https://github.com/...)** 🧑‍💻 | Loki — 日志查询和分析、LogQL | — | 社区 |
| **[Elastic Observability MCP](https://github.com/...)** 🏢 | Elastic 可观测性 — 日志、APM、安全分析 | — | Elastic 官方 |
| **[UptimeRobot MCP](https://github.com/...)** 🧑‍💻 | UptimeRobot — 监控状态管理、维护窗口 | — | 社区 |
| **[Statuspage MCP](https://github.com/...)** 🧑‍💻 | Atlassian Statuspage — 事件管理、组件状态 | — | 社区 |
| **[PagerDuty MCP](https://github.com/...)** 🏢🔥 | PagerDuty — 事件响应、排班表、服务管理 | — | PagerDuty 官方 |
| **[Opsgenie MCP](https://github.com/...)** 🧑‍💻 | Opsgenie — 告警管理、排班表、升级策略 | — | 社区 |

---

### 🛠️ 基础设施 & 容器

容器编排、虚拟化和系统管理。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Docker MCP](https://github.com/...)** 🏢🔥🔥 | Docker — 容器管理、镜像构建、Compose 编排 | — | Docker 官方 |
| **[Kubernetes MCP](https://github.com/...)** 🧑‍💻🔥🔥 | Kubernetes — CRUD 资源、Helm Chart、Tekton 流水线 | 1.7k | 社区 |
| **[Terraform MCP](https://github.com/hashicorp/terraform-mcp)** 🏢🔥 | Terraform — Provider 发现、计划、应用、状态管理 | 1.4k | **HashiCorp 官方** |
| **[Pulumi MCP](https://github.com/pulumi/pulumi-mcp)** 🏢 | Pulumi — IaC 跨云管理，多语言支持 | — | Pulumi 官方 |
| **[Ansible MCP](https://github.com/...)** 🧑‍💻 | Ansible — Playbook 执行、Inventory 管理、模块 | — | Ansible 社区 |
| **[Nix MCP](https://github.com/...)** 🧑‍💻 | Nix/NixOS — 包管理、配置、Flake 支持 | — | 社区 |
| **[Helm MCP](https://github.com/...)** 🧑‍💻🔥 | Helm — K8s Chart 管理、仓库配置、部署 | — | 社区 |
| **[kubectl MCP](https://github.com/...)** 🧑‍💻🔥 | kubectl — K8s 集群管理、Pod/Service/Deployment 操作 | — | 社区 |
| **[Vagrant MCP](https://github.com/...)** 🧑‍💻 | Vagrant — 虚拟机管理、Box 管理 | — | HashiCorp 社区 |
| **[Proxmox MCP](https://github.com/...)** 🧑‍💻 | Proxmox VE — 虚拟机、容器、存储管理 | — | 社区 |
| **[vSphere MCP](https://github.com/...)** 🧑‍💻 | VMware vSphere — 虚拟机、ESXi、集群管理 | — | 社区 |

---

### 🏪 电商 & 商业

电子商务、CRM 和商业平台集成。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Shopify MCP](https://github.com/...)** 🧑‍💻🔥 | Shopify — 商品、订单、库存、分析、客户、折扣 | — | Shopify 社区 |
| **[WooCommerce MCP](https://github.com/...)** 🧑‍💻 | WooCommerce — 商品、订单、客户管理 | — | 社区 |
| **[Magento MCP](https://github.com/...)** 🧑‍💻 | Magento/Adobe Commerce — 电商管理 | — | 社区 |
| **[Salesforce MCP](https://github.com/...)** 🧑‍💻🔥 | Salesforce — 客户、商机、报表、自动化 | — | Salesforce 社区 |
| **[HubSpot MCP](https://github.com/...)** 🧑‍💻🔥 | HubSpot — CRM、营销、销售、服务 Hub | — | 社区 |

---

### 🌍 地理位置 & 地图

地图服务、地理位置和出行相关。

| MCP 服务器 | 描述 | ⭐ | 维护 |
|-----------|------|---|------|
| **[Google Maps MCP](https://github.com/...)** 🧑‍💻🔥 | Google Maps — 地理编码、路线、地点搜索、距离矩阵 | — | 社区 |
| **[OpenStreetMap MCP](https://github.com/...)** 🧑‍💻 | OpenStreetMap — 地图数据查询、逆地理编码 | — | 社区 |
| **[Mapbox MCP](https://github.com/...)** 🧑‍💻 | Mapbox — 地图样式、地理编码、导航 | — | 社区 |
| **[ Here Maps MCP](https://github.com/...)** 🧑‍💻 | HERE Maps — 位置服务、路线规划、交通 | — | 社区 |

---

## 🔧 MCP 工具 & SDK

除了 MCP 服务器，以下工具和 SDK 可帮助你**构建、测试、部署和管理** MCP 服务器。

### 官方 SDK

| SDK | 语言 | 维护方 |
|-----|------|--------|
| **[Python MCP SDK](https://github.com/modelcontextprotocol/python-sdk)** 🏢 | Python | Anthropic 官方 |
| **[TypeScript MCP SDK](https://github.com/modelcontextprotocol/typescript-sdk)** 🏢🔥 | TypeScript | Anthropic 官方 |
| **[Java MCP SDK](https://github.com/modelcontextprotocol/java-sdk)** 🏢 | Java | Anthropic 官方 |
| **[Kotlin MCP SDK](https://github.com/modelcontextprotocol/kotlin-sdk)** 🏢 | Kotlin | Anthropic 官方 |
| **[Go MCP SDK](https://github.com/modelcontextprotocol/go-sdk)** 🏢 | Go | Anthropic 官方 |
| **[C# MCP SDK](https://github.com/modelcontextprotocol/csharp-sdk)** 🏢 | C# | Anthropic 官方 |
| **[Rust MCP SDK](https://github.com/modelcontextprotocol/rust-sdk)** 🏢 | Rust | Anthropic 官方 |

### 社区框架 & 工具

| 工具 | 描述 | ⭐ | 维护 |
|------|------|---|------|
| **[FastMCP](https://github.com/punkpeye/fastmcp)** 🧑‍💻🔥🔥🔥 | Python 快速构建 MCP 服务器的最流行框架 | 17.3k+ | 社区 |
| **[Inspector](https://github.com/modelcontextprotocol/inspector)** 🏢🔥 | MCP 服务器调试器 — 交互式测试和检查 | — | Anthropic 官方 |
| **[MCP Proxy](https://github.com/...)** 🧑‍💻 | MCP 代理服务器 — 统一网关、负载均衡 | — | 社区 |
| **[MCP CLI](https://github.com/...)** 🧑‍💻 | MCP 命令行工具 — 快速测试和调用 MCP 服务器 | — | 社区 |
| **[MCP Docker](https://github.com/...)** 🧑‍💻 | Docker 化 MCP 服务器 — 一键部署模板 | — | 社区 |
| **[MCP Scaffold](https://github.com/...)** 🧑‍💻 | MCP 项目脚手架 — 快速生成服务器模板 | — | 社区 |
| **[MCP Server Manager](https://github.com/...)** 🧑‍💻 | MCP 服务器管理面板 — 可视化配置和管理 | — | 社区 |
| **[MCP Test](https://github.com/...)** 🧑‍💻 | MCP 测试框架 — 自动化测试你的 MCP 服务器 | — | 社区 |

---

## 🔒 MCP 安全扫描工具

在引入 MCP 服务器前，建议使用以下工具进行安全审计。数据显示 **82%** 的 MCP 实现存在路径遍历漏洞，**88%** 使用非安全静态密钥。

| 工具 | 描述 | 特点 |
|------|------|------|
| **[MCPSec](https://github.com/mcp-shark/MCPSec)** 🧑‍💻🔥🔥 | 最全面的 MCP 安全审计器 — 34 个安全发现，6 个审计器 | CI/CD 门控、CVSS 3.1 评分、SARIF 输出、OWASP MCP Top 10 映射 |
| **[MCPShield](https://github.com/mcpshield/mcpshield)** 🧑‍💻🔥 | 供应链安全扫描 — 检测拼写错误攻击、CVE、凭据泄露 | 自动发现 10+ 客户端配置，CI/CD 退出码 |
| **[MCP Security Scanner](https://www.npmjs.com/package/mcp-server-security-scanner)** 🧑‍💻 | 生产级扫描 — 5 个核心工具 | CVE 数据库、SOC 2 合规检查、风险评分 (0-100) |
| **[Cisco AI MCP Scanner](https://pypi.org/project/cisco-ai-mcp-scanner/)** 🏢 | 企业级扫描 — YARA 规则 + LLM 评判 + Cisco 防御 API | 多语言支持、REST API、VirusTotal 集成 |
| **[Ghostprobe](https://github.com/...)** 🧑‍💻🔥 | 红队探测工具 — 工具投毒检测、隐藏指令发现 | 离线分析、快照 diff 对比、OWASP MCP Top 10 |
| **[mcp-security-scan](https://www.npmjs.com/package/mcp-security-scan)** 🧑‍💻 | 零配置 CLI — `npx` 即刻运行 | 自动发现配置、多格式输出 |

---

## 📚 权威汇总列表

以下成熟的项目已经帮你整理了海量 MCP 服务器，建议配合使用：

| 资源 | 描述 | 数量 | 更新 |
|------|------|------|------|
| **[AlexMili/Awesome-MCP](https://github.com/AlexMili/Awesome-MCP)** 🏆🔥 | 按使用场景分类，自动刷新活动和星标 | 1000+ | 持续 |
| **[tolkonepiu/best-of-mcp-servers](https://github.com/tolkonepiu/best-of-mcp-servers)** 🏆🔥 | **按项目质量评分排名**，34 个分类，含评级勋章 | **400** | **每周** |
| **[sunnamed434/awesome-mcp-registry](https://github.com/sunnamed434/awesome-mcp-registry)** 🏆🔥 | **AI 策划** (GPT-4.1-mini) + 信任公式评分 | 数千 | **每周** |
| **[appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers)** 🏆 | 广泛覆盖，附带安全警告标注 | 大量 | 持续 |
| **[bgizdov/awesome-mcp-servers](https://github.com/bgizdov/awesome-mcp-servers)** 🏆 | **自动生成**，51 种语言，408k 总星标 | **7,273** | **每日** |
| **[fuzzylabs/awesome-secure-mcp-servers](https://github.com/fuzzylabs/awesome-secure-mcp-servers)** 🏆 | **安全验证**的服务器列表（mcp-scan 评分） | 精选 | 持续 |
| **[punkpeye/awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)** 🏆 | MCP 客户端汇总（非服务器） | 大量 | 持续 |
| **[PulseMCP](https://www.pulsemcp.com/servers)** 🔥🔥 | 在线 MCP 服务器搜索引擎和目录 | **20,000+** | **每日** |
| **[MCPCorpus 数据集](https://huggingface.co/papers/2506.23474)** | 学术研究数据集，~14K 服务器 × 20+ 属性 | ~14,000 | 定期 |
| **[GitHub MCP 市场](https://github.com/marketplace?type=mcp)** 🏢 | GitHub 官方 MCP 注册中心 | — | 持续 |
| **[MCP 注册中心](https://registry.modelcontextprotocol.io)** 🏢 | MCP 官方中央注册中心 | — | 持续 |

---

## 🚀 快速开始

### 入门组合（个人开发者）

```bash
# 1. 文件系统 — 安全的文件读写
npx -y @modelcontextprotocol/server-filesystem /path/to/project

# 2. GitHub — 仓库和 Issue 管理
npx -y @modelcontextprotocol/server-github

# 3. 网页搜索 — 无需 API Key
npx -y @modelcontextprotocol/server-brave-search

# 4. 文档查询 — 实时库文档（58k+ ⭐）
npx -y @upstash/context7

# 5. 浏览器自动化
npx -y @playwright/mcp
```

### 生产环境组合（团队）

```json
{
  "mcpServers": {
    "filesystem": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-filesystem", "/workspace"]
    },
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"]
    },
    "postgres": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-postgres", "postgresql://..."]
    },
    "sentry": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-sentry"]
    },
    "playwright": {
      "command": "npx",
      "args": ["-y", "@playwright/mcp"]
    },
    "context7": {
      "command": "npx",
      "args": ["-y", "@upstash/context7"]
    }
  }
}
```

### 选择 MCP 服务器的最佳实践

1. **优先选择 🏢 官方维护**的服务器
2. **检查 ⭐ 星标数**和最近更新日期
3. **用 🔒 安全工具扫描**后再使用
4. **从最小权限开始**（Filesystem MCP 限目录、数据库用只读模式）
5. **不要在一开始装太多** — 按需添加，保持可控

---

## 📖 延伸阅读

- **[MCP 官方文档](https://modelcontextprotocol.io)** — 协议规范、快速开始、最佳实践
- **[MCP 规范 (GitHub)](https://github.com/modelcontextprotocol/specification)** — 协议实现细节
- **[Anthropic MCP 介绍](https://www.anthropic.com/news/model-context-protocol)** — MCP 原始发布文章
- **[MCP 服务器基准测试](https://github.com/OrrisTech/agent-eval)** — 各 MCP 服务器性能可靠性对比
- **[Agent Eval 博客](https://agent-eval.vercel.app/blog/mcp-server-benchmark)** — MCP 服务器基准测试详解
- **[MCP Discord 社区](https://discord.gg/mcp)** — MCP 开发者社区
- **[MCP @ GitHub](https://github.com/modelcontextprotocol)** — 官方 GitHub 组织

---

## 🤝 贡献

欢迎贡献！请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详情。

**贡献方式：**
- 提交 PR 添加新的 MCP 服务器
- 更新现有服务器信息（星标、描述等）
- 报告错误的分类或链接
- 提交安全漏洞警告

---

<div align="center">
  <p>
    <sub>⭐ 如果这个列表对你有帮助，请给一个 Star！</sub><br>
    <sub>⚠️ 数据采集于 2026 年 7 月。使用任何 MCP 服务器前请验证其安全性。</sub>
  </p>
  <p>
    <a href="https://github.com/bradyliuY/awesome-mcp-servers">
      <img src="https://img.shields.io/github/stars/bradyliuY/awesome-mcp-servers?style=flat-square&label=Stars" alt="Stars">
    </a>
    <a href="https://github.com/bradyliuY/awesome-mcp-servers/blob/main/CONTRIBUTING.md">
      <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
    </a>
    <a href="https://github.com/bradyliuY/awesome-mcp-servers/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/license-CC0-blue?style=flat-square" alt="License">
    </a>
  </p>
</div>
