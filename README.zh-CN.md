<div align="center">

# 🤖 Awesome AI Agents 2026 · 中文版

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/awesome-ai-agents-2026?style=social)](https://github.com/Zijian-Ni/awesome-ai-agents-2026)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![English Version](https://img.shields.io/badge/Lang-English-informational.svg)](README.md)

**2026 年 AI 模型、Agent 框架、工具、协议与资源精选清单 —— 这是 Agent 真正成为基础设施的一年。**

*覆盖：基础大模型、多模态生成、Agent 协议（MCP / A2A）、编程 Agent、计算机使用、生成式 AI 等。*

### 🏷️ 状态图例

- 🆕 **New** — 60 天内加入，效果尚待沉淀
- 📦 **Archived** — 仓库已归档，仅作历史参考
- 💤 **Stale** — 6 个月以上无提交，可能仍可用但已不再活跃维护
- ⚠️ **Unverified** — 新提交且第三方使用证据有限（star 少 / 单作者 / 同款 PR 批量铺货）。**仅作可见性收录，不背书**，使用前请自行评估
- 🇨🇳 **Chinese ecosystem** — 中国大陆团队主导或主要面向中文市场的项目

</div>

---

> **说明**：本中文版与英文版 [README.md](README.md) 保持同步。中文版翻译了所有章节标题与核心条目描述，部分长描述以英文为准。如发现不一致，**以英文版为准**。
> 翻译/补充欢迎提 PR，请优先英文版改动。

---

## 目录

- [🧠 基础大模型 2026](#-基础大模型-2026)
- [🎨 多模态与生成式 AI](#-多模态与生成式-ai)
- [🔗 Agent 协议与标准](#-agent-协议与标准)
- [🏗️ Agent 框架](#️-agent-框架)
- [🛠️ Agent IDE 与可视化构建器](#️-agent-ide-与可视化构建器)
- [🧠 Agent 记忆](#-agent-记忆)
- [🔌 工具与 API 集成](#-工具与-api-集成)
- [🧪 Agent 沙箱与计算隔离](#-agent-沙箱与计算隔离)
- [🛡️ Agent 安全](#️-agent-安全)
- [🔍 RAG 与知识库](#-rag-与知识库)
- [💻 编程 Agent](#-编程-agent)
- [🤖 Physical AI / 具身智能](#-physical-ai--具身智能)
- [🎮 Agent 仿真与世界模型](#-agent-仿真与世界模型)
- [📊 评测与 Leaderboard](#-评测与-leaderboard)
- [🖥️ Computer Use / 桌面 Agent](#️-computer-use--桌面-agent)
- [🌐 浏览器与 Web Agent](#-浏览器与-web-agent)
- [🗣️ 语音与多模态 Agent](#️-语音与多模态-agent)
- [📱 个人 AI Agent](#-个人-ai-agent)
- [📱 手机 Agent](#-手机-agent)
- [🏢 企业级 Agent 平台](#-企业级-agent-平台)
- [📊 Agent 评估与可观测性](#-agent-评估与可观测性)
- [🔬 AI 研究工具](#-ai-研究工具)
- [📚 学习资源](#-学习资源)
- [🇨🇳 中国 AI 生态](#-中国-ai-生态)
- [📝 横向对比表](#-横向对比表)
- [📅 2026 AI 时间线](#-2026-ai-时间线)

---

## 🧠 基础大模型 2026

*覆盖 OpenAI、Anthropic、Google、Meta、阿里、DeepSeek、月之暗面 等 20+ 家厂商。完整 65+ 条目录见 [英文版](README.md#-foundation-models-2026)。本节列出 2026 年最常被使用的旗舰模型。*

- **OpenAI**：[GPT-5.5 / 5.5 Pro / 5.5-Cyber](https://openai.com/index/gpt-5-5-system-card/)、[GPT-5.4](https://openai.com/)、[Codex CLI](https://github.com/openai/codex)
- **Anthropic**：[Claude Opus 4.7](https://www.anthropic.com/) (SWE-bench 87.6%)、Claude Sonnet 4.6 (1M 上下文)、[Claude Mythos Preview](https://www.anthropic.com/)
- **Google DeepMind**：Gemini 3.1 Pro / Flash / Flash Lite、[Gemini Robotics ER-1.6](https://deepmind.google/)
- **Meta**：Llama 4.x 系列、[Muse Spark](https://ai.meta.com/) (Meta Superintelligence Labs)
- **🇨🇳 阿里 Qwen**：Qwen3.6-Max / Plus / 27B / 35B-A3B（Apache-2.0）
- **🇨🇳 DeepSeek**：DeepSeek V4 Pro & Flash（1.6T MoE，1M 上下文，MIT）
- **🇨🇳 月之暗面 Moonshot**：[Kimi K2.6](https://www.moonshot.ai/)（1T MoE，1000-agent swarm）
- **🇨🇳 智谱 / Z.ai**：GLM-5（开源在华为昇腾上训练，744B MoE）
- **🇨🇳 字节 Doubao**：Doubao 1.5 Pro
- **🇨🇳 腾讯 Hunyuan**：Hy3 Preview（295B/21B MoE，256K 上下文）
- **NVIDIA Nemotron 3**、**Apple Foundation Models**、**Samsung Gauss 2.3**、**xAI Grok 4**、**Cohere + Aleph Alpha** 合并实体

---

## 🎨 多模态与生成式 AI

- **图像**：[Flux](https://github.com/black-forest-labs/flux)（💤 stale 2025-07）、[Ideogram](https://ideogram.ai/)、[Midjourney](https://www.midjourney.com/)、Imagen 4、Stable Diffusion XL Turbo、🇨🇳 [Tianma](https://tongyi.aliyun.com/)（阿里图生视频）
- **视频**：[Kling VIDEO 3.0](https://kling.ai/)（🇨🇳 快手）、Runway Gen-4、Veo 3、Pika 2.5。Sora 已于 2026-04 关停。
- **音频/音乐**：[Bark](https://github.com/suno-ai/bark)（💤 stale 2024-08）、[Lyria 3 Pro](https://deepmind.google/)、ElevenLabs

---

## 🔗 Agent 协议与标准

- [**MCP** (Model Context Protocol)](https://github.com/modelcontextprotocol/servers) — 已成为 Agent 工具调用的事实标准（Anthropic 主推，2025-12 捐赠给 Linux Foundation 旗下的 Agentic AI Foundation）
- [**A2A**](https://github.com/google/A2A) — Google 主导的 Agent 间通信协议，2026 年已有 150+ 合作组织
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python)（2026-04-15 大更新：原生沙箱、MCP 一等公民、子 agent handoff）

---

## 🏗️ Agent 框架

| 框架 | 语言 | 多 Agent | 状态/图 | 流式 | License | 适合场景 |
|------|------|---------|---------|------|---------|---------|
| [LangGraph](https://github.com/langchain-ai/langgraph) | Python/JS | ✅ | ✅ 一等公民 | ✅ | MIT | 生产级有状态工作流 |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Python | ✅ 角色扮演 | ⚠️ 任务图 | ✅ | MIT | 角色化 Agent 团队 |
| [AutoGen](https://github.com/microsoft/autogen) / [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/) | Python/.NET | ✅ | ⚠️ | ✅ | MIT | 企业级多 Agent |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Python | ✅ handoff | ❌ | ✅ | MIT | OpenAI 原生 |
| [Mastra](https://github.com/mastra-ai/mastra) | TypeScript | ✅ | ✅ workflow | ✅ | Elastic-2.0 | TS 优先 |
| [Google ADK](https://github.com/google/adk-python) | Python/Java | ✅ 层级 | ⚠️ | ✅ | Apache-2.0 | Gemini + Vertex AI |
| [DSPy](https://github.com/stanfordnlp/dspy) | Python | ⚠️ | ⚠️ 编程式 | ✅ | MIT | 程序化 prompt 优化 |
| [🇨🇳 MetaGPT](https://github.com/geekan/MetaGPT) | Python | ✅ SOP | ❌ | ✅ | MIT | 软件团队角色化 |
| [🇨🇳 AgentScope](https://github.com/modelscope/agentscope) | Python | ✅ | ✅ | ✅ | Apache-2.0 | 阿里 ModelScope 出品 |
| [Octomind](https://github.com/muvon/octomind) | Rust | ✅ | ⚠️ | ✅ | Apache-2.0 | 多模型 (13+) Rust 运行时 |
| [OpenClaw](https://github.com/openclaw/openclaw) | TypeScript | ✅ | ✅ | ✅ | Apache-2.0 | 个人 Agent 平台、ACP 集成 |

📦 已归档：`reworkd/AgentGPT`（2025-04）、`gpt-engineer-org/gpt-engineer`（2025-05）

---

## 🛠️ Agent IDE 与可视化构建器

- [LangGraph Studio](https://www.langchain.com/langgraph) — LangGraph 的可视化调试器
- [🇨🇳 Dify](https://github.com/langgenius/dify) — 开源 LLM 应用开发平台，主流低代码 Agent 画布
- [Agenta](https://github.com/agenta-ai/agenta) 🆕 — Prompt 实验场 + 评测 + 可观测性一体化
- [Vellum AI](https://www.vellum.ai/) — 闭源 SaaS
- [🇨🇳 Cozeloop](https://github.com/coze-dev/cozeloop) 🆕 — 字节 Coze 团队开源
- [🇨🇳 Bisheng](https://github.com/dataelement/bisheng) — 企业级 LLM DevOps（工作流、RAG、Agent、微调、评测）
- [n8n](https://github.com/n8n-io/n8n) — 通用工作流自动化，2026 年常用作 Agent 画布
- [Restack](https://www.restack.io/) — 持久化 Agent 运行时（Temporal 风格 replay）

---

## 🧠 Agent 记忆

- [Letta (MemGPT)](https://github.com/letta-ai/letta)、[Mem0](https://github.com/mem0ai/mem0)、[Zep](https://github.com/getzep/zep) / [Graphiti](https://github.com/getzep/graphiti)
- [LangMem](https://github.com/langchain-ai/langmem)、[Cognee](https://github.com/topoteretes/cognee)
- [Claude Managed Agents Memory](https://platform.claude.com/docs/en/release-notes/overview)（2026-04 公测）
- 💤 [Motorhead](https://github.com/getmetal/motorhead)（无更新自 2025-07）

---

## 🔌 工具与 API 集成

- [MCP Servers](https://github.com/modelcontextprotocol/servers) ⭐
- [Composio](https://github.com/ComposioHQ/composio) — 150+ 工具 + 托管认证
- [Arcade AI](https://github.com/ArcadeAI/arcade-ai)、[Toolhouse](https://toolhouse.ai/)
- [Firecrawl](https://github.com/mendableai/firecrawl)、[Crawl4AI](https://github.com/unclecode/crawl4ai) — 把网站变成 LLM-ready 数据
- ⚠️ [The Colony](https://thecolony.cc) — 自称 Agent 间社交网络。仓库 <30 天，0–2 star，单维护者；同款 PR 投了 15+ 个 awesome 列表 — **未验证**，仅作可见性收录

---

## 🧪 Agent 沙箱与计算隔离

让 Agent 安全执行生成代码的隔离运行时。完整对比表见英文版「Compare」章节。

- [E2B](https://github.com/e2b-dev/E2B) — OpenAI Agents SDK 默认执行层（云托管，~150ms 冷启）
- [Daytona](https://github.com/daytonaio/daytona) 🆕 — 弹性隔离开发环境，每个 Agent 任务一个（AGPL-3.0）
- [Modal](https://modal.com/) — Serverless Python + GPU
- [Microsandbox](https://github.com/superradcompany/microsandbox) 🆕 — 本地 microVM，隐私优先
- [🇨🇳 SandboxFusion](https://github.com/bytedance/SandboxFusion) — 字节多语言代码执行沙箱
- [Firecracker](https://github.com/firecracker-microvm/firecracker) — 上游 microVM 内核（E2B/Daytona 都用它）

---

## 🛡️ Agent 安全

- [LLM Guard](https://github.com/protectai/llm-guard)、[NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)、[Guardrails AI](https://github.com/guardrails-ai/guardrails)
- [Garak](https://github.com/NVIDIA/garak)（NVIDIA 出品的 LLM 漏洞扫描器）
- [PyRIT](https://github.com/Azure/PyRIT)（微软自动化红队框架）
- [AgentDojo](https://github.com/ethz-spylab/agentdojo) 🆕 — ETH 苏黎世的 Agent 攻防评测基准
- [ModelScan](https://github.com/protectai/modelscan) — 检测模型权重文件中的反序列化攻击
- [Invariant Guardrails](https://github.com/invariantlabs-ai/invariant) 🆕 — Agent 运行时策略执行
- 📦 [Rebuff](https://github.com/protectai/rebuff)（archived 2024-08）、💤 [Vigil](https://github.com/deadbits/vigil-llm)（2024-01 起无更新）

---

## 🔍 RAG 与知识库

- [LlamaIndex](https://github.com/run-llama/llama_index)、[Haystack](https://github.com/deepset-ai/haystack)、[Unstructured](https://github.com/Unstructured-IO/unstructured)
- 向量库：[Chroma](https://github.com/chroma-core/chroma)、[Weaviate](https://github.com/weaviate/weaviate)、[Qdrant](https://github.com/qdrant/qdrant)、[Milvus](https://github.com/milvus-io/milvus)、[Pinecone](https://www.pinecone.io/)
- [🇨🇳 RAGFlow](https://github.com/infiniflow/ragflow) — 深度文档理解 RAG（扫描 PDF / 表格 / 图表强）
- [🇨🇳 LightRAG](https://github.com/HKUDS/LightRAG) — 港大 HKUDS 出品的图式 RAG
- [🇨🇳 FastGPT](https://github.com/labring/FastGPT)、[🇨🇳 QAnything](https://github.com/netease-youdao/QAnything)（💤 2025-03）
- [Docling](https://github.com/DS4SD/docling)、[Kotaemon](https://github.com/Cinnamon/kotaemon)、[R2R](https://github.com/SciPhi-AI/R2R)
- 📦 [Vanna](https://github.com/vanna-ai/vanna)（archived 2026-02）— RAG-for-SQL

---

## 💻 编程 Agent

| 工具 | 形态 | 开源 | 免费层 | SWE-bench | 适合场景 |
|------|------|------|--------|-----------|----------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | CLI/IDE | ❌ | ⚠️ Pro | 80.9% | 长任务工程 |
| [Codex CLI](https://github.com/openai/codex) | CLI | ✅ | ✅ | Terminal-Bench 77.3% | OpenAI 原生 |
| [Cursor](https://www.cursor.com/) | IDE | ❌ | ✅(限) | n/a | 配对编程体验 |
| [Cline](https://github.com/cline/cline) | VS Code 扩展 | ✅ | ✅(BYO) | n/a | 开源替代 |
| [Aider](https://github.com/Aider-AI/aider) | CLI | ✅ | ✅(BYO) | Polyglot 强 | Git-aware 重构 |
| [Devin 3.0](https://www.cognition.ai/) | 云 | ❌ | ❌ | 领先 | 完全托管长任务 |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 自托管 | ✅ | ✅ | 有竞争力 | 自部署 SWE Agent |
| [🇨🇳 Kilo Code](https://www.kilocode.com/) | IDE | ❌ | — | n/a | 中文社区流行 Cursor 替代 |

---

## 🤖 Physical AI / 具身智能

- [Google Gemini Robotics ER-1.6](https://deepmind.google/) 🆕（2026-04-14）
- [NVIDIA Isaac GR00T](https://developer.nvidia.com/isaac/gr00t)、[NVIDIA Industrial AI Cloud](https://nvidianews.nvidia.com/) 🆕
- [Tesla Optimus Gen3](https://www.tesla.com/) 🆕（2026 夏量产）
- 🇨🇳 [Honour 荣耀人形](https://www.honor.com/)（2026 半马世界纪录）、[Zhiyuan 智元 AGIBOT](https://www.agibot.com/)、[Unitree H 系列](https://www.unitree.com/)
- 🇨🇳 [深圳人形机器人中试线](https://www.chinadailyhk.com/hk/article/631892) 🆕（2026-04-12 启用）

---

## 🎮 Agent 仿真与世界模型

- 💤 [Generative Agents](https://github.com/joonspk-research/generative_agents)（斯坦福经典 *Smallville*）
- 💤 [Voyager](https://github.com/MineDojo/Voyager)（Minecraft 终生学习 Agent）
- [SWE-Gym](https://github.com/SWE-Gym/SWE-Gym)、[WebArena](https://webarena.dev/)、[WorkArena](https://github.com/ServiceNow/WorkArena)
- [Genie 3 / 4](https://deepmind.google/) — Google DeepMind 可玩世界模型
- [NVIDIA Cosmos](https://github.com/nvidia-cosmos/cosmos-predict1) — 具身 AI 视频未来生成

---

## 📊 评测与 Leaderboard

- [BenchLM](https://benchlm.ai/)、[SWE-bench Verified](https://www.swebench.com/)
- [GPQA Diamond](https://github.com/idavidrein/gpqa) 💤、[ARC-AGI 2](https://arcprize.org/)、[OSWorld](https://os-world.github.io/)
- [LMArena](https://lmarena.ai/)（前 Chatbot Arena）、[MMLU-Pro](https://github.com/TIGER-AI-Lab/MMLU-Pro)、[LiveCodeBench](https://livecodebench.github.io/)、[Terminal-Bench](https://www.tbench.ai/)

---

## 🖥️ Computer Use / 桌面 Agent

- [Claude Computer Use](https://www.anthropic.com/)、[OpenAI Operator](https://openai.com/)、[Google Project Mariner](https://deepmind.google/)、[Microsoft Copilot Agents](https://www.microsoft.com/en-us/microsoft-copilot/)
- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter)
- 🇨🇳 [Manus AI](https://manus.im/)（北京 Butterfly Effect）、[Genspark](https://www.genspark.ai/)、[Perplexity Computer](https://www.perplexity.ai/)、[Beam AI](https://beam.ai/)

---

## 🌐 浏览器与 Web Agent

| 项目 | 思路 | 部署 | 优势 | License |
|------|------|------|------|---------|
| [Browser Use](https://github.com/browser-use/browser-use) | Vision + DOM (Playwright) | 自托管 | 92K star，社区第一 | MIT |
| [Stagehand](https://github.com/browserbase/stagehand) | 类型化 act/extract/observe | Browserbase / 自托管 | 强类型、结构化输出 | MIT |
| [Steel Browser](https://github.com/steel-dev/steel-browser) 🆕 | 无头 Chrome API | 自托管 / 云 | session + proxy + captcha | Apache-2.0 |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Vision-first | 自托管 | 抗动态页面强 | AGPL-3.0 |
| [AgentQL](https://github.com/tinyfish-io/agentql) | 查询语言 | SDK + 自托管 | 语义化 selector | MIT |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | MCP 原生 | 自托管 | MCP 客户端即插即用 | Apache-2.0 |
| [Hyperbrowser MCP](https://github.com/hyperbrowserai/mcp) 🆕 | 托管浏览器 + MCP | 云 | 标准 MCP 工具 | — |
| [MultiOn](https://www.multion.ai/) | 托管 | 闭源 | 内置 reasoning + memory | 闭源 |
| [Browserbase](https://www.browserbase.com/) | 基础设施 | 云 | Agent 专用浏览器云 | 闭源 |

---

## 🗣️ 语音与多模态 Agent

- [ElevenLabs](https://elevenlabs.io/)、[Vapi](https://github.com/VapiAI/server-sdk-python)、[Retell AI](https://www.retellai.com/)、[Bland AI](https://www.bland.ai/)
- [LiveKit Agents](https://github.com/livekit/agents)、[Pipecat](https://github.com/pipecat-ai/pipecat)、[Bolna](https://github.com/bolna-ai/bolna)、[Cartesia](https://www.cartesia.ai/)、[Sesame](https://www.sesame.com/)
- 💤 [Vocode](https://github.com/vocodedev/vocode-python)（2024-11 起无更新）

---

## 📱 个人 AI Agent

- [OpenClaw](https://github.com/openclaw/openclaw) 🆕、[Khoj](https://github.com/khoj-ai/khoj)、[Leon](https://github.com/leon-ai/leon)
- [Rabbit R1](https://www.rabbit.tech/)、[Limitless](https://www.limitless.ai/)、[Humane AI Pin](https://humane.com/)
- [Lindy AI](https://www.lindy.ai/) 🆕、[Arahi AI](https://arahi.ai/) 🆕、[MuleRun](https://www.mulerun.ai/) 🆕
- 💤 [01 Light](https://github.com/OpenInterpreter/01)（2024-11 起无更新）

---

## 📱 手机 Agent

- [🇨🇳 Mobile-Agent](https://github.com/X-PLUG/MobileAgent) — 阿里多模态手机控制 Agent 家族（v1→v3 + Mobile-Agent-E / V）
- 💤 [AppAgent](https://github.com/mnotgod96/AppAgent) — 腾讯多模态智能体
- [Apple Intelligence](https://www.apple.com/apple-intelligence/) — iOS / iPadOS / macOS 端侧 Agent 层
- [Samsung Galaxy AI / Bixby 2.0](https://www.samsung.com/global/galaxy/galaxy-ai/) — Galaxy S26 端侧 Gauss
- [Google Gemini for Android](https://gemini.google/) — 全面替换 Google Assistant
- [Microsoft Magma](https://microsoft.github.io/Magma/) — UI / 机器人 / 物理动作多模态基座

---

## 🏢 企业级 Agent 平台

- [Salesforce Agentforce](https://www.salesforce.com/agentforce/)、[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)
- [Gemini Enterprise Agent Platform](https://cloud.google.com/blog/products/ai-machine-learning/introducing-gemini-enterprise-agent-platform) 🆕（2026-04-22 GA）
- [Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents/)、[ServiceNow AI Agents](https://www.servicenow.com/products/ai-agents.html)
- [Moveworks](https://www.moveworks.com/)、[UiPath Agentic Automation](https://www.uipath.com/) 🆕、[Sema4.ai](https://sema4.ai/)

---

## 📊 Agent 评估与可观测性

| 工具 | 自托管 | OTel | 评测 | Prompt 管理 | License |
|------|--------|------|-----|------------|---------|
| [Langfuse](https://github.com/langfuse/langfuse) | ✅ | ✅ | ✅ | ✅ | MIT |
| [Helicone](https://github.com/Helicone/helicone) | ✅ | ✅ | ⚠️ | ✅ | Apache-2.0 |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | ✅ | ✅ | ✅ | ⚠️ | Elastic-2.0 |
| [LangSmith](https://www.langchain.com/langsmith) | ❌ | ✅ | ✅ | ✅ | 闭源 |
| [Braintrust](https://www.braintrust.dev/) | ❌ | ✅ | ✅ | ✅ | 闭源 |
| [DeepEval](https://github.com/confident-ai/deepeval) | ✅ | ⚠️ | ✅ | ❌ | Apache-2.0 |
| [Agenta](https://github.com/agenta-ai/agenta) | ✅ | ✅ | ✅ | ✅ | Apache-2.0 |
| [OpenLLMetry](https://github.com/traceloop/openllmetry) | ✅ | ✅ 原生 | ❌ | ❌ | Apache-2.0 |
| [Patronus AI](https://www.patronus.ai/) 🆕 | ❌ | ⚠️ | ✅ | — | 闭源 |

⚠️ Unverified（需谨慎评估）：[BenchClaw](https://github.com/Agnuxo1/benchclaw)、[PromptEden](https://www.prompteden.com)

---

## 🔬 AI 研究工具

- [vLLM](https://github.com/vllm-project/vllm)、[SGLang](https://github.com/sgl-project/sglang)、[llama.cpp](https://github.com/ggml-org/llama.cpp)
- [Ollama](https://github.com/ollama/ollama)、[LM Studio](https://lmstudio.ai/)、[OpenRouter](https://openrouter.ai/)
- [Unsloth](https://github.com/unslothai/unsloth)、[MLX](https://github.com/ml-explore/mlx)、[Weights & Biases](https://wandb.ai/)、[Label Studio](https://github.com/HumanSignal/label-studio)

---

## 📚 学习资源

### 论文

- [ReAct](https://arxiv.org/abs/2210.03629)、[Toolformer](https://arxiv.org/abs/2302.04761)、[Generative Agents](https://arxiv.org/abs/2304.03442)
- [LLM-based Autonomous Agents Survey](https://arxiv.org/abs/2308.11432)、[The Rise and Potential of LLM Agents](https://arxiv.org/abs/2309.07864)

### 课程与教程

- [Hugging Face Agents Course](https://github.com/huggingface/agents-course) ⭐
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook)、[Anthropic Courses](https://github.com/anthropics/courses)
- [Google Gemini Cookbook](https://github.com/google-gemini/cookbook)
- [DeepLearning.AI 短课](https://www.deeplearning.ai/) — LangGraph、CrewAI、A2A 三门
- [LangChain Academy](https://academy.langchain.com/)、[LLM Agents MOOC (Berkeley)](https://llmagents-learning.org/f24)
- [LLM Course (Maxime Labonne)](https://github.com/mlabonne/llm-course)

---

## 🇨🇳 中国 AI 生态

中文向开发者最熟悉的全套清单（详细见英文版「Chinese AI Ecosystem」一节）：

**Agent 平台**：[Dify](https://github.com/langgenius/dify)、[Lobe Chat](https://github.com/lobehub/lobe-chat)、[Cozeloop](https://github.com/coze-dev/cozeloop)、[AgentScope](https://github.com/modelscope/agentscope)、[Bisheng](https://github.com/dataelement/bisheng)、[MetaGPT](https://github.com/geekan/MetaGPT)

**RAG**：[FastGPT](https://github.com/labring/FastGPT)、[QAnything](https://github.com/netease-youdao/QAnything) 💤、[RAGFlow](https://github.com/infiniflow/ragflow)、[LightRAG](https://github.com/HKUDS/LightRAG)

**个人 / 生产力**：[AppFlowy](https://github.com/AppFlowy-IO/AppFlowy)、[Manus AI](https://manus.im/)、[Coze (扣才)](https://www.coze.cn/)、[通义千问 Agent](https://tongyi.aliyun.com/)、[Doubao](https://www.doubao.com/)

**开发者工具**：[Kilo Code](https://www.kilocode.com/)、[Cherry Studio](https://github.com/CherryHQ/cherry-studio)、[ScienceOne 100](https://english.cas.cn/newsroom/cas-in-media/202604/t20260429_1158251.shtml)

---

## 📝 横向对比表

英文版 [README.md#-compare--side-by-side-tables](README.md#-compare--side-by-side-tables) 提供 5 张完整对比表：

1. **Agent 框架**（开源向，8 个）
2. **沙箱**（运行 Agent 生成代码，5 个）
3. **浏览器 Agent 栈**（6 个）
4. **评估 / 可观测性**（8 个）
5. **编程 Agent 头部选择**（7 个）

中文版正在整理中。先以英文版为准。

---

## 📅 2026 AI 时间线

完整 50+ 条时间线请见 [英文版 README](README.md#-2026-ai-timeline)。本中文版只列重要里程碑：

| 日期 | 事件 |
|------|------|
| **2026-02** | Claude Sonnet 4.6 发布（1M 上下文）、Gemini 3.1 Pro 发布、Cursor 支持 8 个并行 Agent |
| **2026-03** | Microsoft Agent Framework GA 目标、MCP 2026 路线图发布、Sora 关停公告 |
| **2026-04-15** | OpenAI Agents SDK 大更新（原生沙箱、MCP 一等公民） |
| **2026-04-16** | Claude Opus 4.7 发布（SWE-bench Verified 87.6%、`/think xhigh`） |
| **2026-04-20-21** | Kimi K2.6 发布（1T MoE、1000-agent swarm） |
| **2026-04-22** | Gemini Enterprise Agent Platform 发布 |
| **2026-04-23** | GPT-5.5 发布、Hunyuan Hy3 Preview 开源、Claude Managed Memory 公测 |
| **2026-04-24** | DeepSeek V4 Pro / Flash 开源（1.6T MoE，MIT）、Cohere + Aleph Alpha 合并（$20B 估值） |
| **2026-04-30** | OpenAI 发布《构建 Agent 实战指南》 |
| **2026-05-01** | Anthropic Claude Security 公测（Opus 4.7 驱动的代码漏洞扫描） |

---

## 贡献

请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。**反垃圾质量门槛**适用于中英文版本：自我推广批量铺货 PR 一律拒绝。

---

*Made with ❤️ by [Zijian Ni](https://github.com/Zijian-Ni) · 2026 © MIT License*
