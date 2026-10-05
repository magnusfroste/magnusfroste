# Hi, I'm Magnus 👋

📍 Sweden | 🤖 Chief Agent Officer & Agent Engineer | 🚀 Product Developer

I design and ship autonomous AI agent systems — from infrastructure to orchestration to production. Building the platforms that let agents run businesses, watch markets, and manage themselves, day and night.

**Tech Stack:** TypeScript · React · Python · Go
**License:** Open Source · MIT (Sluss: AGPL-3.0)

## 🌟 Featured

- **[Clawable](https://www.clawable.org)** — The open-source field report on autonomous agents. Three editions for leaders, builders, and operators.
- **[Flowwink](https://www.flowwink.com)** — AI-native Business Operating System with a built-in autonomous agent and 500+ MCP skills.
- **[Sluss](https://www.sluss.eu)** — The data-sovereign LLM gateway. Your teams already use AI — decide where the data goes, and prove it. Deterministic routing, fail-closed egress, tamper-evident audit for NIS2/DORA/GDPR.
- **[vLLM Cluster Spark](https://github.com/magnusfroste/vllm-cluster-spark)** — Private AI on your own NVIDIA DGX Spark cluster. An Easypanel-inspired control plane for multi-node vLLM: set up, start, watch and fix the whole cluster from one web app — live GPU temperature, power draw, tokens/s and tokens per kWh across every node.
- **[AgentHotel](https://github.com/magnusfroste/agenthotel)** — Self-hosted control panel for AI agents. Check them in, watch them work — isolated rooms, automatic HTTPS, built-in MCP server.
- **[Agentanbud](https://www.agentanbud.se)** — The first platform built for AI agents in Swedish public procurement. Open tender data, no paywalls, MCP-native so your own agent can watch the market and flag what's worth your time.
- **[SiliconSoap](https://www.siliconsoap.com)** — 20+ AI models debate live, under pressure, in character. Benchmarks tell you what a model knows; SiliconSoap shows you how it actually reasons, bluffs, or folds when challenged — the eval that matters before you trust a model in production.

## Technical Expertise

Working with modern AI infrastructure: self-hosted LLM deployments, open weights models, fine-tuning workflows, and production-ready MLOps pipelines. From local development to cloud deployments.

## 🌟 Highlights

- **80+ Open Source Projects** - Built in the open, production-ready
- **Agent Infrastructure** - Self-hosted platforms for deploying, orchestrating, and monitoring autonomous AI agents at scale
- **MCP & A2A Protocols** - Building the connective tissue between agents, tools, and business systems
- **Full-Stack Development** - From agent runtime to production deployment

## Projects

### 🧩 Agents & Agent Infrastructure

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**sluss-eu**](https://github.com/magnusfroste/sluss-eu) | Go · SQLite | Data-sovereign LLM gateway — every prompt classified by deterministic rules (no LLM in the decision), routed fail-closed to your own, EU or the cheapest capable cloud model, and logged in a hash-chained audit trail. One static binary, OpenAI + Anthropic wire formats. Live at [sluss.eu](https://www.sluss.eu) |
| [**agenthotel**](https://github.com/magnusfroste/agenthotel) | React · Node.js · Docker · Caddy | Self-hosted control panel for AI agents — one VPS becomes a hotel with isolated rooms per agent (Hermes, OpenClaw, Odysseus, or any Docker app). Automatic HTTPS, resource guardrails, uptime monitoring, and a built-in MCP server. |
| [**skillhub**](https://github.com/magnusfroste/skillhub) | Supabase · Kong · MCP | SharePoint for agents, starting with skills. A shared store on self-hosted Supabase where each agent connects over MCP with its own key — reads everything public, writes its own, can't overwrite a colleague. Every write traceable. |
| [**agentanbud**](https://github.com/magnusfroste/agentanbud) | FastAPI · Python · SQLite · Docker | The first platform built for AI agents in Swedish public procurement — mirrors tender data from Mercell and TED EU into a local SQLite database, served via dashboard, JSON API and MCP. Single container, no cloud dependencies. Live at [agentanbud.se](https://www.agentanbud.se) |
| [**reel-studio**](https://github.com/magnusfroste/reel-studio) | Python · MCP | Turns any AI agent into a video director — it drives a real browser, narrates on the beat, and renders a polished MP4. Bring your own agent. |
| [**lobby**](https://github.com/magnusfroste/lobby) | Node.js · Markdown · MCP | A hotel for landing pages — one process, many domains, each site a single markdown file. No database, no build step; agents publish over MCP in ~150 ms. |
| [**norrivaagent**](https://github.com/magnusfroste/norrivaagent) | Go | Norriva Desk — a personal agent on your own computer, signed in to a SaaS as you. Row-level security applies to the agent too; a linked folder is its fence. |
| [**clawclass**](https://github.com/magnusfroste/clawclass) | JavaScript · OpenClaw | Multi-tenant agent infrastructure — one server, unlimited OpenClaw agents. Auto domains/HTTPS/container lifecycle, role presets, and A2A swarm orchestration. |
| [**hermeshotel**](https://github.com/magnusfroste/hermeshotel) | Python · Docker · Caddy | Multi-agent Hermes platform — operator, customer and supplier agents with Flowwink MCP, private LLM, TUI control panel and fleet status web. |
| [**agenttable**](https://github.com/magnusfroste/agenttable) | FastAPI · SQLite · MCP | Minimal Airtable-like storage for agents: CSV in → SQLite → MCP out. |
| [**hermes-easy**](https://github.com/magnusfroste/hermes-easy) · [**openclaw-easy**](https://github.com/magnusfroste/openclaw-easy) · [**odysseus-easy**](https://github.com/magnusfroste/odysseus-easy) | Docker · Easypanel | The simplest way to run Hermes, OpenClaw and Odysseus on Easypanel — env-driven config, no build step. |

### 🌊 CMS & Content Management

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**flowwink**](https://github.com/magnusfroste/flowwink) | React · Supabase | Open-source AI-native Business Operating System with a built-in autonomous agent and 500+ MCP skills. CMS, CRM and ERP run by FlowPilot — or by Hermes, Claude, OpenClaw. |
| [**scout-out**](https://github.com/magnusfroste/scout-out) | React · TypeScript · Supabase | Prototype for AI-powered B2B prospecting and personalized outreach — the concept now lives on as the **Outreach** module in [Flowwink](https://www.flowwink.com). |
| [**scout-in**](https://github.com/magnusfroste/scout-in) | React · TypeScript · Supabase | Prototype for AI-driven prospect and company research — the concept now lives on as the **Sales Intelligence** module in [Flowwink](https://www.flowwink.com). |
| [**mycms-space**](https://github.com/magnusfroste/mycms-space) | React · Supabase | Self-hostable CMS that transforms any website into a dynamic, AI-powered digital assistant. Conversational AI widget that engages visitors 24/7. |
| [**markdownweb**](https://github.com/magnusfroste/markdownweb) | TanStack Start · Cloudflare Workers | A tiny CMS where every site is a single markdown file — built so an external AI agent can spin up and maintain dozens of sites over MCP. |

### 🤖 AI, Inference & Machine Learning

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**private-ai-chatspace**](https://github.com/magnusfroste/private-ai-chatspace) | FastAPI · React · Qdrant · LanceDB | Private AI chat with RAG, dual vector stores, hybrid search (semantic + BM25), Docling PDF processing with OCR, and intelligent tool calling. Inspired by AnythingLLM but simpler. |
| [**siliconsoap**](https://github.com/magnusfroste/siliconsoap) | React · TypeScript · Supabase · OpenRouter | Multi-agent AI debate platform — pit 20+ models against each other in dramatic conversations with custom personas and AI-powered analysis. Live at [siliconsoap.com](https://www.siliconsoap.com) |
| [**garageai**](https://github.com/magnusfroste/garageai) | Astro · LiteLLM · NetBird | A marketplace for local AI inference in Europe — garage owners offer GPUs they already own, buyers call them through one OpenAI-compatible API (pool or a specific garage), and owners get paid per token. Encrypted WireGuard mesh behind an EU gateway. Live at [garageai.eu](https://www.garageai.eu) · portal at [app.garageai.eu](https://app.garageai.eu) |
| [**vllm-cluster-spark**](https://github.com/magnusfroste/vllm-cluster-spark) | Python · vLLM · Ray · Easypanel | Private AI on your own DGX Spark cluster — one vLLM model across two or more nodes with tensor parallelism, run from an Easypanel-inspired web app: per-node GPU temperature, power and memory, tokens/s, KV cache, energy and tokens per kWh, model downloads to every node, and auto-recover. |
| [**dgx2spark**](https://github.com/magnusfroste/dgx2spark) | TensorRT-LLM · Docker | Multi-node Qwen3-235B inference on NVIDIA DGX Spark with TensorRT-LLM and a Grok-style chat UI. |
| [**private-ai-portal**](https://github.com/magnusfroste/private-ai-portal) | TypeScript · LiteLLM | Customer portal for a LiteLLM proxy — virtual keys, spend limits and usage per customer. |
| [**private-whisper-agent**](https://github.com/magnusfroste/private-whisper-agent) | Python · Whisper | Fully local voice AI stack (STT → LLM → TTS) — your audio never leaves your server. |
| [**acestep**](https://github.com/magnusfroste/acestep) | Docker · NVIDIA GPU | Self-hosted AI music generation with ACE-Step 1.5, GPU-accelerated. |
| [**mlx-ml**](https://github.com/magnusfroste/mlx-ml) | Python · Apple MLX | LoRA fine-tuning, inference and deployment with Apple's MLX framework on M-series chips — one config.yaml. |
| [**lmstudio-agents**](https://github.com/magnusfroste/lmstudio-agents) | Python · LM Studio | Mini framework for agentic tool calling with local LLMs. |

### 📄 Productivity & Utilities

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**notton**](https://github.com/magnusfroste/notton) | React · Supabase · AI | Cloud-based note-taking with Apple Notes elegance. AI capabilities for semantic search and chat assistant. Live at [notton.app](https://notton.app) |
| [**certera**](https://github.com/magnusfroste/certera) | React · AI | AI-generated diplomas and certificates with blockchain-backed verification. Live at [certera.ink](https://www.certera.ink) |
| [**timeslot**](https://github.com/magnusfroste/timeslot) | React · Supabase | Create time slots, share the link, let others pick — no registration. Live at [timeslot.fit](https://www.timeslot.fit) |
| [**lazyjobs-app**](https://github.com/magnusfroste/lazyjobs-app) | React · AI | Job search reimagined with AI-driven matching. Upload CV and get curated job opportunities from diverse sources. |
| [**painpal**](https://github.com/magnusfroste/painpal) | React · Supabase · AI | Migraine tracking adventure for children. AI-powered assistance makes headache diary an engaging journey. |
| [**md2pdf**](https://github.com/magnusfroste/md2pdf) | TypeScript | Convert Markdown files into styled, high-quality PDFs. |
| [**adlink**](https://github.com/magnusfroste/adlink) | React | Link management for content creators. Transform paywalled resources into monetized, shareable links. |

### 📊 Analytics & Business Intelligence

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**airledger**](https://github.com/magnusfroste/airledger) | React · Supabase · AI | AI-powered bookkeeping assistant that automates financial tracking, data parsing, and reporting while adhering to Swedish accounting standards. Live at [airledger.se](https://www.airledger.se) |
| [**sie-parser**](https://github.com/magnusfroste/sie-parser) | TypeScript | Transforms Swedish bookkeeping data (SIE 4 files) into structured, LLM-friendly JSON for financial analysis. |
| [**shop-analytics**](https://github.com/magnusfroste/shop-analytics) | React · Python | Retail analytics with AI-powered recommendations to boost sales, built on LLMs over visitor data. |
| [**shoplifting-rtsp-analyzer**](https://github.com/magnusfroste/shoplifting-rtsp-analyzer) | Python · React · OpenCV | Pre-flight validation of RTSP camera streams for [anavid.ai](https://anavid.ai) shoplifting detection — frame rate, bitrate and visual snapshots. |
| [**telelog-analytics**](https://github.com/magnusfroste/telelog-analytics) | React · OpenAI · Anthropic | AI-powered Telegram conversation analytics with multi-model support and sentiment analysis. |
| [**audiostats**](https://github.com/magnusfroste/audiostats) | React · Supabase | "Anna" — a meeting companion that turns raw audio recordings into team insights: transcription, key moments, speaker insights, and summaries. |
| [**quickpitch**](https://github.com/magnusfroste/quickpitch) | React · OpenAI · Agora RTC | Pitch practice with real-time video recording and AI feedback. 20-minute timer, 5-slide limit format. |
| [**aircount**](https://github.com/magnusfroste/aircount) | React · Supabase | Accounting for individuals and small businesses — dashboard, transaction tracking, and CSV/SIE import/export. |
| [**crypto-ledger**](https://github.com/magnusfroste/crypto-ledger) | React · Supabase | Manage and track cryptocurrency transactions. |

### 💬 Chat & Communication

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**flowifychat**](https://github.com/magnusfroste/flowifychat) | React · n8n | Beautiful, production-grade chat interfaces for n8n AI agents — streaming, memory-aware, fully customizable. Live at [flowify.chat](https://flowify.chat) |
| [**chatsoap**](https://github.com/magnusfroste/chatsoap) | React · TypeScript · Supabase | Real-time messaging app with persistent history and secure auth. |
| [**james-pwa-n8n**](https://github.com/magnusfroste/james-pwa-n8n) | React · TypeScript · PWA | AI conversational agent PWA for a native-like iOS experience — voice and text with real-time transcription. |
| [**stupid-simple-meet**](https://github.com/magnusfroste/stupid-simple-meet) | Vanilla JS · WebRTC | Ultra-minimal audio/video conferencing. Click one button, join a peer-to-peer stream. No accounts, no room codes, no downloads. |
| [**helplix-legal**](https://github.com/magnusfroste/helplix-legal) | React · AI | Mobile-first dictation app for documenting legal cases. AI agents ask targeted questions across 7 phases with jurisdiction-specific guidance. |

### 🛠️ Developer Tools & APIs

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**subdomains-proxy**](https://github.com/magnusfroste/subdomains-proxy) | Node.js · Caddy · Docker | API-first subdomain proxy — branded subdomains for every customer with automatic HTTPS. Live at [subdomains.site](https://www.subdomains.site) |
| [**domain-proxy-saas**](https://github.com/magnusfroste/domain-proxy-saas) | React · Node.js | SaaS starter kit demonstrating custom domains via DomainProxy, with multi-tenant architecture. |
| [**openjobs-api**](https://github.com/magnusfroste/openjobs-api) | Go | Job aggregation platform with microservices architecture and incremental sync. Unified API across sources. |
| [**marker-api**](https://github.com/magnusfroste/marker-api) | Python · FastAPI | PDF to Markdown conversion API using Marker, ready for Easypanel. |
| [**screncastme-chrome**](https://github.com/magnusfroste/screncastme-chrome) | JavaScript · Chrome Extension | ScreenCastMe — screen recording with draggable webcam overlay, audio capture, and built-in trim editor. |

### 🎵 Media & Entertainment

| Project | Tech Stack | Description |
|---------|------------|-------------|
| [**soundspace**](https://github.com/magnusfroste/soundspace) | React · AI | Ambient music platform for businesses with curated playlists and AI-powered music generation with smart scheduling. |

### 🎮 Games & Education — [skolappar.com](https://www.skolappar.com)

*20+ learning apps serving students — a community platform where parents share home-made learning apps.*

| Project | Description |
|---------|-------------|
| [**skolappar**](https://github.com/magnusfroste/skolappar) | Community platform for parents to share educational apps |
| [**chatexam**](https://github.com/magnusfroste/chatexam) | AI-powered tutor for the Swedish university entrance exam (Högskoleprovet) |
| [**quizla**](https://github.com/magnusfroste/quizla) | AI-tailored quizzes adapting to each student's level |
| [**penpal**](https://github.com/magnusfroste/penpal) | Handwriting practice for kids — AI analyzes handwriting and recommends what to practice |
| [**mathmaster**](https://github.com/magnusfroste/mathmaster) | Multiplication mastery with gamification |
| [**multiply-magic**](https://github.com/magnusfroste/multiply-magic) | Magical multiplication practice for young learners |
| [**geogeniet**](https://github.com/magnusfroste/geogeniet) | Interactive geometry learning through play |
| [**map-game**](https://github.com/magnusfroste/map-game) | Interactive geography challenges and world knowledge |
| [**korsord**](https://github.com/magnusfroste/korsord) | Swedish crossword puzzles for vocabulary building |
| [**wordris**](https://github.com/magnusfroste/wordris) | Word puzzle game with Tetris-style mechanics |
| [**codeadventure**](https://github.com/magnusfroste/codeadventure) | Learn programming through interactive adventure stories |
| [**scenskolan**](https://github.com/magnusfroste/scenskolan) | Acting skills and character dialogue practice |
| [**julkalendern**](https://github.com/magnusfroste/julkalendern) | AI-assisted Santa Calendar with daily messages and conversational AI |
| [**pusselmagi**](https://github.com/magnusfroste/pusselmagi) | Magical puzzle game with enchanting challenges |
| [**brickpussel**](https://github.com/magnusfroste/brickpussel) | Brick puzzle challenges and spatial reasoning games |
| [**roleplaygame**](https://github.com/magnusfroste/roleplaygame) | Interactive roleplay for collaborative storytelling |

---

💡 **80+ open-source projects** — feel free to use, modify, and learn from them! Most are MIT; [Sluss](https://github.com/magnusfroste/sluss-eu) is AGPL-3.0.

⭐ **Star your favorites** to show support and stay updated with new features!
