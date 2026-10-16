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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ChatGPT Enterprise](https://openai.com/enterprise/)**  

  Enterprise AI workspace with **unlimited GPT-4 access**, **SSO/SAML**, **admin console**, and **zero data retention**. Features **custom knowledge bases** and **GPTs** for team-specific workflows.



- **[Claude Enterprise](https://www.anthropic.com/enterprise)**  

  Enterprise access to Claude with **Projects** for document-grounded conversations, **SSO**, **admin controls**, and **higher rate limits**. Features **citation-backed answers** from uploaded documents.



- **[Microsoft Copilot](https://www.microsoft.com/en-us/microsoft-copilot)**  

  AI assistant integrated across Microsoft 365. Features **Graph-grounded responses** from organizational data, **Copilot Studio** for custom agents, and **enterprise data protection**.



- **[Glean](https://www.glean.com/)**  

  **The category-defining enterprise search and AI platform.** **100+ connectors**, permissions-aware retrieval that inherits source-system ACLs, and Glean Assistant for natural-language Q&A grounded in corporate knowledge. **No public pricing**—quoted annually, typically six figures for mid-market and above.



- **[Notion AI](https://www.notion.so/product/ai)**  

  AI features embedded across Notion's all-in-one workspace. **Q&A across your entire workspace**, AI writing assistance, autofill database properties, and AI meeting notes.



- **[Perplexity Enterprise](https://www.perplexity.ai/enterprise)**  

  Enterprise version of Perplexity's answer engine. Features **internal knowledge search combined with web search**, user management, and data retention controls. **$40/user/month** (annual) as of 2026.



- **[Cohere Coral](https://cohere.com/coral)**  

  Enterprise knowledge assistant with **RAG over internal documents**, connectors to common SaaS apps, and **citation-backed answers**. Built on Cohere's Command models.



- **[Writer.com](https://writer.com/)**  

  Enterprise AI writing and knowledge platform. Features **AI-powered document Q&A**, **style guides**, and **brand-consistent content generation**.



- **[Jasper Enterprise](https://www.jasper.ai/)**  

  Enterprise AI marketing platform with **brand voice**, **knowledge base**, and **campaign workflows**. Features **Jasper Chat** for grounded Q&A.



- **[Moveworks](https://www.moveworks.com/)**  

  AI-powered employee support platform with **knowledge retrieval** across IT, HR, and finance systems. Features **autonomous issue resolution** and **workflow automation**.



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
