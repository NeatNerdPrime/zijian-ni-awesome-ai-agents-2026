<div align="center">

# 🤖 Awesome AI Agents 2026 · 中文版

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/awesome-ai-agents-2026?style=social)](https://github.com/Zijian-Ni/awesome-ai-agents-2026)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Audited](https://img.shields.io/badge/Spam_Audited-2026--05--05-success.svg)](#️-状态图例)
[![English](https://img.shields.io/badge/Lang-English-informational.svg)](README.md)
[![日本語](https://img.shields.io/badge/Lang-日本語-red.svg)](README.ja.md)

**2026 年 AI 模型、Agent 框架、工具、协议与资源精选清单 —— 这是 Agent 真正成为基础设施的一年。**

*覆盖：基础大模型、多模态生成、Agent 协议（MCP / A2A）、编程 Agent、计算机使用、生成式 AI 等。*

### 🏷️ 状态图例

每条目可能携带一个或多个状态标签，便于读者一眼判断成熟度：

- 🆕 **New** — 60 天内加入，效果尚待沉淀
- 📦 **Archived** — 仓库已归档，仅作历史参考，不再更新
- 💤 **Stale** — 6 个月以上无提交，可能仍可用但已不再活跃维护
- ⚠️ **Unverified** — 新提交且第三方使用证据有限（star 少 / 单作者 / 同款 PR 批量铺货）。**仅作可见性收录，不背书**，使用前请自行评估
- 🇨🇳 **Chinese ecosystem** — 中国大陆团队主导或主要面向中文市场的项目

[基础大模型](#-基础大模型-2026) · [多模态](#-多模态与生成式-ai) · [协议](#-agent-协议与标准) · [框架](#️-agent-框架) · [IDE 与构建器](#️-agent-ide-与可视化构建器) · [记忆](#-agent-记忆) · [工具](#-工具与-api-集成) · [沙箱](#-agent-沙箱与计算隔离) · [安全](#️-agent-安全) · [RAG](#-rag-与知识库) · [编程](#-编程-agent) · [Physical AI](#-physical-ai--具身智能) · [仿真](#-agent-仿真与世界模型) · [评测](#-评测与-leaderboard) · [Computer Use](#️-computer-use--桌面-agent) · [浏览器与 Web](#-浏览器与-web-agent) · [语音](#️-语音与多模态-agent) · [个人](#-个人-ai-agent) · [手机](#-手机-agent) · [企业](#-企业级-agent-平台) · [评估](#-agent-评估与可观测性) · [研究工具](#-ai-研究工具) · [学习](#-学习资源) · [中国生态](#-中国-ai-生态) · [对比](#-横向对比表) · [2026 看点](#-2026-年值得关注的-agent-项目) · [时间线](#-2026-ai-时间线)

</div>

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
- [🌟 2026 年值得关注的 Agent 项目](#-2026-年值得关注的-agent-项目)
- [📅 2026 AI 时间线](#-2026-ai-时间线)

---

## 🧠 基础大模型 2026

*为整个 AI 生态提供动力的大语言模型，按厂商组织。20+ 家厂商共 65+ 个模型。*

### OpenAI

- [GPT-5.5](https://openai.com/index/gpt-5-5-system-card/) - 🆕 **2026-04-23 发布**（代号 "Spud"）。OpenAI 面向 Agent 任务的新一代旗舰：编程、在线研究、数据分析、自主工具调用。推理稳定性与长任务执行力大幅提升。ChatGPT Plus / Pro / Business / Enterprise 可用。
- [GPT-5.5 Pro](https://openai.com/index/gpt-5-5-system-card/) - 🆕 2026-04-23。并行测试期算力变体，更高准确率。Pro / Business / Enterprise。
- [GPT-5.5-Cyber](https://openai.com/index/trusted-access-for-cyber/) - 🆕 **2026-04-30**。GPT-5.5 的网络安全特化版本，通过 OpenAI Trusted Access for Cyber (TAC) 计划仅向防御者、政府、关键基础设施运营方、安全厂商开放，不对公众发布。
- [GPT-5.4](https://openai.com/) - 2026-03 发布。1M token 上下文，编程、Computer Use、工具检索均强。BenchLM 94，SWE-bench Verified 77.2%，OSWorld 75%（超过人类基线）。
- [GPT-5.4 Pro](https://openai.com/) - GPT-5.4 的高准确率变体。BenchLM 92。
- [GPT-5.3](https://openai.com/) - 2026 年初。包括 GPT-5.3 Instant（对话）和 GPT-5.3-Codex（编程）。
- [GPT-5.2](https://openai.com/) - 2025-12 发布。SOTA 推理 + 长上下文 + 视觉。
- [GPT-5](https://openai.com/index/introducing-gpt-5/) - 2025-08 发布，ChatGPT 默认模型，替代 GPT-4o。多模态 + gpt-5 / mini / nano 三档变体。
- [GPT-4o](https://openai.com/index/hello-gpt-4o/) - Omni 模型，原生支持文本/视觉/音频。2026-02 从 ChatGPT 下线，API 仍可用。
- [o3 / o4-mini](https://openai.com/index/introducing-o3-and-o4-mini/) - 思维链推理模型。2025-04 发布。
- [Codex CLI](https://github.com/openai/codex) - OpenAI 出品的开源终端编程 Agent。![GitHub stars](https://img.shields.io/github/stars/openai/codex?style=flat-square)

### Anthropic

- [Claude Opus 4.7](https://www.anthropic.com/news/claude-opus-4-7) - 🆕 2026-04-16 发布。SWE-bench Verified 87.6% 的工程能力，视觉增强、主动代码验证。支持 `/think xhigh` 推理档位。1M token 上下文。
- [Claude Opus 4.6](https://www.anthropic.com/) - 2026-02 发布。1M token 上下文，14.5 小时任务执行。LMArena 对话榜首。
- [Claude Sonnet 4.6](https://www.anthropic.com/news/claude-sonnet-4-6) - 2026-02 发布。前沿编程与 Agent 表现，1M token 上下文。
- [Claude Mythos Preview](https://www.anthropic.com/) - 🆕 2026-04 受邀研究预览。BenchLM 99（榜首），SWE-bench Verified 93.9%。Project Glasswing 合作伙伴专属。
- [Claude Opus 4](https://www.anthropic.com/news/claude-4) - 2025-05 发布。
- [Claude Sonnet 4](https://www.anthropic.com/news/claude-4) - 2025-05 发布。
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic 出品、运行在终端里的 Agent 化编程工具。Opus 4.7 + `/think xhigh`。
- [Claude Security](https://www.anthropic.com/) - 🆕 **2026-05-01** 公测。Opus 4.7 驱动的企业级代码漏洞扫描器：扫整个代码库，生成有置信度评分、严重程度、复现步骤、修复建议的补丁。Enterprise 用户在 [claude.ai/security](https://claude.ai/security) 使用。

### Google DeepMind

- [Gemini 3.1 Pro](https://deepmind.google/technologies/gemini/) - 2026-02 发布。BenchLM 94，GPQA Diamond 94.3%（世界纪录），ARC-AGI 2 77.1%。Google 最强模型，旗舰定价 `$2/1M tokens`。
- [Gemini 3.1 Flash Live](https://deepmind.google/technologies/gemini/) - 🆕 2026-04。语音助手与交互式 Agent 的实时多模态流式接口，低延迟长上下文。
- [Gemini 3.1 Flash / Flash Lite](https://deepmind.google/technologies/gemini/) - 高吞吐应用的高性价比选择。
- [Gemini 4 (Open)](https://deepmind.google/technologies/gemini/) - 🆕 2026-04 发布。开源家族：2B / 4B / 26B / 31B 变体。科学推理与文档理解强，本地部署友好。
- [Gemini 2.5 Pro / Flash](https://deepmind.google/technologies/gemini/) - 2025-06 GA。Thinking 模型，1M 上下文。
- [Gemma 4 31B](https://github.com/google-deepmind/gemma) - 🆕 2026-04。GPQA Diamond 84.3%。端侧推理首选开源权重之一。![GitHub stars](https://img.shields.io/github/stars/google-deepmind/gemma?style=flat-square)
- [Gemma 3](https://github.com/google-deepmind/gemma) - 上一代开源家族。
- [Gemini Robotics ER-1.6](https://deepmind.google/) - 🆕 2026-04-14。机器人 AI 模型，空间与物理推理增强。Agile Robotics 实地部署。

### Meta

- [Muse Spark](https://ai.meta.com/blog/introducing-muse-spark-msl/) - 🆕 **2026-04-09**。Meta Superintelligence Labs (MSL) 首个模型。原生多模态推理，驱动 Meta AI 应用、智能眼镜，以及 Facebook / Instagram / WhatsApp / Messenger 中的功能。
- [Llama 4 Scout](https://llama.meta.com/) - 109B 总参（17B 激活），16 专家 MoE，10M token 上下文，多模态。单 H100 可跑。
- [Llama 4 Maverick](https://llama.meta.com/) - 400B 总参（17B 激活），128 专家，1M 上下文。多模态超过 GPT-4o。
- [Llama 4 Behemoth](https://llama.meta.com/) - 2T 总参（288B 激活）。Meta 最强模型，对标顶级闭源。
- [Llama 3.3 70B](https://llama.meta.com/) - 强指令跟随，Llama Community License。

### Mistral AI

- [Mistral Large 3](https://mistral.ai/news/mistral-3) - 675B 总 / 41B 激活 MoE，256K 上下文。多模态旗舰开源。2025-12 发布。
- [Mistral Medium 3.1](https://mistral.ai/) - 企业级前沿密集模型。多模态，128K，支持 80+ 编程语言。2025-08 发布。
- [Mistral Small 4](https://mistral.ai/news/mistral-small-4) - 🆕 2026-03。119B 总 / 6B 激活。融合推理 + 多模态 + 编程的混合模型。
- [Magistral 1.2](https://mistral.ai/) - 🆕 2026 推理家族。透明、多语言推理。
- [Devstral 2](https://mistral.ai/) - 🆕 2026 Agent 编程模型。当前最佳开源编程 Agent 模型。
- [Codestral](https://mistral.ai/news/codestral) - 22B 编程模型，80+ 语言，32K 上下文。2024-05 发布。
- [Pixtral Large](https://mistral.ai/) - 124B 多模态 + 1B 视觉编码器，128K 上下文，支持 30+ 高分辨率图像。
- [Ministral 3B/8B/14B](https://mistral.ai/) - 端侧紧凑模型。
- [Mistral Forge](https://mistral.ai/) - 🆕 2026-03 自定义 LLM 训练平台。

### DeepSeek 🇨🇳

- [DeepSeek-V4-Pro](https://api-docs.deepseek.com/news/news260424) - 🆕 **2026-04-24**。1.6T 总 / 49B 激活 MoE，1M 上下文。MIT。Agent、世界知识、推理领域开源标杆。
- [DeepSeek-V4-Flash](https://api-docs.deepseek.com/news/news260424) - 🆕 2026-04-24。284B 总 / 13B 激活 MoE，1M 上下文。MIT。性价比层。
- [DeepSeek-V3.2](https://www.deepseek.com/) - 2025-12 发布。671B MoE，V3.2 Speciale 推理增强。
- [DeepSeek-R2](https://www.deepseek.com/) - 2026 推理模型。R1 后继，对标 GPT-5、Gemini 3 Pro。
- [DeepSeek-R1](https://www.deepseek.com/) - 2025-01 发布的思维链推理模型。
- [DeepSeek-Coder-V2](https://github.com/deepseek-ai/DeepSeek-Coder-V2) - 编程模型，对标 GPT-4。![GitHub stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-Coder-V2?style=flat-square)

### Alibaba (Qwen) 🇨🇳

- [Qwen3.6-27B](https://qwen.ai/blog?id=qwen3.6-27b) - 🆕 **2026-04-22**。27B 密集多模态。开源。Agent 编程 + 思维上下文保持。
- [Qwen3.6-Max-Preview](https://qwen.ai/) - 🆕 **2026-04-18**。闭源前沿预览。1M 上下文，中文模型编程榜顶尖。
- [Qwen3.6-35B-A3B](https://qwen.ai/blog?id=qwen3.6-35b-a3b) - 🆕 **2026-04-15**。MoE 35B 总 / 3B 激活。Apache 2.0。稳定性与实用性增强。
- [Qwen3.6-Plus](https://qwen.ai/) - 🆕 **2026-04-02**。闭源旗舰。token 性价比高，长上下文 + 工具调用 + Agent 表现强。
- [Tianma (天马) AI](https://www.alibabacloud.com/) - 🆕 **2026-04-27** 公测。阿里图生视频模型。角色一致性强，运动质量高。
- [Qwen3.5 Max Pro](https://qwen.ai/) - 2026-04。高性能旗舰。
- [Qwen3.5 Omni Plus](https://qwen.ai/) - 2026-04。统一文本 + 图像输入的全模态基座。
- [Qwen3-Max-Thinking](https://qwen.ai/) - 阿里最强思维模型。1T+ 参数。
- [Qwen3.5-Omni](https://qwen.ai/) - 2026-03。完全全模态：文/视/听/动。113 种语言识别，256K 上下文。
- [Qwen3-Coder-Next](https://qwen.ai/) - 2026-02。开源编程 Agent 模型，MoE 80B 总 / 3B 激活。
- [Qwen3 235B-A22B](https://qwen.ai/) - 双模式推理 MoE。数学、代码、常识强。
- [Qwen2.5 Coder 32B](https://github.com/QwenLM/Qwen2.5-Coder) - 顶级开源编程模型。![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen2.5-Coder?style=flat-square)

### xAI (Grok)

- [Grok 4.3 Beta](https://x.ai/) - 🆕 2026-04。最新迭代，推理与编程基准提升，详见 [`2026.4` benchmark snapshot](https://benchlm.ai/)。
- [Grok 4.20](https://x.ai/) - 2026-02。多 Agent 系统（Heavy 模式 4 标准 + 16 专家 Agent），2M 上下文。
- [Grok 4 / 4 Heavy](https://x.ai/) - 2025-07 发布。3T 参数。
- [Grok 3 / 3 Mini](https://x.ai/) - 2025-02。首批 "Think Mode" 推理模型。

### Microsoft (Phi)

- [Phi-4-reasoning-vision-15B](https://azure.microsoft.com/en-us/products/phi) - 🆕 2026-03。15B 多模态，选择性思维链推理。端侧友好。
- [Phi-4](https://azure.microsoft.com/en-us/products/phi) - 14B SLM，推理水平媲美更大模型。MIT。
- [Phi-4-mini](https://azure.microsoft.com/en-us/products/phi) - 3.8B 密集，128K 上下文。推理 / 数学 / 编程 / 函数调用都强。
- [Phi-4-multimodal](https://azure.microsoft.com/en-us/products/phi) - 5.6B 首个多模态 Phi（语音 + 视觉 + 文本）。

### Cohere

- [Command A](https://cohere.com/) - 🆕 2026-04 发布。111B 开源权重，256K 上下文。Agent / 多语言 / 编程聚焦。
- [Command R+](https://cohere.com/) - 企业级 RAG 模型，128K 上下文，10 种语言，带引用 grounded generation。
- [Command R](https://cohere.com/) - 经济型 RAG 模型。

### Baidu (ERNIE / 文心) 🇨🇳

- [ERNIE 5.0](https://yiyan.baidu.com/) - 🆕 2026-01 发布。2.4T MoE（每次激活 <3%）。原生全模态。LMArena 中文模型第一。
- [ERNIE 4.5](https://yiyan.baidu.com/) - 2025 多模态前作。中文与推理强。

### Zhipu AI / Z.ai (GLM) 🇨🇳

- [GLM-5.1](https://z.ai/blog/glm-5.1) - 🆕 **2026-04-07**。744B MoE / 40B 激活，200K 上下文。MIT。SWE-Bench Pro 第一。**完全在华为昇腾上训练，不依赖 NVIDIA**。
- [GLM-5 Reasoning](https://z.ai/) - 🆕 2026-04。BenchLM 85 —— **开源最高分**。SWE-Bench Pro 超过 GPT-5.4 与 Claude Opus 4.6。
- [GLM-5V-Turbo](https://z.ai/) - 🆕 2026-04。原生多模态 Agent —— 视觉、视频片段、文本输入。性价比平衡。
- [GLM-5](https://z.ai/) - 2026-02 发布。744B 参数，Agent 能力前沿。MIT。
- [GLM-4.7](https://z.ai/) - 2025 末发布。SWE-Bench 持平 Claude Opus 4。

### MiniMax 🇨🇳

- [MiniMax-M2.7 (开源权重)](https://www.minimax.io/) - 🆕 2026-04。1M+ 超长上下文。编程与 Agent 任务顶级表现。
- [MiniMax-M1-80k](https://www.minimax.io/) - 开源混合注意力推理模型。456B 参数，1M token 上下文。
- [Hailuo AI (视频)](https://hailuoai.video/) - 文生 / 图生视频，AI 主播 + 配音 + 角色一致性。
- [Kilo Code 集成](https://www.minimax.io/) - 🆕 MiniMax 为 Kilo Code（新 AI 编程编辑器）默认模型。

### Moonshot AI (Kimi) 🇨🇳

- [Kimi K2.6](https://kimi.ai/) - 🆕 **2026-04-20~21**。1T MoE / 32B 激活，256K 上下文。编程增强、长任务执行、**最大 1000 个 Agent 协作集群**。支持 `thinking.keep="all"` 持久推理。OpenClaw v2026.4.20+ 默认模型。
- [Kimi K2.5](https://kimi.ai/) - 2026-01 至 02。1T 总 / 32B 激活 MoE。原生多模态，最多 100 个并行子 Agent。开源。⚠️ **2026-05-25 停止支持**，请迁移到 K2.6。
- [Kimi Code](https://kimi.ai/) - 基于 K2.5/K2.6 的高级编程层，面向终端工作流。

### ByteDance (Doubao / 豆包) 🇨🇳

- [Doubao-Seed-2.0 Pro](https://seed.bytedance.com/) - 🆕 2026-02 发布。前沿推理与复杂 Agent。和 GPT-5.2 同级，成本约低 90%。
- [Doubao-Seed-2.0 Lite](https://seed.bytedance.com/) - 🆕 通用生产负载。性能效率均衡。
- [Doubao-Seed-2.0 Code](https://seed.bytedance.com/) - 🆕 软件开发：代码生成、调试、评审。
- [BAGEL](https://github.com/bytedance-seed/BAGEL) - 🆕 字节开源多模态模型，文图视频统一理解 + 生成。

### Amazon (Nova)

- [Nova 2 Pro](https://aws.amazon.com/nova/) - 🆕 Amazon 最强推理模型。文 / 图 / 视频 / 语音输入。Agent 编程与长程规划。
- [Nova 2 Lite](https://aws.amazon.com/nova/) - 🆕 1M token 上下文 + 可调 "thinking effort"。
- [Nova 2 Sonic](https://aws.amazon.com/nova/) - 🆕 实时语音对语音模型。1M 上下文，多语言。
- [Nova Act](https://aws.amazon.com/nova/) - 🆕 浏览器 Web 任务 Agent 服务（Nova 2 Lite 驱动）。
- [Nova Forge](https://aws.amazon.com/nova/) - 🆕 自定义 Nova 训练服务。

### NVIDIA (Nemotron)

- [Nemotron 3 Ultra](https://developer.nvidia.com/nemotron) - 🆕 2026-03（GTC）。前沿推理，Blackwell 上 5 倍吞吐。
- [Nemotron 3 Super](https://developer.nvidia.com/nemotron) - 🆕 2026-03。120B 总 / 12B 激活。1M 上下文。
- [Nemotron 3 Nano](https://developer.nvidia.com/nemotron) - 经济型 Transformer-Mamba 混合 MoE。
- [Nemotron 3 Nano Omni](https://blogs.nvidia.com/blog/nemotron-3-nano-omni-multimodal-ai-agents/) - 🆕 **2026-04-28**。30B-A3B 混合 MoE。原生多模态。同类开源 omni 模型 9 倍吞吐。霸榜 6 项排行（MMlongbench-Doc / OCRBenchV2 / WorldSense / DailyOmni / VoiceBench）。

### Tencent (Hunyuan) 🇨🇳

- [Hunyuan Hy3 Preview](https://hy.tencent.com/research/hy3) - 🆕 **2026-04-23**。295B 总 / 21B 激活 MoE，256K 上下文。GitHub / Hugging Face / ModelScope / GitCode 同步开源。"快慢思维融合" 架构，推理效率提升 40%。原生支持 vLLM 与 SGLang。腾讯元宝 / CodeBuddy / QQ / 腾讯文档已集成。OpenRouter 免费预览中。![GitHub stars](https://img.shields.io/github/stars/Tencent-Hunyuan/Hunyuan-A13B?style=flat-square)

### Apple

- [Apple Foundation Models (AFM)](https://machinelearning.apple.com/research/introducing-apple-foundation-models) - 端侧（~3B）+ 服务器版本，Apple Intelligence 内核。隐私优先，离线可用。
- [OpenELM](https://machinelearning.apple.com/research/openelm) - 开源高效语言模型（270M~3B），Apple Silicon 端侧。

### Samsung

- [Samsung Gauss 2.3](https://www.samsung.com/) - 🆕 Galaxy S26 端侧 AI。Gauss 2.3 Think + Gauss O Flash 双变体。Agent 能力。

### Inflection AI

- [Inflection 2.5 / Pi](https://inflection.ai/) - 偏共情对话的 AI，主打情绪感知与人本交互。

### 01.AI 🇨🇳

- [Yi-Lightning](https://www.01.ai/) - MoE，RTX 4090 上 200+ tokens/s。中英双语强，Apache 2.0。2024-10 发布。

### 中国科学院 🇨🇳

- [ScienceOne 100 / 磐石100](https://english.cas.cn/newsroom/cas-in-media/202604/t20260429_1158251.shtml) - 🆕 **2026-04-28~29**。中科院科研 AI 系统。"磐石" 基础模型 + 文献罗盘 + 创新评估引擎 + 2000+ 工具 Agent 工厂。覆盖数学 / 物理 / 生物 / 材料 / 天文 / 航天 / 地球科学。50+ 中科院研究所、100+ 科研场景使用。

---

## 🎨 多模态与生成式 AI

*生成与编辑图像、视频、音频、音乐的工具与模型。*

### 图像生成

- [ChatGPT Images 2.0](https://openai.com/) - 🆕 2026-04。免费层。细节、文字理解、迭代编辑增强。
- [gpt-image-2](https://openai.com/) - 🆕 OpenAI 最新图像 API。支持 2K/4K 提示。OpenClaw v2026.4.21 默认。
- [DALL·E 3](https://openai.com/dall-e-3) - 集成在 ChatGPT 中迭代生成。
- [Midjourney V7](https://www.midjourney.com/) - 仍是艺术风格生成第一梯队。
- [Stable Diffusion 3.5](https://stability.ai/) - 开源图像生成，连贯性与提示跟随增强。
- [Flux](https://github.com/black-forest-labs/flux) - 💤 **Stale**（2025-07 起无更新）。Black Forest Labs 开源模型。![GitHub stars](https://img.shields.io/github/stars/black-forest-labs/flux?style=flat-square)
- [Ideogram 3.0](https://ideogram.ai/) - 文字渲染与设计向特别强。
- [Gemini 3 Pro Image](https://deepmind.google/technologies/gemini/) - Gemini 内原生图像生成。
- [Recraft V3](https://www.recraft.ai/) - 设计师向专业图像生成。
- [Seedance 2.0](https://seed.bytedance.com/) - 🇨🇳 🆕 字节下一代图像 / 动画生成 API。

### 视频生成

- [Kling VIDEO 3.0](https://kling.ai/) - 🇨🇳 🆕 快手出品。真人动作 + 嘴型 + 音画同步，最长 15 秒。
- [Hailuo AI](https://hailuoai.video/) - 🇨🇳 🆕 MiniMax 出品。文生 / 图生视频 + AI 主播 + 配音 + 角色一致性。
- [Veo 2](https://deepmind.google/technologies/veo/) - 🆕 Google DeepMind 高保真视频生成。
- [Runway Gen-4](https://runwayml.com/) - 🆕 专业视频生成与编辑，角色风格一致。
- [Pika 2.0](https://pika.art/) - 🆕 创意短视频，场景与特效控制。
- [LTX Studio](https://ltx.studio/) - 🆕 AI 电影化视频创作平台。
- [Tianma (天马) AI](https://www.alibabacloud.com/) - 🇨🇳 🆕 **2026-04-27** 公测。阿里图生视频。
- [Sora](https://openai.com/sora/) - ⚠️ *2026-04 关停*。OpenAI 文生视频模型，因成本与战略关停。

### 音频与音乐

- [ElevenLabs](https://elevenlabs.io/) - AI 语音合成 + 克隆 + 对话 AI 头部。
- [Suno V4](https://suno.com/) - 🆕 文本到音乐，高保真人声 + 配器。
- [Udio](https://www.udio.com/) - 🆕 商用级音乐生成。
- [OpenAI Audio Models](https://openai.com/) - GPT-4o 内的原生音频理解 + 生成。
- [Stability Audio](https://stability.ai/) - 开源音频音乐生成。
- [Bark](https://github.com/suno-ai/bark) - 💤 **Stale**（2024-08 起无更新）。开源文本到音频。![GitHub stars](https://img.shields.io/github/stars/suno-ai/bark?style=flat-square)

---

## 🔗 Agent 协议与标准

*让 Agent 跨工具、跨框架互联互通的开放标准。*

### Model Context Protocol (MCP)

- [MCP Specification](https://modelcontextprotocol.io/) - 🆕 "AI 的 USB-C" —— Anthropic 主推、用于让 LLM 接入工具与数据源的开放协议。2025-12 捐赠给 Linux Foundation 旗下 Agentic AI Foundation。
- [MCP Servers](https://github.com/modelcontextprotocol/servers) - 官方参考 MCP 服务实现。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat-square)
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - 官方 TypeScript SDK。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat-square)
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - 官方 Python SDK。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat-square)
- [mcp.so](https://mcp.so/) - 🆕 社区 MCP 服务目录。
- [mcp-gateway](https://github.com/Zijian-Ni/mcp-gateway) - MCP 网关，统一路由 / 认证 / 限流。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/mcp-gateway?style=flat-square)

### Agent-to-Agent Protocol (A2A)

- [A2A Protocol](https://github.com/google/A2A) - 🆕 Google 主导的 Agent 间通信开放标准。让不同框架的 Agent 互相发现、委派、协作。Linux Foundation 治理，2026 年已有 150+ 合作组织。![GitHub stars](https://img.shields.io/github/stars/google/A2A?style=flat-square)
- [A2A Course (DeepLearning.AI)](https://www.deeplearning.ai/short-courses/a2a-the-agent2agent-protocol/) - 🆕 免费课程：用 A2A 构建多 Agent 系统。

### 其他标准

- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - 🆕 [2026-04-15 大更新](https://openai.com/index/the-next-evolution-of-the-agents-sdk/)：原生沙箱执行、MCP 一等公民、子 Agent / handoff 模式、Codex 风格文件系统工具，生产级多 Agent。![GitHub stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat-square)
- [Agentic AI Foundation](https://www.linuxfoundation.org/) - 🆕 Linux Foundation 治理基金，由 Anthropic、Block、OpenAI 共同发起。

---

## 🏗️ Agent 框架

*用来构建自主 AI Agent 的框架与库。*

- [LangChain](https://github.com/langchain-ai/langchain) - 上下文感知推理应用的基础框架。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)
- [LangGraph](https://github.com/langchain-ai/langgraph) - 把 Agent 建模为有状态、多 actor 协作的图。v0.3.19（2026-04-27）：预制 Agent 拆出 `langgraph-prebuilt` —— Supervisor / Swarm / LangMem / Trustcall。Agent 工作流的生产级标准。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square)
- [CrewAI](https://github.com/crewAIInc/crewAI) - 角色扮演式 Agent 团队编排。![GitHub stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat-square)
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/) - 🆕 AutoGen + Semantic Kernel 合并的统一框架。多 Agent + 企业能力。2026 Q1 GA。
- [AutoGen](https://github.com/microsoft/autogen) - 微软多 Agent 对话框架（已并入 Microsoft Agent Framework）。![GitHub stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat-square)
- [Google Agent Development Kit (ADK)](https://github.com/google/adk-python) - 🆕 与 Gemini + Vertex AI 深度集成的模块化框架。层级 Agent 组合。![GitHub stars](https://img.shields.io/github/stars/google/adk-python?style=flat-square)
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - 🆕 [2026-04-15 升级](https://openai.com/index/the-next-evolution-of-the-agents-sdk/) —— 原生沙箱、MCP、子 Agent handoff、Codex 文件操作。生产级多 Agent。![GitHub stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat-square)
- [MetaGPT](https://github.com/geekan/MetaGPT) - 🇨🇳 给 LLM 分配 SOP 软件团队角色（PM / 架构师 / 工程师）。![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat-square)
- [Mastra](https://github.com/mastra-ai/mastra) - 🆕 TypeScript 优先的 Agent 框架，工作流驱动 + 内置可观测性。![GitHub stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=flat-square)
- [AgentGPT](https://github.com/reworkd/AgentGPT) - 📦 **Archived**（2025-04）。浏览器中部署 Agent。第一波代表项目，仅作历史参考。![GitHub stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=flat-square)
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - 用 LLM 创建、排序、执行任务的 AI 任务管理。![GitHub stars](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=flat-square)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - 💤 **Stale**（2025-01 起无更新）。开源自主 Agent 框架。![GitHub stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=flat-square)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - 把 LLM 嵌入应用。C# / Python / Java。![GitHub stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=flat-square)
- [Phidata (Agno)](https://github.com/phidatahq/phidata) - 多模态 Agent + 记忆 + 知识 + 工具 + 推理。![GitHub stars](https://img.shields.io/github/stars/phidatahq/phidata?style=flat-square)
- [DSPy](https://github.com/stanfordnlp/dspy) - "编程而不是写 prompt" 的语言模型框架。![GitHub stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square)
- [OpenClaw](https://github.com/openclaw/openclaw) - 🆕 个人 AI Agent 平台：技能、记忆、多渠道消息、Dreaming（三阶段记忆巩固）、Canvas / A2UI、ACP 编程 harness 集成、Standing Orders。v2026.4.21 支持 Opus 4.7、Kimi K2.6、`/think xhigh`。据称 2026-04 GitHub star 数超过 Linux。![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat-square)
- [Dify](https://github.com/langgenius/dify) - 🇨🇳 开源 LLM 应用开发平台 + 可视化 Agent 构建。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Haystack Agents](https://github.com/deepset-ai/haystack) - 端到端 LLM 框架，Agent 流水线。![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square)
- [Vellum AI](https://www.vellum.ai/) - 🆕 闭源 SaaS 生产级 Agent 框架：Prompt 构建 / 评测 / 版本 / 可观测性一体。
- [FastAgency](https://github.com/airtai/fastagency) - 🆕 高速推理 + 生产规模化框架。![GitHub stars](https://img.shields.io/github/stars/airtai/fastagency?style=flat-square)
- [Rasa](https://github.com/RasaHQ/rasa) - 强意图识别 + 对话管理的开源对话 AI。![GitHub stars](https://img.shields.io/github/stars/RasaHQ/rasa?style=flat-square)
- [Lindy](https://www.lindy.ai/) - 🆕 商务用户向无代码 Agent，可视化工作流。
- [Octomind](https://github.com/muvon/octomind) - 🆕 Rust 开源 AI Agent 运行时。多模型（13+），社区贡献的领域 Agent（开发 / 医疗 / 法律 / DevOps），支持 MCP 运行时自扩展。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/muvon/octomind?style=flat-square)
- [Microsoft AI Agent Governance Toolkit](https://www.helpnetsecurity.com/2026/04/03/microsoft-ai-agent-governance-toolkit/) - 🆕 **2026-04-03**。开源治理工具包，把运行时安全策略以策略即代码方式应用到 LangChain / AutoGen 等框架。

---

## 🛠️ Agent IDE 与可视化构建器

*用来设计、调试、上线 Agent 工作流的可视化（或低代码）环境。*

- [LangGraph Studio](https://www.langchain.com/langgraph) - LangGraph 的可视化调试器：步进状态、回放回合、中途改写消息。
- [Dify](https://github.com/langgenius/dify) - 🇨🇳 拖拽式 Agent 工作流构建。生产级使用最广。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Agenta](https://github.com/agenta-ai/agenta) - 🆕 一体化 LLMOps：prompt playground + 管理 + 评测 + 可观测性。![GitHub stars](https://img.shields.io/github/stars/agenta-ai/agenta?style=flat-square)
- [Vellum AI](https://www.vellum.ai/) - 闭源 SaaS。
- [Cozeloop](https://github.com/coze-dev/cozeloop) - 🇨🇳 🆕 字节 Coze 团队开源的 Agent 优化平台。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/coze-dev/cozeloop?style=flat-square)
- [Restack](https://www.restack.io/) - 持久化 Agent 运行时 + 可视化编辑（Temporal 风格 replay）。开源示例：[restackio/examples-python](https://github.com/restackio/examples-python)。
- [Bisheng](https://github.com/dataelement/bisheng) - 🇨🇳 企业级开源 LLM DevOps：工作流 / RAG / Agent / 微调 / 数据集 / 评测 / 可观测性。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/dataelement/bisheng?style=flat-square)
- [n8n](https://github.com/n8n-io/n8n) - 通用工作流自动化，2026 年常被当作 Agent 画布用。400+ 集成 + 原生 AI 节点。Fair-code。![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat-square)

---

## 🧠 Agent 记忆

*让 Agent 拥有持久记忆与上下文管理的系统。*

- [Letta (MemGPT)](https://github.com/letta-ai/letta) - 长期记忆 + 自定义工具的 LLM 服务。![GitHub stars](https://img.shields.io/github/stars/letta-ai/letta?style=flat-square)
- [Mem0](https://github.com/mem0ai/mem0) - LLM 应用的自我提升记忆层。![GitHub stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square)
- [Zep](https://github.com/getzep/zep) - AI 助理与 Agent 的长期记忆。![GitHub stars](https://img.shields.io/github/stars/getzep/zep?style=flat-square)
- [agent-memory](https://github.com/Zijian-Ni/agent-memory) - 跨会话上下文持久化的轻量 Agent 记忆框架。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/agent-memory?style=flat-square)
- [LangMem](https://github.com/langchain-ai/langmem) - LangChain Agent 的长期记忆库。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langmem?style=flat-square)
- [Motorhead](https://github.com/getmetal/motorhead) - 💤 **Stale**（2025-07 起无更新）。LLM 的记忆 + 上下文管理服务。![GitHub stars](https://img.shields.io/github/stars/getmetal/motorhead?style=flat-square)
- [ChromaDB](https://github.com/chroma-core/chroma) - AI 原生开源向量数据库。![GitHub stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square)
- [Cognee](https://github.com/topoteretes/cognee) - 用图 + LLM + 向量检索得到确定性输出。![GitHub stars](https://img.shields.io/github/stars/topoteretes/cognee?style=flat-square)
- [LangGraph Memory](https://github.com/langchain-ai/langgraph) - 🆕 LangGraph 内置的持久化与 checkpoint。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square)
- [Graphiti](https://github.com/getzep/graphiti) - 🆕 时序感知的知识图记忆。![GitHub stars](https://img.shields.io/github/stars/getzep/graphiti?style=flat-square)
- [Claude Managed Agents Memory](https://platform.claude.com/docs/en/release-notes/overview) - 🆕 **2026-04-23** 公测。把读写记忆挂载到 Agent 文件系统，实现跨会话学习。

---

## 🔌 工具与 API 集成

*让 Agent 接入外部服务与 API 的协议与工具。*

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol/servers) - 工具调用的事实标准。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat-square)
- [mcp-gateway](https://github.com/Zijian-Ni/mcp-gateway) - MCP 网关。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/mcp-gateway?style=flat-square)
- [Composio](https://github.com/ComposioHQ/composio) - 150+ 工具 + 托管认证一体化 Agent 集成平台。![GitHub stars](https://img.shields.io/github/stars/ComposioHQ/composio?style=flat-square)
- [Toolhouse](https://toolhouse.ai/) - AI 工具云：存储、管理、执行工具。
- [LangChain Tools](https://github.com/langchain-ai/langchain) - LangChain 生态广泛的工具集成。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)
- [Arcade AI](https://github.com/ArcadeAI/arcade-ai) - AI Agent 工具调用平台。![GitHub stars](https://img.shields.io/github/stars/ArcadeAI/arcade-ai?style=flat-square)
- [E2B](https://github.com/e2b-dev/e2b) - AI Agent 的开源云沙箱。![GitHub stars](https://img.shields.io/github/stars/e2b-dev/e2b?style=flat-square)
- [Browser Use](https://github.com/browser-use/browser-use) - 让 AI Agent 操控浏览器。![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square)
- [Firecrawl](https://github.com/mendableai/firecrawl) - 🆕 把网站变成 LLM-ready 数据。![GitHub stars](https://img.shields.io/github/stars/mendableai/firecrawl?style=flat-square)
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - 🆕 LLM 友好的开源爬虫。![GitHub stars](https://img.shields.io/github/stars/unclecode/crawl4ai?style=flat-square)
- [Stagehand](https://github.com/browserbase/stagehand) - 🆕 Browserbase 出品的 AI 浏览器自动化。![GitHub stars](https://img.shields.io/github/stars/browserbase/stagehand?style=flat-square)
- [AgentQL](https://www.agentql.com/) - 🆕 用语义化查询语言操控网页。
- [StackOne](https://www.stackone.com/) - 🆕 HR / CRM / ATS 统一 API。
- [The Colony](https://thecolony.cc) - ⚠️ **Unverified**。自称 Agent 间社交网络 + REST API + Python / TS / Go SDK + MCP server。组织与 SDK 仓库均 <30 天，0~2 star，单维护者；同款 PR 投了 15+ 个 awesome 列表。**仅作可见性收录**，使用前请自行评估。![GitHub stars](https://img.shields.io/github/stars/TheColonyCC/colony-sdk-python?style=flat-square)

---

## 🧪 Agent 沙箱与计算隔离

*让 Agent 安全执行生成代码 / shell 命令的隔离运行时。一旦让 Agent 自由活动，这是必备基础设施。*

- [E2B](https://github.com/e2b-dev/E2B) - AI 生成代码的开源云沙箱。OpenAI Agents SDK 默认执行层。![GitHub stars](https://img.shields.io/github/stars/e2b-dev/E2B?style=flat-square)
- [Daytona](https://github.com/daytonaio/daytona) - 🆕 弹性、安全的 AI 生成代码运行基础设施。每个 Agent 任务一个隔离的开发环境。AGPL-3.0。![GitHub stars](https://img.shields.io/github/stars/daytonaio/daytona?style=flat-square)
- [Modal](https://modal.com/) - 流行的 Agent 计算 + GPU 任务 + Python 沙箱 Serverless 平台。`modal-client` 是官方 SDK。![GitHub stars](https://img.shields.io/github/stars/modal-labs/modal-client?style=flat-square)
- [Microsandbox](https://github.com/superradcompany/microsandbox) - 🆕 本地、可编程的 microVM 沙箱。隐私优先，本机执行，不依赖云。![GitHub stars](https://img.shields.io/github/stars/superradcompany/microsandbox?style=flat-square)
- [SandboxFusion](https://github.com/bytedance/SandboxFusion) - 🇨🇳 字节多语言代码执行沙箱，面向 Agent / 模型评测流水线。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/bytedance/SandboxFusion?style=flat-square)
- [Northflank](https://northflank.com/) - 通用容器 PaaS，常被用作 Agent 运行时（每任务临时环境 + GPU 池）。
- [Firecracker](https://github.com/firecracker-microvm/firecracker) - E2B / Daytona / 多数 Agent 沙箱底层的 microVM 内核。自建沙箱时是基础原语。![GitHub stars](https://img.shields.io/github/stars/firecracker-microvm/firecracker?style=flat-square)

---

## 🛡️ Agent 安全

*抵御 prompt 注入、数据泄漏、滥用的工具与框架。*

- [prompt-firewall](https://github.com/Zijian-Ni/prompt-firewall) - LLM prompt 防火墙：检测 + 拦截注入。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/prompt-firewall?style=flat-square)
- [LLM Guard](https://github.com/protectai/llm-guard) - LLM 输入输出扫描安全工具包。![GitHub stars](https://img.shields.io/github/stars/protectai/llm-guard?style=flat-square)
- [Rebuff](https://github.com/protectai/rebuff) - 📦 **Archived**（2024-08）。自我加固 prompt 注入检测器。![GitHub stars](https://img.shields.io/github/stars/protectai/rebuff?style=flat-square)
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - LLM 输出验证与纠正。![GitHub stars](https://img.shields.io/github/stars/guardrails-ai/guardrails?style=flat-square)
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - 给 LLM 对话系统加可编程护栏的工具包。![GitHub stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails?style=flat-square)
- [Vigil](https://github.com/deadbits/vigil-llm) - 💤 **Stale**（2024-01 起无更新）。LLM 安全扫描器。![GitHub stars](https://img.shields.io/github/stars/deadbits/vigil-llm?style=flat-square)
- [Lakera Guard](https://www.lakera.ai/) - 企业级 AI 安全平台。
- [Garak](https://github.com/NVIDIA/garak) - NVIDIA 出品的 LLM 漏洞扫描器。![GitHub stars](https://img.shields.io/github/stars/NVIDIA/garak?style=flat-square)
- [Invariant Guardrails](https://github.com/invariantlabs-ai/invariant) - 🆕 Agent 运行时策略执行 + 安全检查。![GitHub stars](https://img.shields.io/github/stars/invariantlabs-ai/invariant?style=flat-square)
- [Prompt Armor](https://promptarmor.com/) - 🆕 企业级 prompt 注入实时检测。
- [Descope MCP Auth](https://www.descope.com/) - 🆕 MCP 服务的认证与授权层。
- [AgentDojo](https://github.com/ethz-spylab/agentdojo) - 🆕 ETH 苏黎世评测工具调用 Agent 的 prompt 注入攻防的研究基准。![GitHub stars](https://img.shields.io/github/stars/ethz-spylab/agentdojo?style=flat-square)
- [ModelScan](https://github.com/protectai/modelscan) - 扫描 ML 模型权重文件（Pickle / PyTorch / TF）的反序列化攻击。![GitHub stars](https://img.shields.io/github/stars/protectai/modelscan?style=flat-square)
- [PyRIT](https://github.com/Azure/PyRIT) - 微软自动化红队框架。![GitHub stars](https://img.shields.io/github/stars/Azure/PyRIT?style=flat-square)

---

## 🔍 RAG 与知识库

*Agent 的检索增强生成与知识管理系统。*

- [LlamaIndex](https://github.com/run-llama/llama_index) - LLM 应用的数据框架：摄取 / 结构化 / 访问私有数据。![GitHub stars](https://img.shields.io/github/stars/run-llama/llama_index?style=flat-square)
- [LangChain Retrievers](https://github.com/langchain-ai/langchain) - LangChain 的检索器与文档加载器集合。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)
- [Haystack](https://github.com/deepset-ai/haystack) - 端到端 RAG。![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square)
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - 文档预处理与提取。![GitHub stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured?style=flat-square)
- [Weaviate](https://github.com/weaviate/weaviate) - 开源向量数据库。![GitHub stars](https://img.shields.io/github/stars/weaviate/weaviate?style=flat-square)
- [Qdrant](https://github.com/qdrant/qdrant) - Rust 实现的高性能向量搜索。![GitHub stars](https://img.shields.io/github/stars/qdrant/qdrant?style=flat-square)
- [Milvus](https://github.com/milvus-io/milvus) - 大规模向量数据库。![GitHub stars](https://img.shields.io/github/stars/milvus-io/milvus?style=flat-square)
- [Pinecone](https://www.pinecone.io/) - 托管向量数据库 SaaS。
- [Chroma](https://github.com/chroma-core/chroma) - AI 原生开源向量数据库。![GitHub stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square)
- [Vanna](https://github.com/vanna-ai/vanna) - 📦 **Archived**（2026-02）。RAG-for-SQL：自然语言对话数据库。![GitHub stars](https://img.shields.io/github/stars/vanna-ai/vanna?style=flat-square)
- [LightRAG](https://github.com/HKUDS/LightRAG) - 🇨🇳 港大 HKUDS 的图式 RAG。![GitHub stars](https://img.shields.io/github/stars/HKUDS/LightRAG?style=flat-square)
- [Docling](https://github.com/DS4SD/docling) - IBM 文档转换工具，PDF / DOCX / HTML 等。![GitHub stars](https://img.shields.io/github/stars/DS4SD/docling?style=flat-square)
- [Kotaemon](https://github.com/Cinnamon/kotaemon) - 开源 RAG UI。![GitHub stars](https://img.shields.io/github/stars/Cinnamon/kotaemon?style=flat-square)
- [R2R](https://github.com/SciPhi-AI/R2R) - 端到端 RAG 服务，企业级。![GitHub stars](https://img.shields.io/github/stars/SciPhi-AI/R2R?style=flat-square)
- [RAGFlow](https://github.com/infiniflow/ragflow) - 🇨🇳 深度文档理解 RAG。![GitHub stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square)

---

## 💻 编程 Agent

### 终端 / CLI Agent

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - 直接在终端里运行的 Agent 编程工具。Opus 4.7 + `/think xhigh`。SWE-bench 80.9%。
- [Codex CLI](https://github.com/openai/codex) - OpenAI 出品，开源终端编程 Agent。![GitHub stars](https://img.shields.io/github/stars/openai/codex?style=flat-square)
- [Aider](https://github.com/Aider-AI/aider) - Git-aware 终端 AI 编程伙伴。![GitHub stars](https://img.shields.io/github/stars/Aider-AI/aider?style=flat-square)
- [Goose](https://github.com/block/goose) - Block 出品的开源 Agent 编程 CLI。![GitHub stars](https://img.shields.io/github/stars/block/goose?style=flat-square)

### IDE Agent

- [Cursor 3.09](https://www.cursor.com/) - 🆕 2026-04-03 更新。Agent 模式增强，支持 Vibe Coding。
- [Kilo Code](https://www.kilocode.com/) - 🇨🇳 🆕 2026-04 中文社区流行的 Cursor 替代。默认 MiniMax 模型。
- [Cursor](https://www.cursor.com/) - 2026-02 更新支持 8 个并行 Agent。
- [Windsurf](https://codeium.com/windsurf) - Codeium 的 Agent 化 IDE。
- [Cline](https://github.com/cline/cline) - VS Code 自主编程 Agent。![GitHub stars](https://img.shields.io/github/stars/cline/cline?style=flat-square)
- [Continue](https://github.com/continuedev/continue) - 开源 AI 编程助手（VS Code + JetBrains）。![GitHub stars](https://img.shields.io/github/stars/continuedev/continue?style=flat-square)
- [GitHub Copilot](https://github.com/features/copilot) - 2026 初支持 Agent 模式，`gh copilot` 终端集成。
- [Kiro](https://kiro.dev/) - AWS 自主 Agent。Spec-driven，最多 10 个并发任务。
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS 生态深度集成。

### 自主软件工程师

- [Devin 3.0](https://www.cognition.ai/) - 🆕 Cognition。动态重新规划、自愈代码、遗留代码迁移。多模态输入（UI 截图、视频）。
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - 自托管的开源 Agent 软件开发平台。![GitHub stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square)
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - 把 LLM 变成能修复 GitHub issue 的工程师。![GitHub stars](https://img.shields.io/github/stars/SWE-agent/SWE-agent?style=flat-square)
- [Devika](https://github.com/stitionai/devika) - 💤 **Stale**（2025-09 起无更新）。开源 Devin 替代。![GitHub stars](https://img.shields.io/github/stars/stitionai/devika?style=flat-square)
- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) - 📦 **Archived**（2025-05）。第一波自主编程项目，仅作历史参考。![GitHub stars](https://img.shields.io/github/stars/gpt-engineer-org/gpt-engineer?style=flat-square)
- [Codegen](https://github.com/codegen-sh/codegen-sdk) - 🆕 程序化代码操作 + 跨文件重构 SDK。![GitHub stars](https://img.shields.io/github/stars/codegen-sh/codegen-sdk?style=flat-square)
- [Qodo](https://www.qodo.ai/) - 🆕 AI 代码评审平台：质量 + 安全 + 测试生成。

---

## 🤖 Physical AI / 具身智能

*能感知、推理、在物理世界中行动的 AI —— 人形机器人、工厂自动化、Physical AI 基础设施。继语言 Agent 之后的下一波。*

### 基础模型与研究

- [Google Gemini Robotics ER-1.6](https://deepmind.google/) - 🆕 2026-04-14。机器人 AI，空间与物理推理增强。Agile Robotics 实地部署。
- [Project Prometheus (Bezos)](https://www.reuters.com/) - 🆕 贝佐斯主导的 Physical AI 项目。$10B / $38B 估值融资。
- [NVIDIA Isaac GR00T](https://developer.nvidia.com/isaac/gr00t) - 人形机器人基础模型平台。GTC 发布、Hannover Messe 2026 扩展。
- [NVIDIA Industrial AI Cloud](https://nvidianews.nvidia.com/) - 🆕 2026-04（Hannover Messe）。德国电信合建 AI factory。

### 人形机器人

- [Tesla Optimus Gen3](https://www.tesla.com/) - 🆕 2026 夏季量产。
- [Honour (荣耀) Humanoid](https://www.honor.com/) - 🇨🇳 🆕 2026 年人形半马世界纪录。
- [Zhiyuan (智元) AGIBOT](https://www.agibot.com/) - 🇨🇳 🆕 2026-04 新本体 + 基模 + 解决方案。把 2026 称为 "Deployment Year Zero"。
- [Unitree H 系列](https://www.unitree.com/) - 🇨🇳 国产 Boston Dynamics 对手，2026 持续迭代。
- [Agile Robotics](https://www.agile-robots.com/) - 🆕 Gemini Robotics ER-1.6 部署伙伴。德国机器人公司。
- [Shenzhen Humanoid Pilot Line](https://www.chinadailyhk.com/hk/article/631892) - 🇨🇳 🆕 **2026-04-12** 首条人形机器人中试线（深圳乐聚 + 东方精工）。2 小时一台，年 500~1000 台。佛山 1 万台 / 年大规模工厂同步规划中。

### 消费级机器人 / 可穿戴

- [Doubao AI Glasses (字节)](https://seed.bytedance.com/) - 🇨🇳 🆕 2026 Q2。实时翻译 + 物体识别 + 豆包 LLM。
- [Nothing AI Glasses/Earbuds](https://nothing.tech/) - 🆕 2026-04 公布。
- [Samsung Galaxy S26 (Gauss 2.3)](https://www.samsung.com/) - 端侧 Agent。
- [Meta Ray-Ban Stories 3](https://www.meta.com/) - Llama 集成深化。

### 自动驾驶

- [Tesla FSD v13](https://www.tesla.com/) - L4 部署扩展。
- [Waymo](https://waymo.com/) - 美国多城市 L4 商业化推进。
- [WeRide / Pony.ai / Baidu Apollo](https://www.weride.ai/) - 🇨🇳 中国 L4 车队扩区。

---

## 🎮 Agent 仿真与世界模型

*Agent 在仿真世界中训练、观察、应力测试的研究环境。世界模型 / 具身研究渗透到语言 Agent 设计中后越来越重要。*

- [Generative Agents](https://github.com/joonspk-research/generative_agents) - 💤 斯坦福经典 *Smallville*（Park et al., 2023）。25 个 LLM 角色 + 记忆 + 反思 + 计划。后续多 Agent 论文几乎都借鉴此实现。![GitHub stars](https://img.shields.io/github/stars/joonspk-research/generative_agents?style=flat-square)
- [Voyager](https://github.com/MineDojo/Voyager) - 💤 Minecraft 终生学习 Agent —— GPT-4 + skill library + curriculum（Wang et al., 2023）。开放式 Agent 评测的经典。![GitHub stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=flat-square)
- [SWE-Gym](https://github.com/SWE-Gym/SWE-Gym) - 用真实 GitHub issue 训练 SWE Agent 的开放环境，SWE-bench 配套。![GitHub stars](https://img.shields.io/github/stars/SWE-Gym/SWE-Gym?style=flat-square)
- [WebArena](https://webarena.dev/) - 真实可复现的 Web 环境（Reddit / 购物 / GitLab 克隆），OSWorld 与多数浏览器 Agent 论文使用。
- [WorkArena](https://github.com/ServiceNow/WorkArena) - ServiceNow 出品的企业工作场景 Web Agent 基准。![GitHub stars](https://img.shields.io/github/stars/ServiceNow/WorkArena?style=flat-square)
- [Genie 3 / Genie 4](https://deepmind.google/) - Google DeepMind 可玩 3D 世界模型，从 prompt 生成。闭源研究。
- [NVIDIA Cosmos](https://github.com/nvidia-cosmos/cosmos-predict1) - 具身 AI / 机器人的世界模型基础，生成物理合理的视频未来。![GitHub stars](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-predict1?style=flat-square)

---

## 📊 评测与 Leaderboard

*跟踪前沿 AI 能力的标准评测套件与实时榜单。*

- [BenchLM](https://benchlm.ai/) - 🆕 多家基准聚合榜单。2026-04 榜首：Claude Mythos 99，Gemini 3.1 Pro / GPT-5.4 并列 94，Claude Opus 4.6 / GPT-5.4 Pro 92，GLM-5 Reasoning 85（开源最高）。
- [SWE-bench Verified](https://www.swebench.com/) - 真实 GitHub issue 修复基准。2026-04 榜首：Claude Mythos 93.9%，Claude Opus 4.7 87.6%。
- [GPQA Diamond](https://github.com/idavidrein/gpqa) - 💤 数据集仓 2024-09 起无更新。专家级科学推理。2026-04 榜首：Gemini 3.1 Pro 94.3%（世界纪录）、Claude Opus 4.7 94.2%。
- [ARC-AGI 2](https://arcprize.org/) - 抽象推理。Gemini 3.1 Pro 77.1%。
- [OSWorld](https://os-world.github.io/) - 桌面 GUI 操作。GPT-5.4 75%（超过人类基线）。
- [LMArena](https://lmarena.ai/)（前 Chatbot Arena） - 众包对话偏好。Opus 4.6 当前领先。
- [MMLU-Pro](https://github.com/TIGER-AI-Lab/MMLU-Pro) - MMLU 加难版。![GitHub stars](https://img.shields.io/github/stars/TIGER-AI-Lab/MMLU-Pro?style=flat-square)
- [LiveCodeBench](https://livecodebench.github.io/) - 持续更新的竞赛风编程基准。
- [AIME 2025 / Humanity's Last Exam (HLE)](https://agi.safe.ai/) - 数学 / 博士级综合推理。
- [Terminal-Bench](https://www.tbench.ai/) - CLI Agent 评测。Codex CLI 77.3%。
- [Wolfram LLM Benchmarking Project](https://www.wolfram.com/llm-benchmarking-project/) - 英文规格 → Wolfram Language 代码生成。

---

## 🖥️ Computer Use / 桌面 Agent

*能看屏幕、控鼠键、自动操作 OS 级软件的 Agent。纯浏览器 Agent 见 [🌐 浏览器与 Web Agent](#-浏览器与-web-agent)。*

- [Claude Computer Use](https://www.anthropic.com/) - 🆕 Anthropic "Desktop Intelligence"，看屏幕 + 用鼠标键盘。
- [OpenAI Operator](https://openai.com/) - 🆕 浏览器 Agent，订票、填表、网页任务。
- [Google Project Mariner](https://deepmind.google/) - 🆕 Gemini 驱动的多任务 AI，支持并行任务和习惯学习。
- [Microsoft Copilot Agents](https://www.microsoft.com/en-us/microsoft-copilot/) - 🆕 Microsoft 365 上的自主后台 Agent。
- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) - 让 LLM 在本地跑代码的自然语言接口。![GitHub stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter?style=flat-square)
- [Manus AI](https://manus.im/) - 🇨🇳 🆕 通用自主 Agent，云本地混合，研究 / 编程 / 复杂任务。
- [Genspark](https://www.genspark.ai/) - 🆕 mixture-of-agents 全能工作 Agent，能打电话。
- [Perplexity Computer](https://www.perplexity.ai/) - 🆕 多模型编排 + 本地文件访问，研究向。
- [Beam AI](https://beam.ai/) - 🆕 自学习桌面 Agent。

---

## 🌐 浏览器与 Web Agent

*真实浏览器中工作的 Agent —— 导航、点击、抓取、跨页流程。*

- [Browser Use](https://github.com/browser-use/browser-use) - 2026 年开源浏览器 Agent 事实标准。92K star。![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square)
- [Stagehand](https://github.com/browserbase/stagehand) - Browserbase 出品的"浏览器 Agent SDK"：类型化 `act / extract / observe`，跑在 Playwright 上。MIT。![GitHub stars](https://img.shields.io/github/stars/browserbase/stagehand?style=flat-square)
- [Steel Browser](https://github.com/steel-dev/steel-browser) - 🆕 AI Agent 专用开源浏览器 API：自带 session 持久化 + 代理轮换。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=flat-square)
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - 用 LLM + 视觉自动化网页流程。AGPL-3.0。![GitHub stars](https://img.shields.io/github/stars/Skyvern-AI/skyvern?style=flat-square)
- [AgentQL](https://github.com/tinyfish-io/agentql) - 查询语言 + Playwright 集成。动态 / 杂乱页面健壮。![GitHub stars](https://img.shields.io/github/stars/tinyfish-io/agentql?style=flat-square)
- [Hyperbrowser MCP](https://github.com/hyperbrowserai/mcp) - 🆕 托管无头浏览器 + 标准 MCP 工具接入 Claude / GPT / LangChain。![GitHub stars](https://img.shields.io/github/stars/hyperbrowserai/mcp?style=flat-square)
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - 🆕 微软官方 Playwright MCP server。生产级即插即用。![GitHub stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat-square)
- [MultiOn](https://www.multion.ai/) - 托管浏览器 Agent，原生 Reasoning + Memory。闭源。
- [Browserbase](https://www.browserbase.com/) - AI Agent 专用浏览器云：隐身、持久化、验证码、可观测性。

---

## 🗣️ 语音与多模态 Agent

- [ElevenLabs](https://elevenlabs.io/) - AI 语音合成 + 对话 Agent。
- [Vapi](https://github.com/VapiAI/server-sdk-python) - 语音 AI Agent 平台。![GitHub stars](https://img.shields.io/github/stars/VapiAI/server-sdk-python?style=flat-square)
- [Retell AI](https://www.retellai.com/) - 生产级对话语音 AI。
- [Bland AI](https://www.bland.ai/) - 企业级 AI 电话平台。
- [LiveKit Agents](https://github.com/livekit/agents) - 实时多模态 Agent（语音 + 视频 + 数据）。![GitHub stars](https://img.shields.io/github/stars/livekit/agents?style=flat-square)
- [Pipecat](https://github.com/pipecat-ai/pipecat) - 开源语音多模态对话框架。![GitHub stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=flat-square)
- [Vocode](https://github.com/vocodedev/vocode-python) - 💤 **Stale**（2024-11 起无更新）。![GitHub stars](https://img.shields.io/github/stars/vocodedev/vocode-python?style=flat-square)
- [Bolna](https://github.com/bolna-ai/bolna) - 端到端开源语音 AI。![GitHub stars](https://img.shields.io/github/stars/bolna-ai/bolna?style=flat-square)
- [Cartesia](https://www.cartesia.ai/) - 🆕 实时低延迟语音 AI。
- [Meta Voice AI](https://ai.meta.com/) - 🆕 收购 PlayHT/Play.ai 后的 Meta 语音技术。原 Play.ai 平台 2025-12-31 关停。
- [Sesame](https://www.sesame.com/) - 🆕 情绪感知 + 自然对话的语音 AI 伙伴。

---

## 📱 个人 AI Agent

- [OpenClaw](https://github.com/openclaw/openclaw) - 🆕 多渠道、本地运行的个人 AI Agent 平台。![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat-square)
- [Rabbit R1](https://www.rabbit.tech/) - 大动作模型驱动的硬件 AI 助理。
- [Limitless](https://www.limitless.ai/) - 个性化 AI（前 Rewind）。
- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) - 自然语言计算机接口。![GitHub stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter?style=flat-square)
- [01 Light](https://github.com/OpenInterpreter/01) - 💤 **Stale**（2024-11 起无更新）。开源语音电脑接口。![GitHub stars](https://img.shields.io/github/stars/OpenInterpreter/01?style=flat-square)
- [Leon](https://github.com/leon-ai/leon) - 自托管开源个人助理。![GitHub stars](https://img.shields.io/github/stars/leon-ai/leon?style=flat-square)
- [Khoj](https://github.com/khoj-ai/khoj) - 你的笔记 / 文档 / 图片的"第二大脑"AI。![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=flat-square)
- [Humane AI Pin](https://humane.com/) - 无屏幕环境计算的可穿戴 AI。
- [Arahi AI](https://arahi.ai/) - 🆕 个人生产力 + 业务自动化助理。
- [Lindy AI](https://www.lindy.ai/) - 🆕 邮件 / 日历 / 工作流的无代码 Agent。
- [MuleRun](https://www.mulerun.ai/) - 🆕 周期任务的常驻 Agent。

---

## 📱 手机 Agent

*操控 Android / iOS 的 GUI Agent —— 桌面 Computer Use 之后的下一前沿。*

- [Mobile-Agent](https://github.com/X-PLUG/MobileAgent) - 🇨🇳 阿里多模态手机控制 Agent 家族（v1 → v3 + Mobile-Agent-E / V）。Android 基准 SOTA。![GitHub stars](https://img.shields.io/github/stars/X-PLUG/MobileAgent?style=flat-square)
- [AppAgent](https://github.com/mnotgod96/AppAgent) - 💤 腾讯多模态智能体，通过点 / 滑操作 App。早期影响力实现。![GitHub stars](https://img.shields.io/github/stars/mnotgod96/AppAgent?style=flat-square)
- [Apple Intelligence](https://www.apple.com/apple-intelligence/) - iOS / iPadOS / macOS 端侧 Agent 层。App Intents + 屏幕感知动作。
- [Samsung Galaxy AI / Bixby 2.0](https://www.samsung.com/global/galaxy/galaxy-ai/) - Galaxy S26 端侧 Gauss。
- [Google Gemini for Android](https://gemini.google/) - 全面替换 Google Assistant，包括系统意图与 Workspace。
- [Magma](https://microsoft.github.io/Magma/) - 微软研究多模态 Agent 基座，统一 UI / 机器人 / 物理动作。

---

## 🏢 企业级 Agent 平台

- [Salesforce Agentforce](https://www.salesforce.com/agentforce/) - CRM 自主 Agent —— 销售 / 客服 / 营销。
- [Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio) - 企业 Copilot 与 Agent 构建。
- [Gemini Enterprise Agent Platform](https://cloud.google.com/blog/products/ai-machine-learning/introducing-gemini-enterprise-agent-platform) - 🆕 **2026-04-22**（Google Cloud Next '26）。Vertex AI 进化为统一企业 Agent 中心。Gemini 3.1 Pro/Flash + Lyria 3 + 第三方模型（Claude Opus / Sonnet / Haiku）。
- [Google Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) - 企业生成式 AI Agent 构建。
- [Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents/) - 多步任务 Agent。
- [ServiceNow AI Agents](https://www.servicenow.com/products/ai-agents.html) - 🆕 ITSM Agent + AI Control Tower。
- [IBM watsonx Orchestrate](https://www.ibm.com/products/watsonx-orchestrate) - 跨企业应用的 AI 助理平台。
- [Oracle AI Agents](https://www.oracle.com/artificial-intelligence/) - 🆕 与 Oracle Fusion Cloud ERP 集成。
- [Moveworks](https://www.moveworks.com/) - 跨系统企业 copilot。
- [UiPath Agentic Automation](https://www.uipath.com/) - 🆕 在 RPA 之上叠加 Agent 推理。
- [AgentX](https://www.agentx.so/) - 🆕 即插即用的企业 Agent 自动化。
- [OutSystems](https://www.outsystems.com/) - 🆕 关键应用快速构建 + Agent 治理。
- [Sema4.ai](https://sema4.ai/) - 🆕 Python 优先 + 内置治理的企业 Agent 平台。

---

## 📊 Agent 评估与可观测性

- [LangSmith](https://www.langchain.com/langsmith) - LangChain 的官方调试 / 评测 / 监控平台。
- [LangSmith SDK](https://github.com/langchain-ai/langsmith-sdk) - 客户端 SDK。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langsmith-sdk?style=flat-square)
- [Langfuse](https://github.com/langfuse/langfuse) - 开源 LLM 工程平台：可观测性 + 评测 + prompt 管理。![GitHub stars](https://img.shields.io/github/stars/langfuse/langfuse?style=flat-square)
- [Helicone](https://github.com/Helicone/helicone) - 开源 LLM 可观测性。![GitHub stars](https://img.shields.io/github/stars/Helicone/helicone?style=flat-square)
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - 开源 LLM 可观测性 + 评测。![GitHub stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=flat-square)
- [Braintrust](https://www.braintrust.dev/) - LLM 评测 + 优化平台。
- [LMArena (formerly LMSYS Chatbot Arena)](https://lmarena.ai/) - 🆕 众包 LLM 偏好投票。
- [Patronus AI](https://www.patronus.ai/) - 🆕 自动 LLM 评测 + 红队。
- [DeepEval](https://github.com/confident-ai/deepeval) - Pytest 风格的 LLM 评测框架，14+ 内置指标。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/confident-ai/deepeval?style=flat-square)
- [Agenta](https://github.com/agenta-ai/agenta) - 🆕 一体化开源 LLMOps。![GitHub stars](https://img.shields.io/github/stars/agenta-ai/agenta?style=flat-square)
- [AutoEvals](https://github.com/braintrustdata/autoevals) - 独立的最佳实践评测器库（事实性 / JSON 有效性 / 语义相似度等）。Braintrust 出品。![GitHub stars](https://img.shields.io/github/stars/braintrustdata/autoevals?style=flat-square)
- [BenchClaw](https://github.com/Agnuxo1/benchclaw) - ⚠️ **Unverified**。自称多维度 Agent 评测。8 个 awesome 列表 7 个拒收，2 star 单维护者。**仅作可见性收录**。![GitHub stars](https://img.shields.io/github/stars/Agnuxo1/benchclaw?style=flat-square)
- [PromptEden](https://www.prompteden.com) - ⚠️ **Unverified**。商业 SaaS：监控 ChatGPT / Claude / Gemini / Perplexity / Copilot / Grok 如何描述你的品牌。同款 PR 同日投了 10 个 awesome 列表。**仅作可见性收录**。

---

## 🔬 AI 研究工具

- [Hugging Face Transformers](https://github.com/huggingface/transformers) - 模型与训练工具的事实标准库。![GitHub stars](https://img.shields.io/github/stars/huggingface/transformers?style=flat-square)
- [vLLM](https://github.com/vllm-project/vllm) - 高吞吐 LLM 推理与服务。![GitHub stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat-square)
- [SGLang](https://github.com/sgl-project/sglang) - 高性能 LLM 推理引擎。![GitHub stars](https://img.shields.io/github/stars/sgl-project/sglang?style=flat-square)
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - C/C++ 高性能 LLM 推理。![GitHub stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=flat-square)
- [Ollama](https://github.com/ollama/ollama) - 本地跑 LLM 的最简单方法。![GitHub stars](https://img.shields.io/github/stars/ollama/ollama?style=flat-square)
- [LM Studio](https://lmstudio.ai/) - 桌面本地 LLM GUI，多提供商。
- [OpenRouter](https://openrouter.ai/) - 一个 API 统一访问 100+ LLM。
- [Unsloth](https://github.com/unslothai/unsloth) - 2 倍运行、节省 70% 显存的 LLM 微调。![GitHub stars](https://img.shields.io/github/stars/unslothai/unsloth?style=flat-square)
- [MLX](https://github.com/ml-explore/mlx) - Apple Silicon 上的机器学习框架。![GitHub stars](https://img.shields.io/github/stars/ml-explore/mlx?style=flat-square)
- [Weights & Biases](https://wandb.ai/) - ML 实验跟踪 + 模型管理。
- [Label Studio](https://github.com/HumanSignal/label-studio) - 多类型数据标注平台。![GitHub stars](https://img.shields.io/github/stars/HumanSignal/label-studio?style=flat-square)
- [DSPy](https://github.com/stanfordnlp/dspy) - 编程代替 prompt 工程。![GitHub stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square)

---

## 📚 学习资源

### 论文

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) - 定义 ReAct 范式的里程碑论文。
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) - LLM 学会使用外部工具。
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) - 使用 LLM 创建可信人类行为 Agent。
- [LLM-based Autonomous Agents Survey](https://arxiv.org/abs/2308.11432) - 中人大 LLM 自主 Agent 综述。
- [The Rise and Potential of LLM Based Agents](https://arxiv.org/abs/2309.07864) - LLM Agent 发展与潜力。

### 课程与教程

- [LangChain Academy](https://academy.langchain.com/) - LangChain 官方课程（包含 LangGraph）。
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) - 涵盖主要框架 / 协议的 AI 短课。
- [LLM Agents MOOC (Berkeley)](https://llmagents-learning.org/f24) - UC Berkeley 的 LLM Agent 课程。
- [Microsoft Agent Framework Docs](https://learn.microsoft.com/en-us/agent-framework/) - 🆕 微软统一 Agent 框架官方文档。
- [Hugging Face Agents Course](https://github.com/huggingface/agents-course) - 5 单元免费课程（smolagents / LangGraph / Llama-Index）。![GitHub stars](https://img.shields.io/github/stars/huggingface/agents-course?style=flat-square)
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) - 官方调工具、Computer Use、Agent 模式、Claude Code 示例本。![GitHub stars](https://img.shields.io/github/stars/anthropics/anthropic-cookbook?style=flat-square)
- [Google Gemini Cookbook](https://github.com/google-gemini/cookbook) - Gemini API 示例：grounding / function calling / 多模态 / live audio。![GitHub stars](https://img.shields.io/github/stars/google-gemini/cookbook?style=flat-square)
- [LLM Course (Maxime Labonne)](https://github.com/mlabonne/llm-course) - LLM 从入门到微调的完整课程 + Colab。![GitHub stars](https://img.shields.io/github/stars/mlabonne/llm-course?style=flat-square)
- [Anthropic Courses](https://github.com/anthropics/courses) - Anthropic 官方 prompt engineering / 评测 / 工具调用课程。![GitHub stars](https://img.shields.io/github/stars/anthropics/courses?style=flat-square)

### 精选列表

- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - 💤 **Stale**（2025-02 起无更新）。E2B 出品。![GitHub stars](https://img.shields.io/github/stars/e2b-dev/awesome-ai-agents?style=flat-square)
- [awesome-llm-agents](https://github.com/kaushikb11/awesome-llm-agents) - LLM Agent 资源。![GitHub stars](https://img.shields.io/github/stars/kaushikb11/awesome-llm-agents?style=flat-square)
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - 🆕 MCP server 实现精选。![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat-square)

---

## 🇨🇳 中国 AI 生态

*中国大陆团队主导或主要面向中文市场的重要项目。列出是因为中国技术栈越来越形成独立生态，有自己的框架、模型、开发者文化。*

*中国友出品的基础模型（Qwen / DeepSeek / GLM / Doubao / Kimi / Hunyuan / ERNIE）已直接列在 [🧠 基础大模型](#-基础大模型-2026) 下。*

### Agent 平台与框架

- [Dify](https://github.com/langgenius/dify) - 开源 LLM 应用开发平台 + 可视化 Agent 构建。中文技术圈主流低代码 Agent 画布。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Lobe Chat](https://github.com/lobehub/lobe-chat) - 多 Agent 聊天工作区 + 插件 / Agent 市场。最高 star 的 TypeScript AI 项目之一。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/lobehub/lobe-chat?style=flat-square)
- [Cozeloop](https://github.com/coze-dev/cozeloop) - 🆕 字节 Coze 团队开源的 Agent 优化平台。![GitHub stars](https://img.shields.io/github/stars/coze-dev/cozeloop?style=flat-square)
- [AgentScope](https://github.com/modelscope/agentscope) - 阿里 ModelScope 多 Agent 框架 + 可视化调试 + 分布式执行。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/modelscope/agentscope?style=flat-square)
- [Bisheng](https://github.com/dataelement/bisheng) - 开源企业级 LLM DevOps：工作流 / RAG / Agent / 微调 / 评测。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/dataelement/bisheng?style=flat-square)
- [MetaGPT](https://github.com/geekan/MetaGPT) - SOP 角色多 Agent（PM / 架构师 / 工程师）。DeepWisdom 出品。![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat-square)

### RAG / 知识

- [FastGPT](https://github.com/labring/FastGPT) - 知识库优先的 LLM 平台：数据摄入 / RAG / 可视化工作流。![GitHub stars](https://img.shields.io/github/stars/labring/FastGPT?style=flat-square)
- [QAnything](https://github.com/netease-youdao/QAnything) - 💤 网易有道出品，针对任意本地文档的问答引擎。![GitHub stars](https://img.shields.io/github/stars/netease-youdao/QAnything?style=flat-square)
- [RAGFlow](https://github.com/infiniflow/ragflow) - 深度文档理解的 RAG 引擎 —— 扫描 PDF 、表格、图表处理能力强。![GitHub stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square)
- [LightRAG](https://github.com/HKUDS/LightRAG) - 港大 HKUDS 轻量图式 RAG。![GitHub stars](https://img.shields.io/github/stars/HKUDS/LightRAG?style=flat-square)

### 个人与生产力

- [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) - 开源 Notion 替代品 + AI 工作区。AGPL-3.0。![GitHub stars](https://img.shields.io/github/stars/AppFlowy-IO/AppFlowy?style=flat-square)
- [Manus AI](https://manus.im/) - 通用自主 Agent（北京 Butterfly Effect）。中文技术圈 2026 最受关注的 Agent 产品之一。
- [Coze (扣才)](https://www.coze.cn/) - 字节无代码 Agent 构建。国内面向消费者；国际版为 coze.com。
- [通义千问 Agent](https://tongyi.aliyun.com/) - 阿里大众消费者 Agent，集成在淘宝 / 钉钉 / 夸克。
- [Doubao Agents](https://www.doubao.com/) - 字节豆包模型上的主力消费者助手。

### 开发者工具

- [Kilo Code](https://www.kilocode.com/) - 2026 中文社区热门的 Cursor 替代。默认 MiniMax 模型。
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - 中文开发者圈装机量最高的开源桌面 LLM 客户端，多提供商 + 知识库。![GitHub stars](https://img.shields.io/github/stars/CherryHQ/cherry-studio?style=flat-square)
- [ScienceOne 100 / 磐石100](https://english.cas.cn/newsroom/cas-in-media/202604/t20260429_1158251.shtml) - 🆕 中科院科研推理 Agent 系统，50+ 中科院研究所、100+ 科研场景、带 2000+ 研究工具。

---

## 📝 横向对比表

*2026 年最常见的“该选哪个？”决策矩阵。*

### 🏗️ Agent 框架（开源向）

| 框架 | 语言 | 多 Agent | 状态 / 图 | 流式 | License | 适合场景 |
|------|------|---------|------|------|---------|---------|
| [LangGraph](https://github.com/langchain-ai/langgraph) | Python / JS | ✅ 原生 | ✅ 一等公民 | ✅ | MIT | 生产级有状态工作流 |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Python | ✅ 角色扮演 | ⚠️ 任务图 | ✅ | MIT | 角色化 Agent 团队 |
| [AutoGen / Microsoft Agent Framework](https://github.com/microsoft/autogen) | Python / .NET | ✅ 对话 | ⚠️ Group Chat | ✅ | CC-BY-4.0 / MIT | 企业多 Agent 对话 |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Python | ✅ handoff | ❌ | ✅ | MIT | OpenAI 原生生产 |
| [Mastra](https://github.com/mastra-ai/mastra) | TypeScript | ✅ | ✅ workflows | ✅ | Elastic-2.0 | TypeScript 优先 |
| [Google ADK](https://github.com/google/adk-python) | Python / Java | ✅ 层级 | ⚠️ | ✅ | Apache-2.0 | Gemini + Vertex AI |
| [DSPy](https://github.com/stanfordnlp/dspy) | Python | ⚠️ 模块 | ⚠️ 编程式 | ✅ | MIT | 程序化 prompt 优化 |
| [Phidata / Agno](https://github.com/phidatahq/phidata) | Python | ✅ teams | ❌ | ✅ | MPL-2.0 | 多模态 Agent + 记忆 |

### 🧪 沙箱（运行 Agent 生成代码）

| 沙箱 | 部署 | 冷启动 | 语言 | 持久化 | License | 适合场景 |
|------|------|---------|------|---------|---------|---------|
| [E2B](https://github.com/e2b-dev/E2B) | 云（托管） | ~150ms | Python / Node / shell | per-session | Apache-2.0 | OpenAI Agents SDK / 生产 |
| [Daytona](https://github.com/daytonaio/daytona) | 云 / 自托管 | ~500ms | 多语言 | 持久化 workspace | AGPL-3.0 | 长任务开发 |
| [Modal](https://modal.com/) | 云（托管） | ~200ms | Python | function-scoped | 闭源 | GPU + Serverless Agent |
| [Microsandbox](https://github.com/superradcompany/microsandbox) | 本地 microVM | ~100ms | 多语言 | per-session | Apache-2.0 | 隐私优先的本地开发 |
| [SandboxFusion](https://github.com/bytedance/SandboxFusion) | 自托管 | ~300ms | 20+ 语言 | 临时 | Apache-2.0 | 评测 / 基准流水线 |

### 🌐 浏览器 Agent 栈

| 栈 | 思路 | 部署 | 优势 | License |
|------|------|------|------|---------|
| [Browser Use](https://github.com/browser-use/browser-use) | Vision + DOM（Playwright） | 自托管 | 92K star，社区第一 | MIT |
| [Stagehand](https://github.com/browserbase/stagehand) | 类型化 act / extract / observe | Browserbase / 自托管 | 强类型 + 结构化输出 | MIT |
| [Steel Browser](https://github.com/steel-dev/steel-browser) | 无头 Chrome API | 自托管 / 云 | session + proxy + captcha | Apache-2.0 |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Vision 优先 | 自托管 | 抗动态页面强 | AGPL-3.0 |
| [AgentQL](https://github.com/tinyfish-io/agentql) | 查询语言 | SDK + 自托管 | 语义化 selector | MIT |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | MCP 原生 | 自托管 | MCP 客户端即插即用 | Apache-2.0 |

### 📊 评估与可观测性

| 工具 | 自托管 | OpenTelemetry | 评测套件 | Prompt 管理 | License |
|------|---------|----------|---------|------------|---------|
| [Langfuse](https://github.com/langfuse/langfuse) | ✅ | ✅ | ✅ | ✅ | MIT |
| [Helicone](https://github.com/Helicone/helicone) | ✅ | ✅ | ⚠️ 基础 | ✅ | Apache-2.0 |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | ✅ | ✅ | ✅ | ⚠️ | Elastic-2.0 |
| [LangSmith](https://www.langchain.com/langsmith) | ❌（仅云） | ✅ | ✅ | ✅ | 闭源 |
| [Braintrust](https://www.braintrust.dev/) | ❌（仅云） | ✅ | ✅ | ✅ | 闭源 |
| [DeepEval](https://github.com/confident-ai/deepeval) | ✅（库） | ⚠️ 依赖 Confident | ✅ | ❌ | Apache-2.0 |
| [Agenta](https://github.com/agenta-ai/agenta) | ✅ | ✅ | ✅ | ✅ | Apache-2.0 |
| [OpenLLMetry](https://github.com/traceloop/openllmetry) | ✅（插件） | ✅ 原生 | ❌ | ❌ | Apache-2.0 |

### 💻 编程 Agent —— 头部选择

| 工具 | 形态 | 开源 | 免费层 | SWE-bench | 适合场景 |
|------|------|------|--------|-----------|----------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | CLI / IDE | ❌ | ⚠️ Pro | 80.9% | 长期工程 |
| [Codex CLI](https://github.com/openai/codex) | CLI | ✅ | ✅ | n/a（Terminal-Bench 77.3%） | OpenAI 原生 shell |
| [Cursor](https://www.cursor.com/) | IDE | ❌ | ✅（限制） | n/a | 配对编程体验 |
| [Cline](https://github.com/cline/cline) | VS Code 扩展 | ✅ | ✅（BYO） | n/a | 开源 IDE 替代 |
| [Aider](https://github.com/Aider-AI/aider) | CLI | ✅ | ✅（BYO） | Polyglot 强 | Git-aware 重构 |
| [Devin 3.0](https://www.cognition.ai/) | 云 | ❌ | ❌ | 领先 | 完全托管长任务 |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 自托管 | ✅ | ✅ | 有竞争力 | 自部署 SWE Agent |

*表格于 2026-05-05 验证。数据变化请提 PR。*

---

## 🌟 2026 年值得关注的 Agent 项目

*塑造 2026 年 AI Agent 格局的里程碑与事件。*

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol/servers) - 成为 Agent 工具互联互通的事实标准。已损赠给 Linux Foundation。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat-square)
- [A2A Protocol](https://github.com/google/A2A) - 🆕 Google A2A 让跨框架 Agent 协作，150+ 合作伙伴。![GitHub stars](https://img.shields.io/github/stars/google/A2A?style=flat-square)
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - SWE-bench 80.9%，成为 2026 终端编程 Agent 首选。
- [Kiro](https://kiro.dev/) - 🆕 AWS 发布的自主编程 Agent，可同时管理 10 个任务。
- [Devin 3.0](https://www.cognition.ai/) - 🆕 动态重规划、自愉合代码、遗留代码迁移。
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/) - 🆕 AutoGen + Semantic Kernel 合并。
- [OpenAI Codex CLI](https://github.com/openai/codex) - OpenAI 进入开源终端 Agent 赛道。![GitHub stars](https://img.shields.io/github/stars/openai/codex?style=flat-square)
- [Browser Use](https://github.com/browser-use/browser-use) - 让 AI Agent 自然使用网页的突破性项目。![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square)
- [Claude Computer Use](https://www.anthropic.com/) - 🆕 Claude "Desktop Intelligence"。
- [Manus AI](https://manus.im/) - 🇨🇳 🆕 通用自主 Agent，能处理研究 / 编程 / 复杂工作流。
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - 开源 SWE Agent 平台大量采用。![GitHub stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square)
- [Dify](https://github.com/langgenius/dify) - 🇨🇳 低代码 LLM Agent 平台走向主流。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Cline](https://github.com/cline/cline) - VS Code 自主编程 Agent。![GitHub stars](https://img.shields.io/github/stars/cline/cline?style=flat-square)
- [Mem0](https://github.com/mem0ai/mem0) - Agent 架构中的记忆层必备。![GitHub stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square)
- [Sora 停服](https://openai.com/) - 🆕 OpenAI 2026-04 关闭 Sora，战略转向企业 + 推理。
- [Kling VIDEO 3.0](https://kling.ai/) - 🇨🇳 🆕 快手出品，Sora 停服后的领先视频平台。
- [Cohere + Aleph Alpha 合并](https://siliconangle.com/2026/04/24/ai-startups-cohere-aleph-alpha-merge-600m-new-funding/) - 🆕 **2026-04-24**。东西合作 “主权 AI”，多伦多 + 德国双总部，$20B 估值 + $600M 资金。
- [ScienceOne 100 / 磐石100](https://english.cas.cn/newsroom/cas-in-media/202604/t20260429_1158251.shtml) - 🇨🇳 🆕 **2026-04-28~29**。中科院专业科研 AI 系统。
- [Google 投资 Anthropic $40B](https://aibusiness.com/generative-ai/google-could-invest-another-40-billion-anthropic) - 🆕 **2026-04**。$10B 初始 + 最高 $30B，含 5GW 算力。

---

## 📅 2026 AI 时间线

*2026 年 AI 重要里程碑。*

| 时间 | 事件 | 分类 |
|------|------|------|
| **2026-01** | AMD Ryzen AI 400 在 CES 发布 —— 主流 AI PC 及 60 TOPS NPU | 硬件 |
| **2026-02** | Claude Opus 4.6 发布 —— Agent 团队能力 | 模型 |
| **2026-02** | Claude Sonnet 4.6 发布 —— 1M 上下文，Agent 检索 | 模型 |
| **2026-02** | Gemini 3.1 Pro 发布 | 模型 |
| **2026-02** | Qwen3.5 系列发布 —— 原生多模态 + Agent 编程 | 模型 |
| **2026-02** | Qwen3-Coder-Next 发布 —— 80B MoE 编程 Agent 模型 | 模型 |
| **2026-02** | Cursor 支持 8 个并行 Agent | 工具 |
| **2026-02** | GitHub Copilot 扩展 Agent 模式与模型 | 工具 |
| **2026-03** | Gemini 3.1 Flash Lite 面向开发者发布 | 模型 |
| **2026-03** | Mistral Forge 发布 —— 自定义 LLM 训练平台 | 平台 |
| **2026-03** | Microsoft Agent Framework（AutoGen + Semantic Kernel）目标 GA | 框架 |
| **2026-03** | DeepSeek 宣布使用最新英伟达芯片训练新模型 | 模型 |
| **2026-03** | MCP 2026 路线图发布 —— 重点生产规模化与治理 | 协议 |
| **2026-03** | Sora 关闭公告（4 月 26 日应用下架） | 事件 |
| **2026-04-02** | 阿里巴巴发布 Qwen3.6-Plus 闭源旗舰 | 模型 |
| **2026-04-03** | Microsoft AI Agent Governance Toolkit 开源 | 工具 |
| **2026-04-06** | Microsoft Agent Framework 正式宣布 | 框架 |
| **2026-04-07** | 智谱 GLM-5.1 开源 —— 744B MoE，华为昂腾训练 | 模型 |
| **2026-04-08~09** | Meta Muse Spark 发布 —— MSL 首个模型 | 模型 |
| **2026-04** | Claude Mythos Preview —— 受控网络安全研究模型（BenchLM 99，SWE-bench 93.9%） | 模型 |
| **2026-04** | Sora 应用正式关闭 | 事件 |
| **2026-04-14** | Gemini Robotics ER-1.6 升级机器人 AI，增强空间推理 | 机器人 |
| **2026-04-15** | Qwen3.6-35B-A3B 开源（Apache 2.0）| 模型 |
| **2026-04-16** | Claude Opus 4.7 发布 —— SWE-bench Verified 87.6%，`/think xhigh` | 模型 |
| **2026-04-18** | Qwen3.6-Max-Preview 发布 | 模型 |
| **2026-04-20~21** | Kimi K2.6 发布 —— 1T MoE，1000-Agent 集群 | 模型 |
| **2026-04-22** | Qwen3.6-27B 开源 —— 27B 密集多模态 | 模型 |
| **2026-04-23** | 腾讯开源 Hunyuan Hy3 Preview —— 295B/21B MoE，256K 上下文 | 模型 |
| **2026-04-23** | Claude Managed Agents Memory 公测 —— 跨会话记忆 | 工具 |
| **2026-04-23** | OpenAI 发布 GPT-5.5 —— 代理 / 推理升级 | 模型 |
| **2026-04-24** | DeepSeek V4 Pro & Flash 发布 —— 1.6T MoE，1M 上下文，MIT | 模型 |
| **2026-04-24** | Cohere 与德国 Aleph Alpha 合并，$20B 估值 + $600M 资金 | 产业 |
| **2026-04-27** | 阿里天马 AI 图生视频进入公测 | 模型 |
| **2026-04-27** | LangGraph v0.3.19 发布，Swarm 预制 Agent | 框架 |
| **2026-04-28** | NVIDIA Nemotron 3 Nano Omni 发布 —— 30B 多模态 | 模型 |
| **2026-04-28~29** | 中科院 ScienceOne 100 / 磐石100 发布 —— 50+ 中科院研究所 | 模型 |
| **2026-04-30** | OpenAI GPT-5.5-Cyber 通过 TAC 计划扣发 | 模型 |
| **2026-04-30** | OpenAI 发布 [《构建 Agent 实战指南》](https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/) | 资源 |
| **2026-05-01** | Anthropic Claude Security 公测 —— Opus 4.7 驱动代码库漏洞扫描 | 工具 |
| **2026-05** | 麦子銀行报告 7 个月使用 Gemini Enterprise 节约 13 万小时 | 产业 |
| **2026-05** | Google 开始为启用车辆推送 Gemini，替代 Google Assistant（英语优先，美国首发） | 产业 |
| **2026-04** | Gartner 预计 2026 年底 40% 企业应用嵌入 AI Agent | 产业 |
| **2026-04** | Google 承诺对 Anthropic 跟进最高 $40B 投资（首期 $10B） | 产业 |
| **2026 持续** | A2A Protocol 合作伙伴增至 150+ | 协议 |
| **2026 持续** | 85% 开发者经常使用 AI 编程工具 | 产业 |
| **2026 持续** | 企业 Agent AI 实践加速 —— "Agents as a Service" 兴起 | 产业 |

---

## 贡献

请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。**反垃圾质量门槛**适用于中英日三个版本：自我推广批量铺货 PR 一律拒绝。

## License

MIT © [Zijian Ni](https://github.com/Zijian-Ni)

---

*Made with ❤️ by [Zijian Ni](https://github.com/Zijian-Ni) · 2026。中文版本与英文版保持同步，发现不一致以英文为准。*
