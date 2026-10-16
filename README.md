# Awesome-AI-Workspace-RAG

## Top AI Workspace & RAG Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Local RAG Workspaces, Enterprise Knowledge Retrieval & Agent-Augmented Chat*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Workspace & RAG**. These tools enable organizations to build private, context-aware AI workspaces that retrieve from internal documents, connected applications, and knowledge bases—keeping sensitive data on-premises while delivering reliable, citation-backed answers.



**Examples** include ChatGPT Enterprise, Claude Enterprise, Microsoft Copilot, Glean, Notion AI, Perplexity Enterprise, Cohere Coral, Writer.com, Jasper Enterprise, and Moveworks (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local RAG, and open workspace infrastructure—ideal for teams seeking transparent, vendor-independent AI workspaces.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The enterprise AI Workspace and Retrieval-Augmented Generation (RAG) market is estimated at approximately **$2.5B to $4B** in 2024–2026 and is projected to expand toward **$10B–$43B+ by the early 2030s** at a 25–40% CAGR. The sector is **moderately to highly fragmented** rather than winner-take-all: while mega-cap platform providers (Microsoft Copilot, OpenAI, Anthropic) dominate horizontal workplace suites, specialized enterprise search engines (Glean, Moveworks), vertical copilots, and rapidly advancing open-source RAG pipelines maintain substantial market differentiation and avoid complete platform consolidation.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Pricing (Starting Tier) | Free Tier / Trial Limits | Description & Key Features |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Copilot](https://www.microsoft.com/en-us/microsoft-copilot)** | ~$3.1T Market Cap | $30 / user / month (Microsoft 365 Copilot add-on, billed annually) | **Free tier available**: Basic Copilot web chat is free for personal Microsoft accounts with daily prompt limits (up to ~30 turns/session); enterprise Graph-grounded Copilot offers no free tier (requires paid 365 business license). | AI assistant integrated across Microsoft 365. Features Graph-grounded responses from organizational data, Copilot Studio for custom agents, and enterprise data protection. |
| **[ChatGPT Enterprise](https://openai.com/enterprise/)** | ~$157B Valuation | $25 / user / month (ChatGPT Team, billed annually at $30/mo monthly; Enterprise custom quoted ~60/user/mo) | **Free tier available**: Free plan includes access to GPT-4o with standard dynamic rate limits (switches to mini when capacity reached); does not include team knowledge bases or enterprise admin controls. | Enterprise AI workspace with unlimited GPT-4 access, SSO/SAML, admin console, zero data retention, and custom knowledge bases/GPTs for team workflows. |
| **[Claude Enterprise](https://www.anthropic.com/enterprise)** | ~$40B Valuation | $25 / user / month (Claude Team, billed annually; Enterprise tier custom quoted ~30-50/user/mo) | **Free tier available**: Free Claude plan gives personal access to Claude 3.5 Sonnet with daily message caps (resets every 5 hours based on server load); does not include team Projects or enterprise admin controls. | Enterprise access to Claude with Projects for document-grounded conversations, SSO, admin controls, higher rate limits, and citation-backed answers. |
| **[Notion AI](https://www.notion.so/product/ai)** | ~$10B Valuation | $8 / user / month (billed annually, or $10/user/mo monthly as an add-on to Notion plans) | **Free trial available**: 20 free AI responses per member for workspace evaluation before requiring the $8–$10/user/month add-on subscription. | AI features embedded across Notion's all-in-one workspace. Q&A across entire workspace, AI writing assistance, autofill database properties, and AI meeting notes. |
| **[Perplexity Enterprise](https://www.perplexity.ai/enterprise)** | ~$9B Valuation | $40 / user / month (billed annually, or $40/user/mo monthly for Enterprise Pro) | **Free tier available**: Standard Perplexity Free plan provides unlimited basic quick searches and up to 5 Pro Searches (with file upload/reasoning) per day. | Enterprise answer engine combining internal knowledge search with web search, user management, SOC 2 compliance, and strict data retention controls. |
| **[Cohere Coral](https://cohere.com/coral)** | ~$5.5B Valuation | $10 / month (Developer API pay-as-you-go starting baseline; enterprise Coral managed deployment custom quoted) | **Free trial available**: Cohere provides a free trial evaluation key with 1,000 free API calls/month for testing models and RAG endpoints. | Enterprise knowledge assistant with RAG over internal documents, connectors to common SaaS apps, and citation-backed answers built on Cohere Command models. |
| **[Glean](https://www.glean.com/)** | ~$4.6B Valuation | ~$35 / user / month (mid-market/enterprise pricing, typically starting at $25,000–$60,000/year minimum contract value) | **No self-serve free tier or free trial**: Sales-led evaluation only via scheduled POCs for qualified enterprise deployments (typically 50–100+ seats minimum). | Enterprise search and AI platform with 100+ connectors, permissions-aware retrieval mirroring source-system ACLs, and Glean Assistant for corporate knowledge Q&A. |
| **[Moveworks](https://www.moveworks.com/)** | ~$2.1B Valuation | ~$150 / user / year on AWS Marketplace (~$15–$45/employee/year enterprise-wide; min contract ~$50,000–$100,000/yr) | **No free tier or public trial**: Sales-led enterprise engagements only with guided pilot/PoC on custom request. | AI-powered employee support platform with knowledge retrieval across IT, HR, and finance systems, autonomous issue resolution, and workflow automation. |
| **[Writer.com](https://writer.com/)** | ~$1.9B Valuation | $18 / user / month (Team plan for up to 5 users, billed monthly or annually) | **Free trial available**: 14-day free trial on the Team tier with access to Palmyra LLMs, document Q&A, and style guides. | Enterprise AI writing and knowledge platform with AI-powered document Q&A, style guides, and brand-consistent content generation. |
| **[Jasper Enterprise](https://www.jasper.ai/)** | ~$1.5B Valuation | $39 / seat / month (Creator plan, billed annually at $49/mo monthly; Pro tier is $59/seat/mo) | **Free trial available**: 7-day free trial on Pro and Creator plans providing full access to brand voice and workspace features. | Enterprise AI marketing platform with brand voice, knowledge base, campaign workflows, and Jasper Chat for grounded Q&A. |



## Open-Source GitHub Projects



- **[AnythingLLM (Mintplex Labs)](https://github.com/Mintplex-Labs/anything-llm)**  

  **The most feature-complete open-source all-in-one AI workspace with local RAG and agent capabilities** (MIT) . **45,000+ GitHub stars**—one of the most popular self-hosted AI applications . **The all-in-one AI application, tool suite, and API for RAG & Agents for Docker & Desktop** . **Turn any document, resource, or piece of content into context that any LLM can use as references during chatting** . **Workspaces** function like threads with containerized documents—can share documents but keep context isolated per workspace . **Supports commercial and open-source LLMs** (OpenAI, Anthropic, Google Gemini, Ollama, LM Studio, LocalAI, Together AI, Perplexity, OpenRouter, Mistral, Groq) and **vector databases** (LanceDB default, Pinecone, Chroma, Weaviate, QDrant, Milvus, Zilliz) . **Key features**: **Multi-user support with permissions** (Docker only), **custom AI Agents**, **no-code AI Agent builder**, **full MCP compatibility**, **multi-modal support**, **embeddable chat widget** (Docker only), **in-chat citations**, and **full Developer API** . **Desktop version** for one-click local install (Mac, Windows, Linux) with full privacy—**no multi-user support, no public internet exposure** . **Docker version** for team deployment with multi-user management, embeddable widgets, and web-accessible UI .



- **[Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)**  

  **The most mature open-source enterprise search and AI assistant platform** (MIT for core) . **The leading open-source Glean alternative.** Features **40+ connectors** (Slack, Google Drive, Confluence, Jira, Notion, GitHub, SharePoint, Teams, and more), **permission-aware retrieval** that mirrors source-system ACLs, **Onyx Assistant** for natural-language Q&A with citations, **custom assistants** with scoped knowledge and personas, and **multi-LLM support** . **Uses contextual retrieval, advanced RAG, hybrid search, and AI-generated knowledge graphs** for reliable responses with least hallucinations . **Self-hosted via Docker Compose or Kubernetes.** Used by Netflix, Ramp, and other enterprises. Enterprise edition adds SSO, RBAC, and advanced analytics.



- **[Dify](https://github.com/langgenius/dify)**  

  **Open-source LLM app development platform with RAG, agents, and visual workflows** (Apache-2.0 with conditions) . **157,000+ GitHub stars** . **Combines AI workflow, RAG pipeline, agent capabilities, model management, and observability** (Opik, Langfuse, Arize Phoenix) . **Visual canvas** for building and testing AI workflows, **comprehensive model support** (GPT, Mistral, Llama3, any OpenAI-compatible), **Prompt IDE**, **RAG pipeline** with PDF/PPT extraction, **autonomous agents with sandbox**, and **LLMOps monitoring** . **Publish as app, API, embed, or MCP-compatible tool.** Deploy via Docker Compose with minimum **2 CPU cores and 4 GiB RAM** . **The most complete open-source alternative to commercial LLMOps platforms** for teams wanting visual workflow building.



- **[RAGFlow](https://github.com/infiniflow/ragflow)**  

  **Open-source RAG engine built around deep document understanding** (Apache-2.0) . **55,000+ GitHub stars** . **Ingests PDFs, Word docs, scanned images, and tables, chunks them with the DeepDoc parser, indexes embeddings in Elasticsearch, and serves grounded LLM Q&A with traceable citations** . **DeepDoc parser** handles PDFs, DOCX, XLSX, PPTX, scanned images, HTML, Markdown, and tables with layout-aware chunking—**best in class for PDFs/tables** . **Hybrid retrieval** (Elasticsearch BM25 + dense vector search with rerankers), **paragraph-level citations**, **multi-tenant**, and **agent workflows** with visual flow builder . **Ingestion Pipeline** (v0.21.0+) allows custom ETL workflows with Parser, Transformer, and Indexer stages . **Pick RAGFlow when document parsing fidelity matters most** .



- **[LobeChat](https://github.com/lobehub/lobe-chat)**  

  **Modern open-source AI chat framework with multi-provider support** (LobeHub Community License) . **62,000+ GitHub stars** . Features **plugin system**, **knowledge base**, **artifacts**, and **one-click deployment** (Vercel, Docker). **The most visually polished open-source chat interface** .



- **[Open WebUI](https://github.com/open-webui/open-webui)**  

  **Extensible, feature-rich, user-friendly self-hosted AI platform** (BSD-3-Clause with branding clause) . **150,000+ GitHub stars** . Features **multi-model support** (Ollama, OpenAI-compatible APIs), **RAG document integration**, **RBAC**, **pipelines/plugins**, and **offline operation**. **The most widely deployed open-source AI interface**—runs entirely offline with Ollama or connects to any OpenAI-compatible backend .



### Additional Strong Open-Source Options



- **[LibreChat](https://github.com/danny-avila/LibreChat)** — Enhanced ChatGPT clone with multi-provider support, agents, code interpreter, and conversation branching (MIT) . **42,000+ GitHub stars** .

- **[Khoj](https://github.com/khoj-ai/khoj)** — Open-source AI personal assistant that searches the web and your documents (AGPL-3.0) . **25,000+ GitHub stars**.

- **[RAGFlow](https://github.com/infiniflow/ragflow)** — See above.

- **[Haystack (deepset)](https://github.com/deepset-ai/haystack)** — Production-ready NLP framework with typed pipelines for RAG (Apache-2.0) . **21,000+ GitHub stars** .

- **[SemantixRAG](https://pypi.org/project/semantixrag/)** — Open-source RAG platform with GraphRAG, PII scanning, and observability (PyPI) . Features **Neo4j knowledge graph**, **OpenSearch hybrid retrieval**, **Microsoft Presidio PII detection**, and **GDPR DSAR automation** .

- **[Velites](https://pypi.org/project/velites/)** — Minimal, local-first AI workbench with SQLite-powered RAG (Apache-2.0, pre-alpha) . **Single-process model on distroless container**—no external database servers .

- Community **n8n** workflows for RAG pipeline automation and workspace integration.



**Frameworks for building custom systems**: Combine **AnythingLLM** for all-in-one local RAG workspaces with **Onyx** for permission-aware enterprise search, **Dify** for visual workflow building, **RAGFlow** for high-fidelity document parsing, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade AI workspace platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI workspace platforms handling internal documents must comply with data protection regulations (GDPR, CCPA, etc.) and respect source-system permissions.

- **Open-source AI workspaces are mature and production-ready.** AnythingLLM provides all-in-one local RAG with agents and multi-user support . Onyx delivers permission-aware enterprise search with 40+ connectors . Dify combines visual workflows, RAG, and agents with 157K+ stars . RAGFlow offers best-in-class document parsing . **These are genuine alternatives to Glean and ChatGPT Enterprise.**

- **Workspace isolation is a core feature.** AnythingLLM's workspaces keep document contexts separate—"they do not talk to each other so you can keep your context for each workspace clean" . **Mixing documents across topics dilutes RAG relevance** .

- **Desktop vs Docker matters for team deployment.** AnythingLLM Desktop is **single-player only**—no multi-user support, no public internet exposure . **Docker version** adds multi-user management, embeddable widgets, and web-accessible UI . **Choose based on whether one person or a team will use it.**

- **Document parsing quality determines answer quality.** RAGFlow's DeepDoc parser handles complex tables, scanned documents, and layout-aware chunking that simpler parsers fail on . **If your knowledge lives in PDFs and legacy documents, parsing is the bottleneck.**

- Self-hosted open-source solutions require proper security hardening, document storage encryption, and ongoing maintenance. **RAG systems are only as good as their retrieval**—test with real queries before production deployment.



---



**Made for AI engineers, platform teams, and developers building transparent AI workspace solutions.**  

Let's make AI Workspace & RAG more open, data-driven, and context-aware.
