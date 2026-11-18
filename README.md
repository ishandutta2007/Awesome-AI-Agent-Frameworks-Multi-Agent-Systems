# Awesome-AI-Agent-Frameworks-Multi-Agent-Systems

## Top AI Agent Frameworks & Multi-Agent Systems Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Multi-Agent Collaboration, Cyclic State Graphs, Autonomous Swarms, Visual Flow Builders & Production Runtimes*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Frameworks & Multi-Agent Systems**. These tools enable developers and organizations to coordinate specialized AI agents, design cyclic state-machine workflows, manage shared memory and tool handoffs, and deploy autonomous multi-agent swarms in production.



**Examples** include CrewAI Enterprise, LangGraph Platform, AutoGen Studio, Dify, Flowise Cloud, Botpress, Letta, SuperAGI, Stack AI, Fixie.ai, and atomicbot-ai/atomic-agent (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for Python and TypeScript multi-agent orchestration, visual low-code flow builders, stateful agent memory, SOP-driven software swarms, and lightweight atomic agent architectures — ideal for AI architects, researchers, and developers building transparent multi-agent systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI Agent and Agentic AI market size is estimated at approximately $7.84 billion in 2025 and is projected to reach $52.62 billion by 2030 (CAGR of 46.3% per MarketsandMarkets), with total enterprise agentic AI software spend scaling toward $985 billion by 2030 (Gartner). The sector is currently **moderately to highly fragmented**—characterized by fierce competition across orchestration layers, memory runtimes, voice gateways, and low-code builders—with rapid consolidation underway via major tech acquisitions rather than an entrenched winner-take-all monopoly.



## SaaS/Hosted Platforms

| Platform | Description | Estimated Size (Valuation / Scale) | Pricing (Starting Paid Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[LangGraph Platform](https://langchain.com)** | Managed cloud infrastructure for deploying, scaling, and debugging stateful cyclic multi-agent graphs with LangSmith integration. | **$3.0B** (Series C valuation; ~$460M total raised) | **$39 / user / month** (Plus tier; includes 1 small serverless agent server & 10,000 monthly traces) | **Free tier forever**: 1 user seat, 5,000 base traces/month, 14-day data retention, up to 100k local node runs |
| **[Dify Cloud](https://dify.ai)** | Hosted LLM app and agentic workflow platform combining visual orchestration, RAG pipelines, model routing, and API publishing. | **$180M** (Series Pre-A valuation; ~$30M raised) | **$59 / month** (Professional tier; includes 5,000 messages/mo, 50 apps, 3 team members) | **Free tier forever** (Sandbox plan): 1 member, 5 apps, 200 one-time message credits, 50 MB / 50 docs storage |
| **[Botpress Cloud](https://botpress.com)** | Enterprise conversational AI and autonomous agent studio with visual flow building, knowledge base sync, and omnichannel deployment. | **$120M** (Series B valuation; ~$40M+ raised, ~$10M+ ARR) | **$150 / month** (Plus tier billed annually / $189 monthly; includes 250 conversations/mo & $25 AI credits) | **Free tier forever**: 3 workspace seats, up to 3 AI agents, up to 100 conversations/month (hard capped) |
| **[CrewAI Enterprise](https://crewai.com)** | Cloud-hosted multi-agent orchestration platform featuring visual crew and flow builders, RBAC, tracing, and managed deployments. | **$76M–$93M** (Estimated valuation; $18M Series A, ~$2.4M–$3.2M ARR) | **$25 / month** (Starting paid tier / Pro via marketplace; Custom Enterprise at $60,000+/yr) | **Free tier forever** (Basic plan): Visual editor & copilot, 50 workflow executions/month, 2 automations |
| **[Stack AI](https://stack-ai.com)** | Enterprise AI workflow and multi-agent automation platform with SOC2/HIPAA compliance and pre-built business connectors. | **$75M** (Acquired by Asana; previously $64M valuation, ~$20M raised) | **Custom Enterprise** (Self-serve paid tiers retired post-acquisition; contact sales for pricing) | **Free tier forever**: 1 user seat, 2 projects, 500 workflow runs/month, Discord community support |
| **[Letta Cloud](https://letta.com)** | Hosted stateful agent runtime built on MemGPT principles for long-term hierarchical memory and multi-session context. | **$70M** (Seed valuation; $10M raised, ~$1.4M ARR) | **$20 / month** (Pro plan; includes up to 20 stateful agents and monthly credit allowance) | **Free tier forever**: Up to 3 stateful agents, 5 MiB storage per memory repository (BYO LLM API keys) |
| **[SuperAGI Cloud](https://superagi.com)** | Cloud-based autonomous agent platform for concurrent agent runs, marketplace toolkits, and trajectory performance telemetry. | **~$60M–$75M** ("Sub-$100M" Series A valuation; ~$15M raised, ~$9.9M ARR) | **$19 / month** (Starting paid starter tier; credit-based usage for multi-agent workflows) | **Free tier forever**: Basic cloud agent access, community tools, Bring-Your-Own-Key (BYOK) execution |
| **[Fixie.ai](https://fixie.ai)** | Speech-native voice AI and conversational agent runtime platform (operating as Ultravox). | **$51.5M** (Seed valuation; $17M raised, acquired by Inworld AI) | **$100 / month** (Pro plan; uncapped concurrency, outbound scheduler, 5 voice clones, 20 RAG corpora) | **Free tier forever** (Pay-as-you-go starter): 30 free call minutes, max 5 concurrent calls, unlimited playground testing |
| **[Relevance AI](https://relevanceai.com)** | Low-code cloud workforce platform for building, chaining, and scheduling teams of autonomous AI agents across business operations. | **~$50M+** (Est. valuation; ~$37M–$42M raised across Series A/B, ~$2.5M+ ARR) | **$29 / month** (Pro plan billed monthly / $19 monthly billed annually; includes 2,500 Actions & 2 builders) | **7-day free trial** with annual subscription toggle (permanent free plan retired; limited trial credits) |
| **[Flowise Cloud](https://flowiseai.com)** | Managed visual drag-and-drop platform for building and deploying multi-agent workflows and tool-calling assistants via APIs. | **~$10M–$20M** (Acquired by Workday; previously raised seed round, ~$1M ARR) | **$35 / month** (Starter plan; includes unlimited flows, ~10,000 predictions/month, 1 GB storage) | **Free tier forever**: 2 flows & assistants, 100 predictions/month, 5 MB storage, community support |





## Open-Source GitHub Projects



- **[atomicbot-ai/atomic-agent](https://github.com)**  

  Lightweight open-source multi-agent framework built on atomic, composable agent primitives, structured I/O schemas, and deterministic pipeline chaining.



- **[CrewAI](https://github.com)**  

  Popular open-source (`MIT`) Python framework for orchestrating role-playing autonomous AI agents and event-driven deterministic Flows.



- **[LangGraph](https://github.com)**  

  Open-source (`MIT`) framework for building resilient, stateful, multi-actor agent applications as cyclic graphs with fine-grained control over state and human-in-the-loop interrupts.



- **[Microsoft AutoGen & AutoGen Studio](https://github.com)**  

  Open-source programming framework and low-code web UI for building event-driven, asynchronous multi-agent conversational systems.



- **[AG2 (formerly AutoGen Community)](https://github.com)**  

  Community-led open-source (`Apache-2.0`) multi-agent programming framework continuing the classic `pyautogen` architecture with nested chats, group chats, and swarm patterns.



- **[Letta (formerly MemGPT)](https://github.com)**  

  Open-source (`Apache-2.0`) stateful agent framework equipping LLMs with self-editing hierarchical memory, persistent storage, and multi-agent communication.



- **[Dify](https://github.com)**  

  Production-ready open-source platform for agentic workflow development, visual prompt orchestration, RAG pipelines, and multi-model routing.



- **[Flowise](https://github.com)**  

  Open-source (`Apache-2.0`) low-code visual builder for rapidly prototyping and self-hosting multi-agent systems (`Agentflows`) and tool-calling chains.



- **[Botpress](https://github.com)**  

  Open-source conversational AI framework and runtime for building, testing, and deploying custom NLU and LLM-powered autonomous agents.



- **[SuperAGI](https://github.com)**  

  Dev-first open-source (`MIT`) autonomous AI agent framework supporting concurrent multi-agent provisioning, graphical trajectory tracking, and vector memory.



- **[OpenAI Agents SDK & Swarm](https://github.com)**  

  Lightweight open-source (`MIT`) Python runtime for multi-agent handoffs, guardrails, session state, and built-in trace inspection.



- **[Google Agent Development Kit (ADK)](https://github.com)**  

  Code-first open-source (`Apache-2.0`) toolkit for developing, evaluating, and deploying modular multi-agent hierarchies with bidirectional streaming support.



- **[Agno (formerly Phidata)](https://github.com)**  

  High-performance open-source (`MPL-2.0`) framework and runtime for building multi-modal agent teams with shared memory, knowledge bases, and deterministic workflows.



- **[CAMEL-AI](https://github.com)**  

  Open-source (`Apache-2.0`) multi-agent framework focused on scalable communicative agents, role-playing societies, synthetic data generation, and task automation.



- **[MetaGPT](https://github.com)**  

  Open-source (`MIT`) multi-agent meta-programming framework that assigns standardized operating procedures (SOPs) to product managers, architects, and software engineers.



- **[ChatDev (OpenBMB)](https://github.com)**  

  Open-source (`Apache-2.0`) communicative multi-agent software development company framework where specialized agents collaborate across design, coding, testing, and documentation phases.



- **[AgentScope (Alibaba)](https://github.com)**  

  Developer-centric open-source (`Apache-2.0`) multi-agent platform featuring fault-tolerant distributed execution, actor-based message passing, and visual monitoring.



- **[LlamaIndex Workflows](https://github.com)**  

  Open-source (`MIT`) event-driven orchestration framework engineered for multi-agent handoffs, complex RAG pipelines, and document-centric runtimes.



- **[Semantic Kernel](https://github.com)**  

  Enterprise-grade open-source (`MIT`) SDK from Microsoft for orchestrating multi-agent collaborations, plugins, and planners across Python, C#/.NET, and Java.



- **[Pydantic AI](https://github.com)**  

  Type-safe open-source (`MIT`) Python agent framework engineered for validated structured outputs, agent delegation, and durable production workflows.



- **[Mastra](https://github.com)**  

  Open-source (`Apache-2.0`) TypeScript multi-agent framework featuring graph workflows, shared memory, evals, and native Next.js/React integration.



- **[ElizaOS (ai16z)](https://github.com)**  

  Open-source (`MIT`) TypeScript multi-agent runtime designed for autonomous characters, cross-platform social integrations, and modular plugin ecosystems.



### Additional Strong Open-Source Options



- **[Atomic Agents (`BrainBlend-AI/atomic-agents`)](https://github.com)** for ultra-lightweight, Pydantic-first input/output agent chaining without heavy framework magic.

- **[Model Context Protocol (MCP) Servers](https://github.com)** for standardized tool, database, and API sharing across multi-agent swarms.

- **[n8n](https://github.com)** for fair-code/open-source visual workflow automation with native LangChain multi-agent nodes and 400+ enterprise integrations.

- **[Mem0](https://github.com)** and **[Graphiti (Zep)](https://github.com)** for shared episodic, semantic, and temporal graph memory across multi-agent teams.

- **[Langfuse](https://github.com)** and **[Arize Phoenix](https://github.com)** for open-source OpenTelemetry trace visualization across nested multi-agent calls.



**Frameworks for building custom systems**: Combine **CrewAI** or **LangGraph** with **atomicbot-ai/atomic-agent**, **Letta / Mem0** (shared memory), **Model Context Protocol (MCP)** (tools), and **Langfuse** (multi-agent tracing) for transparent, production-grade multi-agent systems.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
