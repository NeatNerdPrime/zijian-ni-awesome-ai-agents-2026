<div align="center">

# 🤖 Awesome AI Agents 2026 · 日本語版

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/awesome-ai-agents-2026?style=social)](https://github.com/Zijian-Ni/awesome-ai-agents-2026)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Audited](https://img.shields.io/badge/Spam_Audited-2026--05--05-success.svg)](#️-ステータス凡例)
[![English](https://img.shields.io/badge/Lang-English-informational.svg)](README.md)
[![中文](https://img.shields.io/badge/Lang-中文-red.svg)](README.zh-CN.md)

**2026 年の AI モデル・エージェントフレームワーク・ツール・プロトコル・リソースを厳選したリスト —— エージェントが本格的にインフラ化した一年。**

*基盤大規模言語モデル、マルチモーダル生成、エージェントプロトコル（MCP / A2A）、コーディングエージェント、Computer Use、生成 AI までカバー。*

### 🏷️ ステータス凡例

各エントリには成熟度を一目で判断できるよう、以下のタグが付くことがあります:

- 🆕 **New** — 60 日以内に追加。実績はまだ確定していない
- 📦 **Archived** — リポジトリがアーカイブ済み。歴史的参照のためのみ残す
- 💤 **Stale** — 6 か月以上コミットなし。動作はするかもしれないが活発な保守はない
- ⚠️ **Unverified** — 提出は新しく、第三者の利用実績が乏しい（star が少ない / 単独メンテナ / 同じ PR を多数の awesome リストに同時投稿）。**可視性のための掲載で推奨ではない** —— 利用前に各自で評価すること
- 🇨🇳 **Chinese ecosystem** — 中国本土のチームによる、または主に中国市場を対象とするプロジェクト

[基盤モデル](#-基盤モデル-2026) · [マルチモーダル](#-マルチモーダルと生成-ai) · [プロトコル](#-エージェントプロトコルと標準) · [フレームワーク](#️-エージェントフレームワーク) · [IDE & ビジュアル](#️-エージェント-ide-とビジュアルビルダー) · [メモリ](#-エージェントメモリ) · [ツール](#-ツールと-api-連携) · [サンドボックス](#-エージェントサンドボックスと計算分離) · [セキュリティ](#️-エージェントセキュリティ) · [RAG](#-rag-とナレッジ) · [コーディング](#-コーディングエージェント) · [Physical AI](#-physical-ai--身体性エージェント) · [シミュレーション](#-エージェントシミュレーションと世界モデル) · [ベンチマーク](#-ベンチマークとリーダーボード) · [Computer Use](#️-computer-use--デスクトップエージェント) · [ブラウザ & Web](#-ブラウザと-web-エージェント) · [音声](#️-音声とマルチモーダルエージェント) · [パーソナル](#-パーソナル-ai-エージェント) · [モバイル](#-モバイルエージェント) · [エンタープライズ](#-エンタープライズエージェントプラットフォーム) · [評価](#-エージェント評価とオブザーバビリティ) · [研究ツール](#-ai-研究ツール) · [学習](#-学習リソース) · [中国エコシステム](#-中国-ai-エコシステム) · [比較](#-比較--サイドバイサイド表) · [2026 注目](#-2026-年に注目すべきエージェントプロジェクト) · [タイムライン](#-2026-ai-タイムライン)

</div>

---

## 目次

- [🧠 基盤モデル 2026](#-基盤モデル-2026)
- [🎨 マルチモーダルと生成 AI](#-マルチモーダルと生成-ai)
- [🔗 エージェントプロトコルと標準](#-エージェントプロトコルと標準)
- [🏗️ エージェントフレームワーク](#️-エージェントフレームワーク)
- [🛠️ エージェント IDE とビジュアルビルダー](#️-エージェント-ide-とビジュアルビルダー)
- [🧠 エージェントメモリ](#-エージェントメモリ)
- [🔌 ツールと API 連携](#-ツールと-api-連携)
- [🧪 エージェントサンドボックスと計算分離](#-エージェントサンドボックスと計算分離)
- [🛡️ エージェントセキュリティ](#️-エージェントセキュリティ)
- [🔍 RAG とナレッジ](#-rag-とナレッジ)
- [💻 コーディングエージェント](#-コーディングエージェント)
- [🤖 Physical AI / 身体性エージェント](#-physical-ai--身体性エージェント)
- [🎮 エージェントシミュレーションと世界モデル](#-エージェントシミュレーションと世界モデル)
- [📊 ベンチマークとリーダーボード](#-ベンチマークとリーダーボード)
- [🖥️ Computer Use / デスクトップエージェント](#️-computer-use--デスクトップエージェント)
- [🌐 ブラウザと Web エージェント](#-ブラウザと-web-エージェント)
- [🗣️ 音声とマルチモーダルエージェント](#️-音声とマルチモーダルエージェント)
- [📱 パーソナル AI エージェント](#-パーソナル-ai-エージェント)
- [📱 モバイルエージェント](#-モバイルエージェント)
- [🏢 エンタープライズエージェントプラットフォーム](#-エンタープライズエージェントプラットフォーム)
- [📊 エージェント評価とオブザーバビリティ](#-エージェント評価とオブザーバビリティ)
- [🔬 AI 研究ツール](#-ai-研究ツール)
- [📚 学習リソース](#-学習リソース)
- [🇨🇳 中国 AI エコシステム](#-中国-ai-エコシステム)
- [📝 比較 — サイドバイサイド表](#-比較--サイドバイサイド表)
- [🌟 2026 年に注目すべきエージェントプロジェクト](#-2026-年に注目すべきエージェントプロジェクト)
- [📅 2026 AI タイムライン](#-2026-ai-タイムライン)

---

## 🧠 基盤モデル 2026

*AI エコシステムを動かす最新の大規模言語モデル群、ベンダー別。20+ ベンダーから 65+ モデル。*

### OpenAI

- [GPT-5.5](https://openai.com/index/gpt-5-5-system-card/) - 🆕 **2026-04-23 公開**（コードネーム "Spud"）。エージェントタスク向けの新フロンティア: コーディング、オンライン調査、データ分析、自律的なツール操作。推論の安定性と長時間タスク処理能力が大幅向上。ChatGPT Plus / Pro / Business / Enterprise で利用可能。
- [GPT-5.5 Pro](https://openai.com/index/gpt-5-5-system-card/) - 🆕 2026-04-23。並列テストタイム計算による高精度バリアント。Pro / Business / Enterprise。
- [GPT-5.5-Cyber](https://openai.com/index/trusted-access-for-cyber/) - 🆕 **2026-04-30**。GPT-5.5 のサイバーセキュリティ特化版。OpenAI の Trusted Access for Cyber (TAC) プログラム経由で、検証済みの防御者・政府・重要インフラ・セキュリティベンダーにのみ提供。一般公開なし。
- [GPT-5.4](https://openai.com/) - 2026-03 公開。1M トークンコンテキスト、高度なコーディング、Computer Use、ツール検索。BenchLM 94、SWE-bench Verified 77.2%、OSWorld 75%（人間ベースライン超え）。
- [GPT-5.4 Pro](https://openai.com/) - GPT-5.4 の高精度バリアント。BenchLM 92。
- [GPT-5.3](https://openai.com/) - 2026 年初頭。GPT-5.3 Instant（会話）と GPT-5.3-Codex（コーディング）を含む。
- [GPT-5.2](https://openai.com/) - 2025-12 公開。最先端の推論・長文脈・視覚。
- [GPT-5](https://openai.com/index/introducing-gpt-5/) - 2025-08 公開。ChatGPT のデフォルトモデル、GPT-4o の後継。マルチモーダル、gpt-5 / mini / nano の 3 段階。
- [GPT-4o](https://openai.com/index/hello-gpt-4o/) - テキスト・視覚・音声をネイティブにサポートする Omni モデル。2026-02 に ChatGPT から退役、API では引き続き利用可能。
- [o3 / o4-mini](https://openai.com/index/introducing-o3-and-o4-mini/) - 思考連鎖推論モデル。2025-04 公開。
- [Codex CLI](https://github.com/openai/codex) - OpenAI が公開したオープンソースのターミナルコーディングエージェント。![GitHub stars](https://img.shields.io/github/stars/openai/codex?style=flat-square)

### Anthropic

- [Claude Opus 4.7](https://www.anthropic.com/news/claude-opus-4-7) - 🆕 2026-04-16 公開。SWE-bench Verified 87.6% の高度なソフトウェアエンジニアリング、視覚強化、能動的なコード検証。`/think xhigh` 推論レベル対応。1M トークンコンテキスト。
- [Claude Opus 4.6](https://www.anthropic.com/) - 2026-02 公開。1M トークン、14.5 時間のタスク完了。Arena 会話リーダーボード首位。
- [Claude Sonnet 4.6](https://www.anthropic.com/news/claude-sonnet-4-6) - 2026-02 公開。フロンティア級コーディングとエージェント性能、1M トークンコンテキスト。
- [Claude Mythos Preview](https://www.anthropic.com/) - 🆕 2026-04 招待制研究プレビュー。BenchLM 99（リーダーボード首位）、SWE-bench Verified 93.9%。Project Glasswing パートナー限定。
- [Claude Opus 4](https://www.anthropic.com/news/claude-4) - 2025-05 公開。
- [Claude Sonnet 4](https://www.anthropic.com/news/claude-4) - 2025-05 公開。バランス重視。
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - ターミナルで動作する Anthropic のエージェント型コーディングツール。Opus 4.7 + `/think xhigh` 対応。
- [Claude Security](https://www.anthropic.com/) - 🆕 **2026-05-01** パブリックベータ。Opus 4.7 駆動の企業向けコードベース脆弱性スキャナ —— 信頼度評価・深刻度・再現手順・推奨修正付きパッチを生成。Enterprise ユーザー向け [claude.ai/security](https://claude.ai/security)。

### Google DeepMind

- [Gemini 3.1 Pro](https://deepmind.google/technologies/gemini/) - 2026-02 公開。BenchLM 94、GPQA Diamond 94.3%（世界記録）、ARC AGI2 77.1%。Google 最強モデル、フラッグシップ価格 `$2/1M tokens`。
- [Gemini 3.1 Flash Live](https://deepmind.google/technologies/gemini/) - 🆕 2026-04。音声アシスタント・対話エージェント向けリアルタイムマルチモーダルストリーミング。低遅延・長文脈。
- [Gemini 3.1 Flash / Flash Lite](https://deepmind.google/technologies/gemini/) - 高スループット用途向けの高速・低コストモデル。
- [Gemini 4 (Open)](https://deepmind.google/technologies/gemini/) - 🆕 2026-04 公開。オープンモデル: 2B / 4B / 26B / 31B。科学推論と文書理解、ローカル展開向け。
- [Gemini 2.5 Pro / Flash](https://deepmind.google/technologies/gemini/) - 2025-06 GA。Thinking モデル + 1M コンテキスト。
- [Gemma 4 31B](https://github.com/google-deepmind/gemma) - 🆕 2026-04。GPQA Diamond 84.3%。デバイス推論用の強力なオープンウェイト代替。![GitHub stars](https://img.shields.io/github/stars/google-deepmind/gemma?style=flat-square)
- [Gemma 3](https://github.com/google-deepmind/gemma) - 前世代のオープンモデルファミリー。
- [Gemini Robotics ER-1.6](https://deepmind.google/) - 🆕 2026-04-14。空間・物理推論を強化したロボティクス AI。Agile Robotics と提携し実機展開。

### Meta

- [Muse Spark](https://ai.meta.com/blog/introducing-muse-spark-msl/) - 🆕 **2026-04-09**。Meta Superintelligence Labs (MSL) の最初のモデル。ネイティブマルチモーダル推論で Meta AI アプリ・スマートグラス・Facebook / Instagram / WhatsApp / Messenger の機能を駆動。
- [Llama 4 Scout](https://llama.meta.com/) - 109B 総 / 17B アクティブ、16 専門家 MoE、10M トークン、マルチモーダル。単一 H100 で動作。
- [Llama 4 Maverick](https://llama.meta.com/) - 400B 総 / 17B アクティブ、128 専門家、1M コンテキスト。マルチモーダルで GPT-4o を上回る。
- [Llama 4 Behemoth](https://llama.meta.com/) - 2T パラメータ（288B アクティブ）。Meta のフロンティア、トップクローズドソースに対抗。
- [Llama 3.3 70B](https://llama.meta.com/) - 強力な命令追従と推論、Llama Community License。

### Mistral AI

- [Mistral Large 3](https://mistral.ai/news/mistral-3) - 675B 総 / 41B アクティブ MoE、256K コンテキスト。マルチモーダルオープンウェイトのフラッグシップ。2025-12 公開。
- [Mistral Medium 3.1](https://mistral.ai/) - 企業向けフロンティア級密モデル。マルチモーダル、128K、80+ プログラミング言語。2025-08 公開。
- [Mistral Small 4](https://mistral.ai/news/mistral-small-4) - 🆕 2026-03 公開。119B 総 / 6B アクティブ。推論・マルチモーダル・コーディングを統合したハイブリッド。
- [Magistral 1.2](https://mistral.ai/) - 🆕 2026 年の推論ファミリー。透過的で多言語の推論。
- [Devstral 2](https://mistral.ai/) - 🆕 2026 年のエージェントコーディングモデル。コーディングエージェントに最適なオープンソース。
- [Codestral](https://mistral.ai/news/codestral) - 22B コード生成モデル、80+ プログラミング言語、32K コンテキスト。2024-05 公開。
- [Pixtral Large](https://mistral.ai/) - 124B マルチモーダル + 1B ビジョンエンコーダ、128K、30+ 高解像度画像処理。
- [Ministral 3B/8B/14B](https://mistral.ai/) - エッジ向けのコンパクトモデル。
- [Mistral Forge](https://mistral.ai/) - 🆕 2026-03 のカスタム LLM 訓練プラットフォーム。

### DeepSeek 🇨🇳

- [DeepSeek-V4-Pro](https://api-docs.deepseek.com/news/news260424) - 🆕 **2026-04-24**。1.6T 総 / 49B アクティブ MoE、1M トークン。MIT。エージェント能力・世界知識・推論でリード。オープンソースベンチマーク首位。
- [DeepSeek-V4-Flash](https://api-docs.deepseek.com/news/news260424) - 🆕 2026-04-24。284B 総 / 13B アクティブ MoE、1M コンテキスト。MIT。コスト効率版。
- [DeepSeek-V3.2](https://www.deepseek.com/) - 2025-12 公開。671B MoE、V3.2 Speciale 推論強化版あり。
- [DeepSeek-R2](https://www.deepseek.com/) - 2026 年の推論モデル。R1 後継、GPT-5・Gemini 3 Pro と競合。
- [DeepSeek-R1](https://www.deepseek.com/) - 2025-01 公開、思考連鎖推論モデル。
- [DeepSeek-Coder-V2](https://github.com/deepseek-ai/DeepSeek-Coder-V2) - GPT-4 と互角のコード生成モデル。![GitHub stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-Coder-V2?style=flat-square)

### Alibaba (Qwen) 🇨🇳

- [Qwen3.6-27B](https://qwen.ai/blog?id=qwen3.6-27b) - 🆕 **2026-04-22**。27B 密マルチモーダル。オープン化。エージェントコーディング + 思考文脈保持。
- [Qwen3.6-Max-Preview](https://qwen.ai/) - 🆕 **2026-04-18**。プロプライエタリのフロンティアプレビュー。1M コンテキスト、中国モデルでコーディング首位級。
- [Qwen3.6-35B-A3B](https://qwen.ai/blog?id=qwen3.6-35b-a3b) - 🆕 **2026-04-15**。MoE 35B 総 / 3B アクティブ。Apache 2.0。安定性・実用性の改善。
- [Qwen3.6-Plus](https://qwen.ai/) - 🆕 **2026-04-02**。プロプライエタリのフラッグシップ。トークンあたりの価値が高く、長文脈・ツール呼び出し・エージェント挙動が良好。
- [Tianma (天馬) AI](https://www.alibabacloud.com/) - 🆕 **2026-04-27** ベータ。アリババの画像から動画への生成モデル。キャラクター一貫性と動きの品質が高い。
- [Qwen3.5 Max Pro](https://qwen.ai/) - 2026-04。高性能フラッグシップ。
- [Qwen3.5 Omni Plus](https://qwen.ai/) - 2026-04。テキスト + 画像入力を統合した全モーダル。
- [Qwen3-Max-Thinking](https://qwen.ai/) - アリババ最強の Thinking モデル。1T+ パラメータ。
- [Qwen3.5-Omni](https://qwen.ai/) - 2026-03。完全全モーダル: 言語・視覚・音・動作。113 言語の音声認識、256K コンテキスト。
- [Qwen3-Coder-Next](https://qwen.ai/) - 2026-02。オープンウェイトのコーディングエージェントモデル、MoE 80B 総 / 3B アクティブ。
- [Qwen3 235B-A22B](https://qwen.ai/) - 二重モード推論 MoE。数学・コード・常識推論に強い。
- [Qwen2.5 Coder 32B](https://github.com/QwenLM/Qwen2.5-Coder) - トップクラスのオープンソースコーディングモデル。![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen2.5-Coder?style=flat-square)

### xAI (Grok)

- [Grok 4.3 Beta](https://x.ai/) - 🆕 2026-04。推論・コーディングベンチマーク強化。[`2026.4` ベンチマークスナップショット](https://benchlm.ai/) 参照。
- [Grok 4.20](https://x.ai/) - 2026-02。マルチエージェントシステム（Heavy モードで標準 4 + 専門 16）、2M コンテキスト。
- [Grok 4 / 4 Heavy](https://x.ai/) - 2025-07 公開。3T パラメータ。
- [Grok 3 / 3 Mini](https://x.ai/) - 2025-02。"Think Mode" 推論モデルの最初の世代。

### Microsoft (Phi)

- [Phi-4-reasoning-vision-15B](https://azure.microsoft.com/en-us/products/phi) - 🆕 2026-03。15B マルチモーダル + 選択的思考連鎖推論。エッジ展開可能。
- [Phi-4](https://azure.microsoft.com/en-us/products/phi) - 14B SLM、ずっと大きいモデルに匹敵する推論力。MIT。
- [Phi-4-mini](https://azure.microsoft.com/en-us/products/phi) - 3.8B 密モデル。128K コンテキスト。推論・数学・コーディング・関数呼び出しで秀逸。
- [Phi-4-multimodal](https://azure.microsoft.com/en-us/products/phi) - 5.6B 初の Phi マルチモーダル（音声 + 視覚 + テキスト）。

### Cohere

- [Command A](https://cohere.com/) - 🆕 2026-04 公開。111B オープンウェイト、256K コンテキスト。エージェント・多言語・コーディング志向。
- [Command R+](https://cohere.com/) - エンタープライズ RAG モデル、128K コンテキスト、10 言語、引用付き grounded generation。
- [Command R](https://cohere.com/) - 経済的な RAG モデル。

### Baidu (ERNIE / 文心) 🇨🇳

- [ERNIE 5.0](https://yiyan.baidu.com/) - 🆕 2026-01 公開。2.4T MoE（1 クエリで <3% 活性化）。ネイティブ全モーダル。LMArena で中国モデル首位。
- [ERNIE 4.5](https://yiyan.baidu.com/) - 2025 年公開のマルチモーダル前任者。中国語・推論に強い。

### Zhipu AI / Z.ai (GLM) 🇨🇳

- [GLM-5.1](https://z.ai/blog/glm-5.1) - 🆕 **2026-04-07**。744B MoE / 40B アクティブ、200K コンテキスト。MIT ライセンス。SWE-Bench Pro で首位。**完全に華為昇騰で訓練**（NVIDIA 不使用）。
- [GLM-5 Reasoning](https://z.ai/) - 🆕 2026-04。BenchLM 85 —— **オープンソース最高スコア**。SWE-Bench Pro で GPT-5.4 と Claude Opus 4.6 を上回る。
- [GLM-5V-Turbo](https://z.ai/) - 🆕 2026-04。ネイティブマルチモーダルエージェント —— 視覚・動画クリップ・テキスト入力。コスト性能バランス。
- [GLM-5](https://z.ai/) - 2026-02 公開。744B パラメータ、先進的なエージェント知性。MIT。
- [GLM-4.7](https://z.ai/) - 2025 年末公開。SWE-Bench で Claude Opus 4 と互角。

### MiniMax 🇨🇳

- [MiniMax-M2.7 (オープンウェイト)](https://www.minimax.io/) - 🆕 2026-04。1M+ の超長文脈ウィンドウ。コーディング・エージェントタスクでトップクラス。
- [MiniMax-M1-80k](https://www.minimax.io/) - オープンウェイトのハイブリッドアテンション推論モデル。456B パラメータ、1M トークン。
- [Hailuo AI (動画)](https://hailuoai.video/) - テキスト/画像から動画への生成、AI アバター・ナレーション・キャラクター一貫性。
- [Kilo Code 統合](https://www.minimax.io/) - 🆕 MiniMax は新しい AI コーディングエディタ Kilo Code のデフォルトモデル。

### Moonshot AI (Kimi) 🇨🇳

- [Kimi K2.6](https://kimi.ai/) - 🆕 **2026-04-20~21**。1T MoE / 32B アクティブ、256K コンテキスト。コーディング強化、長期マルチステップ実行、**最大 1,000 体協調エージェント群**。`thinking.keep="all"` 永続推論対応。OpenClaw v2026.4.20+ のデフォルト。
- [Kimi K2.5](https://kimi.ai/) - 2026 年 1~2 月。1T 総 / 32B アクティブ MoE。ネイティブマルチモーダル、最大 100 並列子エージェント。オープンソース。⚠️ 2026-05-25 サポート終了 —— K2.6 へ移行を。
- [Kimi Code](https://kimi.ai/) - K2.5/K2.6 駆動のプレミアムコーディング層、ターミナル開発者ワークフロー向け。

### ByteDance (Doubao / 豆包) 🇨🇳

- [Doubao-Seed-2.0 Pro](https://seed.bytedance.com/) - 🆕 2026-02 公開。フロンティア推論と複雑エージェント。GPT-5.2 と互角でコストは約 90% 低減。
- [Doubao-Seed-2.0 Lite](https://seed.bytedance.com/) - 🆕 一般生産負荷向け。
- [Doubao-Seed-2.0 Code](https://seed.bytedance.com/) - 🆕 ソフトウェア開発: コード生成・デバッグ・レビュー。
- [BAGEL](https://github.com/bytedance-seed/BAGEL) - 🆕 オープンソースのマルチモーダル基盤モデル、テキスト・画像・動画の理解と生成を統合。

### Amazon (Nova)

- [Nova 2 Pro](https://aws.amazon.com/nova/) - 🆕 Amazon の最強推論モデル。テキスト・画像・動画・音声入力。エージェントコーディングと長期計画。
- [Nova 2 Lite](https://aws.amazon.com/nova/) - 🆕 1M コンテキスト + "thinking effort" 調整。
- [Nova 2 Sonic](https://aws.amazon.com/nova/) - 🆕 リアルタイム音声対音声モデル。1M コンテキスト、多言語。
- [Nova Act](https://aws.amazon.com/nova/) - 🆕 ブラウザ Web タスクエージェントサービス（Nova 2 Lite 駆動）。
- [Nova Forge](https://aws.amazon.com/nova/) - 🆕 カスタム Nova モデル訓練サービス。

### NVIDIA (Nemotron)

- [Nemotron 3 Ultra](https://developer.nvidia.com/nemotron) - 🆕 2026-03（GTC）。フロンティア級推論、Blackwell で 5 倍スループット。
- [Nemotron 3 Super](https://developer.nvidia.com/nemotron) - 🆕 2026-03。120B 総 / 12B アクティブ、1M コンテキスト。
- [Nemotron 3 Nano](https://developer.nvidia.com/nemotron) - 経済的な Transformer-Mamba ハイブリッド MoE。
- [Nemotron 3 Nano Omni](https://blogs.nvidia.com/blog/nemotron-3-nano-omni-multimodal-ai-agents/) - 🆕 **2026-04-28**。30B-A3B ハイブリッド MoE、ネイティブマルチモーダル。同等オープン omni モデル比 9 倍スループット。MMlongbench-Doc / OCRBenchV2 / WorldSense / DailyOmni / VoiceBench で 6 リーダーボード首位。

### Tencent (Hunyuan) 🇨🇳

- [Hunyuan Hy3 Preview](https://hy.tencent.com/research/hy3) - 🆕 **2026-04-23**。295B 総 / 21B アクティブ MoE、256K コンテキスト。GitHub / Hugging Face / ModelScope / GitCode 同時オープンソース化。"Fast-slow thinking fusion" アーキテクチャ、推論効率 40% 改善。vLLM と SGLang 対応。元宝 / CodeBuddy / QQ / 騰訊文档に統合済み。OpenRouter で無料プレビュー中。![GitHub stars](https://img.shields.io/github/stars/Tencent-Hunyuan/Hunyuan-A13B?style=flat-square)

### Apple

- [Apple Foundation Models (AFM)](https://machinelearning.apple.com/research/introducing-apple-foundation-models) - Apple Intelligence の中核となるオンデバイス（~3B）+ サーバーモデル。プライバシー優先、オフライン対応。
- [OpenELM](https://machinelearning.apple.com/research/openelm) - Apple Silicon オンデバイス向けオープンソース効率言語モデル（270M~3B）。

### Samsung

- [Samsung Gauss 2.3](https://www.samsung.com/) - 🆕 Galaxy S26 用オンデバイス AI。Gauss 2.3 Think + Gauss O Flash の 2 バリアント。エージェント機能対応。

### Inflection AI

- [Inflection 2.5 / Pi](https://inflection.ai/) - 共感的会話 AI、感情知能と人間中心インタラクションで知られる。

### 01.AI 🇨🇳

- [Yi-Lightning](https://www.01.ai/) - MoE、RTX 4090 で 200+ tokens/s。中英多言語に強く、Apache 2.0。2024-10 公開。

### 中国科学院 🇨🇳

- [ScienceOne 100 / 磐石100](https://english.cas.cn/newsroom/cas-in-media/202604/t20260429_1158251.shtml) - 🆕 **2026-04-28~29**。中国科学院の科学研究 AI 系統。コアの "ScienceOne" 基盤モデル + 文献コンパス + 革新評価エンジン + 2,000+ ツールエージェントファクトリー。数学・物理・生物・材料・天文・宇宙・地球科学を網羅。50+ CAS 研究所、100+ 研究シナリオで使用。

---

## 🎨 マルチモーダルと生成 AI

*画像・動画・音声・音楽の生成と編集のためのツールとモデル。*

### 画像生成

- [ChatGPT Images 2.0](https://openai.com/) - 🆕 2026-04。無料層対応。ディテール・テキスト理解・反復編集が向上。
- [gpt-image-2](https://openai.com/) - 🆕 OpenAI 最新の画像生成 API。2K/4K 解像度ヒント対応。OpenClaw v2026.4.21 のデフォルト。
- [DALL·E 3](https://openai.com/dall-e-3) - ChatGPT に統合された OpenAI のテキスト → 画像モデル。
- [Midjourney V7](https://www.midjourney.com/) - フォトリアル・芸術風スタイルの第一線。
- [Stable Diffusion 3.5](https://stability.ai/) - 一貫性・プロンプト追従が改善されたオープンソース画像生成。
- [Flux](https://github.com/black-forest-labs/flux) - 💤 **Stale**（2025-07 以降更新なし）。Black Forest Labs のオープンソースモデル。![GitHub stars](https://img.shields.io/github/stars/black-forest-labs/flux?style=flat-square)
- [Ideogram 3.0](https://ideogram.ai/) - 画像内のテキスト描画とデザイン志向の生成に強い。
- [Gemini 3 Pro Image](https://deepmind.google/technologies/gemini/) - Gemini 内のネイティブ画像生成。
- [Recraft V3](https://www.recraft.ai/) - プロのデザイナー向け AI 画像生成。
- [Seedance 2.0](https://seed.bytedance.com/) - 🇨🇳 🆕 ByteDance の次世代画像/アニメーション生成 API。

### 動画生成

- [Kling VIDEO 3.0](https://kling.ai/) - 🇨🇳 🆕 快手製。リアルな動き・リップシンク・音声同期付きナラティブ。最大 15 秒。
- [Hailuo AI](https://hailuoai.video/) - 🇨🇳 🆕 MiniMax 製。テキスト/画像から動画、AI アバター・ナレーション・キャラクター一貫性。
- [Veo 2](https://deepmind.google/technologies/veo/) - 🆕 Google DeepMind の高忠実度動画生成。
- [Runway Gen-4](https://runwayml.com/) - 🆕 プロ向け動画生成・編集、キャラクター・スタイル一貫性。
- [Pika 2.0](https://pika.art/) - 🆕 シーン・エフェクト制御付きクリエイティブ動画生成。
- [LTX Studio](https://ltx.studio/) - 🆕 AI 駆動シネマティック動画作成プラットフォーム。
- [Tianma (天馬) AI](https://www.alibabacloud.com/) - 🇨🇳 🆕 **2026-04-27** ベータ。アリババの画像→動画モデル。
- [Sora](https://openai.com/sora/) - ⚠️ *2026-04 サービス終了*。OpenAI のテキスト→動画モデル、コストと戦略転換のため停止。

### 音声・音楽

- [ElevenLabs](https://elevenlabs.io/) - AI 音声合成・クローン・対話 AI のリーダー。
- [Suno V4](https://suno.com/) - 🆕 高品質ボーカル・楽器付きの AI 音楽生成。
- [Udio](https://www.udio.com/) - 🆕 商用品質の音楽生成。
- [OpenAI Audio Models](https://openai.com/) - GPT-4o 内のネイティブ音声理解・生成。
- [Stability Audio](https://stability.ai/) - オープンソース音声・音楽生成。
- [Bark](https://github.com/suno-ai/bark) - 💤 **Stale**（2024-08 以降更新なし）。オープンソースのテキスト→音声モデル。![GitHub stars](https://img.shields.io/github/stars/suno-ai/bark?style=flat-square)

---

## 🔗 エージェントプロトコルと標準

*エージェントの相互運用性・ツールアクセス・クロスプラットフォーム通信を可能にするオープン標準。*

### Model Context Protocol (MCP)

- [MCP Specification](https://modelcontextprotocol.io/) - 🆕 "AI 用の USB-C" —— Anthropic 製、LLM をツール・データソースに接続するオープンプロトコル。2025-12 に Linux Foundation 傘下の Agentic AI Foundation へ寄贈。
- [MCP Servers](https://github.com/modelcontextprotocol/servers) - MCP サーバーの公式リファレンス実装集。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat-square)
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - 公式 TypeScript SDK。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat-square)
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - 公式 Python SDK。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat-square)
- [mcp.so](https://mcp.so/) - 🆕 MCP サーバー・ツールのコミュニティディレクトリ。
- [mcp-gateway](https://github.com/Zijian-Ni/mcp-gateway) - MCP 接続のルーティングと管理を行うゲートウェイ。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/mcp-gateway?style=flat-square)

### Agent-to-Agent Protocol (A2A)

- [A2A Protocol](https://github.com/google/A2A) - 🆕 Google が主導するエージェント間通信のオープン標準。フレームワーク不問でエージェントの発見・委譲・協調を可能にする。Linux Foundation 統治、150+ パートナー。![GitHub stars](https://img.shields.io/github/stars/google/A2A?style=flat-square)
- [A2A Course (DeepLearning.AI)](https://www.deeplearning.ai/short-courses/a2a-the-agent2agent-protocol/) - 🆕 A2A でマルチエージェントシステムを構築する無料コース。

### その他の標準

- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - 🆕 [2026-04-15 大型アップデート](https://openai.com/index/the-next-evolution-of-the-agents-sdk/): ネイティブサンドボックス実行、第一級 MCP 統合、サブエージェント / handoff パターン、Codex 風ファイルシステムツール。プロダクション級マルチエージェントワークフロー。![GitHub stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat-square)
- [Agentic AI Foundation](https://www.linuxfoundation.org/) - 🆕 Anthropic、Block、OpenAI が共同設立した Linux Foundation のオープンエージェント標準統治基金。

---

## 🏗️ エージェントフレームワーク

*自律 AI エージェントを構築するためのフレームワークとライブラリ。*

- [LangChain](https://github.com/langchain-ai/langchain) - LLM を使った文脈認識推論アプリの基盤。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)
- [LangGraph](https://github.com/langchain-ai/langgraph) - エージェントを状態を持つマルチアクターのグラフとしてモデル化。v0.3.19（2026-04-27）: プリビルトエージェントが `langgraph-prebuilt` に分離 —— Supervisor / Swarm / LangMem / Trustcall。エージェントワークフローのプロダクション標準。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square)
- [CrewAI](https://github.com/crewAIInc/crewAI) - ロールプレイ型自律エージェントチームのオーケストレーションフレームワーク。![GitHub stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat-square)
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/) - 🆕 AutoGen + Semantic Kernel を統合した新フレームワーク。マルチエージェント + エンタープライズ機能。2026 Q1 GA。
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft のマルチエージェント会話フレームワーク（Microsoft Agent Framework に統合）。![GitHub stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat-square)
- [Google Agent Development Kit (ADK)](https://github.com/google/adk-python) - 🆕 Gemini + Vertex AI と密接に統合したモジュラーフレームワーク。階層エージェント構成。![GitHub stars](https://img.shields.io/github/stars/google/adk-python?style=flat-square)
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - 🆕 [2026-04-15 進化](https://openai.com/index/the-next-evolution-of-the-agents-sdk/) —— ネイティブサンドボックス、MCP ネイティブ、サブエージェント handoff、Codex 風ファイル操作。プロダクション級マルチエージェント。![GitHub stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat-square)
- [MetaGPT](https://github.com/geekan/MetaGPT) - 🇨🇳 LLM に SOP ソフトウェアチームの役割（PM / アーキテクト / エンジニア）を割り当てる多エージェント。![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat-square)
- [Mastra](https://github.com/mastra-ai/mastra) - 🆕 TypeScript 優先のエージェントフレームワーク、ワークフロー駆動 + オブザーバビリティ内蔵。![GitHub stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=flat-square)
- [AgentGPT](https://github.com/reworkd/AgentGPT) - 📦 **Archived**（2025-04）。ブラウザでエージェントを構成・展開。第一波の代表、歴史的参照のみ。![GitHub stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=flat-square)
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - LLM でタスクを作成・優先順位付け・実行する AI タスクマネジメント。![GitHub stars](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=flat-square)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - 💤 **Stale**（2025-01 以降更新なし）。オープンソース自律エージェントフレームワーク。![GitHub stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=flat-square)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - LLM 技術をアプリに統合。C# / Python / Java。![GitHub stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=flat-square)
- [Phidata (Agno)](https://github.com/phidatahq/phidata) - メモリ・知識・ツール・推論つきマルチモーダルエージェント。![GitHub stars](https://img.shields.io/github/stars/phidatahq/phidata?style=flat-square)
- [DSPy](https://github.com/stanfordnlp/dspy) - "プロンプトを書くのではなくプログラミングする" 言語モデルフレームワーク。![GitHub stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square)
- [OpenClaw](https://github.com/openclaw/openclaw) - 🆕 スキル・メモリ・マルチチャネルメッセージング・Dreaming（3 段階メモリ統合）・Canvas/A2UI・ACP コーディング harness 統合・Standing Orders を備えた個人向け AI エージェントプラットフォーム。v2026.4.21 で Opus 4.7・Kimi K2.6・`/think xhigh` をサポート。2026-04 に GitHub star で Linux を超えたとされる。![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat-square)
- [Dify](https://github.com/langgenius/dify) - 🇨🇳 ビジュアルエージェントビルダー付きオープンソース LLM アプリ開発プラットフォーム。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Haystack Agents](https://github.com/deepset-ai/haystack) - エージェント型パイプラインのエンドツーエンド LLM フレームワーク。![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square)
- [Vellum AI](https://www.vellum.ai/) - 🆕 プロダクション級プロプライエタリ SaaS：プロンプト構築・評価・バージョニング・オブザーバビリティ。
- [FastAgency](https://github.com/airtai/fastagency) - 🆕 高速推論 + プロダクションスケーリングフレームワーク。![GitHub stars](https://img.shields.io/github/stars/airtai/fastagency?style=flat-square)
- [Rasa](https://github.com/RasaHQ/rasa) - 強力な意図認識と対話管理のオープンソース対話 AI。![GitHub stars](https://img.shields.io/github/stars/RasaHQ/rasa?style=flat-square)
- [Lindy](https://www.lindy.ai/) - 🆕 ビジネスユーザー向けノーコードエージェント、ビジュアルワークフロービルダー。
- [Octomind](https://github.com/muvon/octomind) - 🆕 Rust ベースのオープンソース AI エージェントランタイム。モデル不問（13+）、コミュニティ製の専門エージェント（開発・医療・法律・DevOps）、ランタイム自己拡張対応 MCP、ゼロコンフィグ。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/muvon/octomind?style=flat-square)
- [Microsoft AI Agent Governance Toolkit](https://www.helpnetsecurity.com/2026/04/03/microsoft-ai-agent-governance-toolkit/) - 🆕 **2026-04-03**。LangChain や AutoGen などフレームワーク横断でランタイムセキュリティポリシーを強制するオープンソースツールキット。

---

## 🛠️ エージェント IDE とビジュアルビルダー

*コードを書かずに（または最小限で）エージェントワークフローを設計・デバッグ・出荷するためのビジュアル環境。*

- [LangGraph Studio](https://www.langchain.com/langgraph) - LangGraph エージェントのビジュアルデバッガとトレース検査。状態のステップ実行、ターンの再生、メッセージの途中編集が可能。
- [Dify](https://github.com/langgenius/dify) - 🇨🇳 ドラッグ&ドロップのエージェントワークフロービルダー付きオープンソース LLM アプリ開発。プロダクション利用が主流。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Agenta](https://github.com/agenta-ai/agenta) - 🆕 プロンプトプレイグラウンド・プロンプト管理・評価実行・オブザーバビリティを統合したオープンソース LLMOps プラットフォーム。![GitHub stars](https://img.shields.io/github/stars/agenta-ai/agenta?style=flat-square)
- [Vellum AI](https://www.vellum.ai/) - クローズドソース SaaS。
- [Cozeloop](https://github.com/coze-dev/cozeloop) - 🇨🇳 🆕 ByteDance の Coze チームによるオープンソースのエージェント最適化プラットフォーム。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/coze-dev/cozeloop?style=flat-square)
- [Restack](https://www.restack.io/) - 永続化エージェントランタイム + ビジュアルワークフローエディタ（Temporal 風 replay）。オープン例: [restackio/examples-python](https://github.com/restackio/examples-python)。
- [Bisheng](https://github.com/dataelement/bisheng) - 🇨🇳 オープンエンタープライズ LLM DevOps プラットフォーム: ワークフローエディタ・RAG・エージェントオーケストレーション・ファインチューニング・データセット管理・オブザーバビリティ。Apache 2.0。![GitHub stars](https://img.shields.io/github/stars/dataelement/bisheng?style=flat-square)
- [n8n](https://github.com/n8n-io/n8n) - エージェントキャンバスとして人気の汎用ビジュアルワークフロー自動化 —— 400+ 連携 + ネイティブ AI ノード。Fair-code ライセンス。![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat-square)

---

## 🧠 エージェントメモリ

*エージェントに永続メモリと文脈管理を与えるシステム。*

- [Letta (MemGPT)](https://github.com/letta-ai/letta) - 長期メモリとカスタムツールを持つ LLM サービスを作成。![GitHub stars](https://img.shields.io/github/stars/letta-ai/letta?style=flat-square)
- [Mem0](https://github.com/mem0ai/mem0) - LLM アプリ用の自己改善型メモリ層。![GitHub stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square)
- [Zep](https://github.com/getzep/zep) - AI アシスタント・エージェント向け長期メモリ。![GitHub stars](https://img.shields.io/github/stars/getzep/zep?style=flat-square)
- [agent-memory](https://github.com/Zijian-Ni/agent-memory) - セッション横断の文脈永続化を実現する軽量エージェントメモリフレームワーク。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/agent-memory?style=flat-square)
- [LangMem](https://github.com/langchain-ai/langmem) - LangChain エージェント用長期メモリライブラリ。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langmem?style=flat-square)
- [Motorhead](https://github.com/getmetal/motorhead) - 💤 **Stale**（2025-07 以降更新なし）。LLM 用メモリ・文脈管理サーバー。![GitHub stars](https://img.shields.io/github/stars/getmetal/motorhead?style=flat-square)
- [ChromaDB](https://github.com/chroma-core/chroma) - AI ネイティブのオープンソース埋め込みデータベース。![GitHub stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square)
- [Cognee](https://github.com/topoteretes/cognee) - グラフ + LLM + ベクトル検索による決定論的 LLM 出力。![GitHub stars](https://img.shields.io/github/stars/topoteretes/cognee?style=flat-square)
- [LangGraph Memory](https://github.com/langchain-ai/langgraph) - 🆕 状態管理エージェントワークフロー用の組み込み永続化とチェックポイント。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square)
- [Graphiti](https://github.com/getzep/graphiti) - 🆕 時間意識を備えたエージェントメモリ用知識グラフ。![GitHub stars](https://img.shields.io/github/stars/getzep/graphiti?style=flat-square)
- [Claude Managed Agents Memory](https://platform.claude.com/docs/en/release-notes/overview) - 🆕 **2026-04-23**（パブリックベータ）。Claude Managed Agents 用 Anthropic 永続メモリ機能。読み書きメモリストアをエージェントのファイルシステムにマウントしてセッション間で情報を保持。

---

## 🔌 ツールと API 連携

*エージェントを外部サービス・API に接続するプロトコルとツール。*

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol/servers) - AI モデルを外部ツール・データソースに接続するオープンプロトコル。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat-square)
- [mcp-gateway](https://github.com/Zijian-Ni/mcp-gateway) - MCP プロトコル接続のルーティングと管理を行うゲートウェイ。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/mcp-gateway?style=flat-square)
- [Composio](https://github.com/ComposioHQ/composio) - AI エージェント向け統合プラットフォーム —— マネージド認証付き 150+ ツール。![GitHub stars](https://img.shields.io/github/stars/ComposioHQ/composio?style=flat-square)
- [Toolhouse](https://toolhouse.ai/) - AI ツール利用のクラウドインフラ —— ツールの保存・管理・実行。
- [LangChain Tools](https://github.com/langchain-ai/langchain) - LangChain エコシステム内の広範なツール統合。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)
- [Arcade AI](https://github.com/ArcadeAI/arcade-ai) - AI エージェント・アシスタント用ツール呼び出しプラットフォーム。![GitHub stars](https://img.shields.io/github/stars/ArcadeAI/arcade-ai?style=flat-square)
- [E2B](https://github.com/e2b-dev/e2b) - AI エージェント用オープンソースクラウドランタイム —— セキュアなサンドボックス環境。![GitHub stars](https://img.shields.io/github/stars/e2b-dev/e2b?style=flat-square)
- [Browser Use](https://github.com/browser-use/browser-use) - AI エージェント用のブラウザ自動化。![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square)
- [Firecrawl](https://github.com/mendableai/firecrawl) - 🆕 ウェブサイトを LLM-ready なデータに変換。![GitHub stars](https://img.shields.io/github/stars/mendableai/firecrawl?style=flat-square)
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - 🆕 LLM フレンドリーなオープンソースクローラ。![GitHub stars](https://img.shields.io/github/stars/unclecode/crawl4ai?style=flat-square)
- [Stagehand](https://github.com/browserbase/stagehand) - 🆕 Browserbase 製の AI 駆動ブラウザ自動化フレームワーク。![GitHub stars](https://img.shields.io/github/stars/browserbase/stagehand?style=flat-square)
- [AgentQL](https://www.agentql.com/) - 🆕 AI エージェントが意味的にウェブページと対話するためのクエリ言語。
- [StackOne](https://www.stackone.com/) - 🆕 HR・CRM・ATS プラットフォーム横断の統一 API。
- [The Colony](https://thecolony.cc) - ⚠️ **Unverified**。エージェント間のソーシャルネットワークと REST API を謳う。組織と SDK リポジトリは <30 日、すべて 0~2 star、単独メンテナで、同じ申請が 15+ awesome リストに並列投稿された —— 可視性のための掲載のみ、利用前に評価のこと。![GitHub stars](https://img.shields.io/github/stars/TheColonyCC/colony-sdk-python?style=flat-square)

---

## 🧪 エージェントサンドボックスと計算分離

*エージェントが生成したコードや shell コマンドをホストを危険にさらさず実行するセキュアなランタイム。エージェントを自由に動かす段階で必須となる重要インフラ。*

- [E2B](https://github.com/e2b-dev/E2B) - AI 生成コード用のオープンソースセキュアクラウドサンドボックス。OpenAI Agents SDK の実行層に採用。![GitHub stars](https://img.shields.io/github/stars/e2b-dev/E2B?style=flat-square)
- [Daytona](https://github.com/daytonaio/daytona) - 🆕 AI 生成コードを実行するセキュアで弾力的なインフラ。エージェントタスク毎に隔離された開発環境を起動。AGPL-3.0。![GitHub stars](https://img.shields.io/github/stars/daytonaio/daytona?style=flat-square)
- [Modal](https://modal.com/) - エージェント計算・GPU ジョブ・サンドボックス Python に人気のサーバーレスクラウド。`modal-client` が公式 SDK。![GitHub stars](https://img.shields.io/github/stars/modal-labs/modal-client?style=flat-square)
- [Microsandbox](https://github.com/superradcompany/microsandbox) - 🆕 AI エージェント向けローカル・プログラマブル microVM サンドボックス —— クラウド非依存でローカル機にセキュアなコード実行。![GitHub stars](https://img.shields.io/github/stars/superradcompany/microsandbox?style=flat-square)
- [SandboxFusion](https://github.com/bytedance/SandboxFusion) - 🇨🇳 ByteDance のエージェント・モデル評価パイプライン用多言語コード実行サンドボックス。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/bytedance/SandboxFusion?style=flat-square)
- [Northflank](https://northflank.com/) - エージェントランタイムバックエンドとして使われる汎用コンテナ PaaS（タスク毎エフェメラル環境 + GPU プール）。
- [Firecracker](https://github.com/firecracker-microvm/firecracker) - E2B、Daytona、ほとんどのエージェントサンドボックスの基盤となる microVM カーネル。自前のサンドボックスを組むときの基本要素。![GitHub stars](https://img.shields.io/github/stars/firecracker-microvm/firecracker?style=flat-square)

---

## 🛡️ エージェントセキュリティ

*プロンプトインジェクション・データ漏洩・悪用から AI エージェントを守るツールとフレームワーク。*

- [prompt-firewall](https://github.com/Zijian-Ni/prompt-firewall) - LLM プロンプト用ファイアウォール —— インジェクション攻撃を検出・遮断。![GitHub stars](https://img.shields.io/github/stars/Zijian-Ni/prompt-firewall?style=flat-square)
- [LLM Guard](https://github.com/protectai/llm-guard) - LLM 対話用のセキュリティツールキット —— 入出力スキャナ。![GitHub stars](https://img.shields.io/github/stars/protectai/llm-guard?style=flat-square)
- [Rebuff](https://github.com/protectai/rebuff) - 📦 **Archived**（2024-08）。自己強化型プロンプトインジェクション検出器。歴史的参照のみ。![GitHub stars](https://img.shields.io/github/stars/protectai/rebuff?style=flat-square)
- [Guardrails AI](https://github.com/guardrails-ai/guardrails) - LLM 出力の検証・修正にガードレールを追加。![GitHub stars](https://img.shields.io/github/stars/guardrails-ai/guardrails?style=flat-square)
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) - LLM ベース対話システムにプログラマブルガードレールを追加するツールキット。![GitHub stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails?style=flat-square)
- [Vigil](https://github.com/deadbits/vigil-llm) - 💤 **Stale**（2024-01 以降更新なし）。LLM セキュリティスキャナ。![GitHub stars](https://img.shields.io/github/stars/deadbits/vigil-llm?style=flat-square)
- [Lakera Guard](https://www.lakera.ai/) - エンタープライズ級 AI セキュリティプラットフォーム。
- [Garak](https://github.com/NVIDIA/garak) - NVIDIA の LLM 脆弱性スキャナ。![GitHub stars](https://img.shields.io/github/stars/NVIDIA/garak?style=flat-square)
- [Invariant Guardrails](https://github.com/invariantlabs-ai/invariant) - 🆕 AI エージェント用ランタイムガードレール —— ポリシー強制と安全チェック。![GitHub stars](https://img.shields.io/github/stars/invariantlabs-ai/invariant?style=flat-square)
- [Prompt Armor](https://promptarmor.com/) - 🆕 リアルタイム検出のエンタープライズプロンプトインジェクション保護。
- [Descope MCP Auth](https://www.descope.com/) - 🆕 MCP サーバーセキュリティ用の認証・認可レイヤ。
- [AgentDojo](https://github.com/ethz-spylab/agentdojo) - 🆕 ETH チューリッヒの研究ベンチマーク。ツール使用 LLM エージェントへのプロンプトインジェクション攻撃と防御を評価。![GitHub stars](https://img.shields.io/github/stars/ethz-spylab/agentdojo?style=flat-square)
- [ModelScan](https://github.com/protectai/modelscan) - ML モデル重みファイル（Pickle、PyTorch、TF）のシリアライズ攻撃をスキャン。![GitHub stars](https://img.shields.io/github/stars/protectai/modelscan?style=flat-square)
- [PyRIT](https://github.com/Azure/PyRIT) - Microsoft の生成 AI 用自動レッドチームフレームワーク。![GitHub stars](https://img.shields.io/github/stars/Azure/PyRIT?style=flat-square)

---

## 🔍 RAG とナレッジ

*エージェント用の検索拡張生成と知識管理システム。*

- [LlamaIndex](https://github.com/run-llama/llama_index) - LLM アプリ用データフレームワーク —— プライベートデータの取り込み・構造化・アクセス。![GitHub stars](https://img.shields.io/github/stars/run-llama/llama_index?style=flat-square)
- [LangChain Retrievers](https://github.com/langchain-ai/langchain) - LangChain 内のリトリーバとドキュメントローダー集合。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square)
- [Haystack](https://github.com/deepset-ai/haystack) - エンドツーエンド RAG。![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square)
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - ドキュメント前処理と抽出。![GitHub stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured?style=flat-square)
- [Weaviate](https://github.com/weaviate/weaviate) - オープンソースベクトルデータベース。![GitHub stars](https://img.shields.io/github/stars/weaviate/weaviate?style=flat-square)
- [Qdrant](https://github.com/qdrant/qdrant) - Rust 製の高性能ベクトル検索。![GitHub stars](https://img.shields.io/github/stars/qdrant/qdrant?style=flat-square)
- [Milvus](https://github.com/milvus-io/milvus) - 大規模ベクトルデータベース。![GitHub stars](https://img.shields.io/github/stars/milvus-io/milvus?style=flat-square)
- [Pinecone](https://www.pinecone.io/) - マネージドベクトルデータベース SaaS。
- [Chroma](https://github.com/chroma-core/chroma) - AI ネイティブオープンソースベクトルデータベース。![GitHub stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square)
- [Vanna](https://github.com/vanna-ai/vanna) - 📦 **Archived**（2026-02）。RAG-for-SQL: 自然言語でデータベースと対話。![GitHub stars](https://img.shields.io/github/stars/vanna-ai/vanna?style=flat-square)
- [LightRAG](https://github.com/HKUDS/LightRAG) - 🇨🇳 香港大学 HKUDS のグラフ型 RAG。![GitHub stars](https://img.shields.io/github/stars/HKUDS/LightRAG?style=flat-square)
- [Docling](https://github.com/DS4SD/docling) - IBM のドキュメント変換ツール（PDF / DOCX / HTML 等）。![GitHub stars](https://img.shields.io/github/stars/DS4SD/docling?style=flat-square)
- [Kotaemon](https://github.com/Cinnamon/kotaemon) - オープンソース RAG UI。![GitHub stars](https://img.shields.io/github/stars/Cinnamon/kotaemon?style=flat-square)
- [R2R](https://github.com/SciPhi-AI/R2R) - エンタープライズグレードのエンドツーエンド RAG サービス。![GitHub stars](https://img.shields.io/github/stars/SciPhi-AI/R2R?style=flat-square)
- [RAGFlow](https://github.com/infiniflow/ragflow) - 🇨🇳 深いドキュメント理解 RAG。![GitHub stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square)

---

## 💻 コーディングエージェント

### ターミナル / CLI エージェント

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - 端末で動く Anthropic のエージェント型コーディングツール。Opus 4.7 + `/think xhigh`。SWE-bench 80.9%。
- [Codex CLI](https://github.com/openai/codex) - OpenAI 製のオープンソースターミナルコーディングエージェント。![GitHub stars](https://img.shields.io/github/stars/openai/codex?style=flat-square)
- [Aider](https://github.com/Aider-AI/aider) - Git アウェアなターミナル AI ペアプログラミングパートナー。![GitHub stars](https://img.shields.io/github/stars/Aider-AI/aider?style=flat-square)
- [Goose](https://github.com/block/goose) - Block 製のオープンソースエージェントコーディング CLI。![GitHub stars](https://img.shields.io/github/stars/block/goose?style=flat-square)

### IDE エージェント

- [Cursor 3.09](https://www.cursor.com/) - 🆕 2026-04-03 アップデート。Vibe Coding ワークフロー向けにエージェントモードを強化。
- [Kilo Code](https://www.kilocode.com/) - 🇨🇳 🆕 2026-04 中国コミュニティで人気の Cursor 代替。デフォルトモデル: MiniMax。
- [Cursor](https://www.cursor.com/) - 2026-02 アップデートで 8 並列エージェント対応。
- [Windsurf](https://codeium.com/windsurf) - Codeium 製のエージェント型 IDE。
- [Cline](https://github.com/cline/cline) - VS Code で動く自律コーディングエージェント。![GitHub stars](https://img.shields.io/github/stars/cline/cline?style=flat-square)
- [Continue](https://github.com/continuedev/continue) - VS Code・JetBrains 対応のオープンソース AI コードアシスタント。![GitHub stars](https://img.shields.io/github/stars/continuedev/continue?style=flat-square)
- [GitHub Copilot](https://github.com/features/copilot) - 2026 年初頭よりエージェントモードと `gh copilot` シェル統合。
- [Kiro](https://kiro.dev/) - AWS の自律エージェント。スペック驅動開発、最大3だ 10 タスクを同時管理。
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) - AWS エコシステムと深く統合された AI コーディングコンパニオン。

### 自律ソフトウェアエンジニア

- [Devin 3.0](https://www.cognition.ai/) - 🆕 Cognition 製。動的再プランニング、自己修復コード、レガシーコードベース移行、マルチモーダル入力（UI モックアップ、ビデオ録画）。
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - 自律エージェントとして AI ソフトウェア開発者を使うオープンソースプラットフォーム。![GitHub stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square)
- [SWE-agent](https://github.com/SWE-agent/SWE-agent) - LLM を GitHub Issue を修正するソフトウェアエージェントに変える。![GitHub stars](https://img.shields.io/github/stars/SWE-agent/SWE-agent?style=flat-square)
- [Devika](https://github.com/stitionai/devika) - 💤 **Stale**（2025-09 以降更新なし）。エージェント型 AI ソフトウェアエンジニア、Devin のオープンソース代替。![GitHub stars](https://img.shields.io/github/stars/stitionai/devika?style=flat-square)
- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) - 📦 **Archived**（2025-05）。何を作るか指定すると AI が質問して作成。自律コーディング時代初期の基礎、歴史的参照として維持。![GitHub stars](https://img.shields.io/github/stars/gpt-engineer-org/gpt-engineer?style=flat-square)
- [Codegen](https://github.com/codegen-sh/codegen-sdk) - 🆕 プログラム的なコード操作とマルチファイルリファクタリング SDK。![GitHub stars](https://img.shields.io/github/stars/codegen-sh/codegen-sdk?style=flat-square)
- [Qodo](https://www.qodo.ai/) - 🆕 品質・セキュリティ・テスト生成に特化した AI コードレビュープラットフォーム。

---

## 🤖 Physical AI / 身体性エージェント

*物理世界を知覚し推論し行動する AI —— ヒューマノイドロボット、工場自動化、Physical AI インフラ。言語エージェントの次の波。*

### 基盤モデルと研究

- [Google Gemini Robotics ER-1.6](https://deepmind.google/) - 🆕 2026-04-14。空間・物理推論が強化されたロボティクス AI モデル。Agile Robotics と提携して実機で展開。
- [Project Prometheus (Bezos)](https://www.reuters.com/) - 🆕 ジェフ・ベゾス主導の Physical AI ベンチャー。評価額 $38B、$10B を調達。
- [NVIDIA Isaac GR00T](https://developer.nvidia.com/isaac/gr00t) - NVIDIA のヒューマノイドロボット用基盤モデルプラットフォーム。GTC で発表、Hannover Messe 2026 で拡充。
- [NVIDIA Industrial AI Cloud](https://nvidianews.nvidia.com/) - 🆕 2026-04（Hannover Messe）。ドイツテレコムと共同構築した産業 AI ワークロード用 AI 工場。

### ヒューマノイドロボット

- [Tesla Optimus Gen3](https://www.tesla.com/) - 🆕 2026 年夏量産。汎用タスク向けの高度ヒューマノイド。
- [Honour (荣耀) Humanoid](https://www.honor.com/) - 🇨🇳 🆕 2026 ハーフマラソンで人型ロボット世界記録。
- [Zhiyuan (智元) AGIBOT](https://www.agibot.com/) - 🇨🇳 🆕 2026-04。新しいヒューマノイドボディ、基盤モデル、ソリューションスイート。「展開元年」と表現。
- [Unitree H シリーズ](https://www.unitree.com/) - 🇨🇳 Boston Dynamics の中国競争相手。
- [Agile Robotics](https://www.agile-robots.com/) - 🆕 Gemini Robotics ER-1.6 の展開パートナー。ドイツのロボティクス企業。
- [Shenzhen Humanoid Pilot Line](https://www.chinadailyhk.com/hk/article/631892) - 🇨🇳 🆕 深圳が **2026-04-12** にヒューマノイドロボット初のパイロット生産ラインを稼働（乐聚 Robotics + 東方精工、龍華區）。2 時間で組み立て、年 500～1,000 台。佛山の年 1 万台工場へ量産移行予定。

### 消費者向けロボティクス・ウェアラブル

- [Doubao AI Glasses (ByteDance)](https://seed.bytedance.com/) - 🇨🇳 🆕 2026 年第 2 四半期ローンチ。リアルタイム翻訳、物体認識、豆包 LLM 統合。
- [Nothing AI Glasses/Earbuds](https://nothing.tech/) - 🆕 2026-04 発表。AI 統合スマートウェアラブル。
- [Samsung Galaxy S26 (Gauss 2.3)](https://www.samsung.com/) - オンデバイスのエージェント AI。Gauss 2.3 Think と Gauss O Flash。
- [Meta Ray-Ban Stories 3](https://www.meta.com/) - Llama 統合を継続的に深化。

### 自動運転

- [Tesla FSD v13](https://www.tesla.com/) - 主要市場で L4 対応展開を拡充。
- [Waymo](https://waymo.com/) - 2026 年を通じて米国都市で商用 L4 を展開中。
- [WeRide / Pony.ai / Baidu Apollo](https://www.weride.ai/) - 🇨🇳 中国 L4 車両集団が運行区域を拡大。

---

## 🎮 エージェントシミュレーションと世界モデル

*エージェントを訓練し、観察し、ストレステストするシミュレーション環境。世界モデル・身体性研究が言語エージェントと交わる中、重要性が高まり続けている。*

- [Generative Agents](https://github.com/joonspk-research/generative_agents) - 💤 スタンフォードの名著 *Smallville*（Park et al., 2023）。25 体の LLM 駆動キャラクターをメモリ + 反省 + 計画で連携させるコストチューム。後続の多くのマルチエージェント論文に影響。![GitHub stars](https://img.shields.io/github/stars/joonspk-research/generative_agents?style=flat-square)
- [Voyager](https://github.com/MineDojo/Voyager) - 💤 Minecraft の生涯学習エージェント—— GPT-4 にスキルライブラリとカリキュラム（Wang et al., 2023）。オープンエンド型エージェント評価の古典。![GitHub stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=flat-square)
- [SWE-Gym](https://github.com/SWE-Gym/SWE-Gym) - 実際の GitHub Issue で SWE エージェントを訓練するオープン環境、SWE-bench とセット。![GitHub stars](https://img.shields.io/github/stars/SWE-Gym/SWE-Gym?style=flat-square)
- [WebArena](https://webarena.dev/) - 現実的で再現可能なウェブ環境（Reddit、ショッピング、GitLab クローン）。OSWorld や多くのブラウザエージェント論文で使用される。
- [WorkArena](https://github.com/ServiceNow/WorkArena) - ServiceNow 製のブラウザエージェント用エンタープライズ職場ベンチマーク。![GitHub stars](https://img.shields.io/github/stars/ServiceNow/WorkArena?style=flat-square)
- [Genie 3 / Genie 4](https://deepmind.google/) - Google DeepMind の対話型ビデオ世界モデル—— プロンプトからプレイ可能な 3D 世界を生成。クローズドコード研究。
- [NVIDIA Cosmos](https://github.com/nvidia-cosmos/cosmos-predict1) - 身体性 AI / ロボティクス用の NVIDIA 世界モデル基盤—— 物理的にもっともらしいビデオ未来を生成。![GitHub stars](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-predict1?style=flat-square)

---

## 📊 ベンチマークとリーダーボード

*フロンティア AI 能力を追跡する標準評価スイートとライブリーダーボード。*

- [BenchLM](https://benchlm.ai/) - 🆕 複数のベンチマークファミリーを集約したリーダーボード。2026-04 首位: Claude Mythos Preview 99、Gemini 3.1 Pro / GPT-5.4 同点 94、Claude Opus 4.6 / GPT-5.4 Pro 92、GLM-5 Reasoning 85（オープン首位）。
- [SWE-bench Verified](https://www.swebench.com/) - 実世界の GitHub Issue 解決ベンチマーク。2026-04 首位: Claude Mythos 93.9%、Claude Opus 4.7 87.6%。
- [GPQA Diamond](https://github.com/idavidrein/gpqa) - 💤 データセットリポは 2024-09 以降更新なし。専門家レベルの科学推論。2026-04 首位: Gemini 3.1 Pro 94.3%（世界記録）、Claude Opus 4.7 94.2%。
- [ARC-AGI 2](https://arcprize.org/) - 抽象推論。Gemini 3.1 Pro 77.1%。
- [OSWorld](https://os-world.github.io/) - デスクトップ GUI 操作。GPT-5.4 75%（人間ベースライン超え）。
- [LMArena (旧 Chatbot Arena)](https://lmarena.ai/) - クラウドソース型の会話選好バトル。Opus 4.6 が現在トップ。
- [MMLU-Pro](https://github.com/TIGER-AI-Lab/MMLU-Pro) - MMLU の難化后継者。![GitHub stars](https://img.shields.io/github/stars/TIGER-AI-Lab/MMLU-Pro?style=flat-square)
- [LiveCodeBench](https://livecodebench.github.io/) - コンテスト形式のコーディングベンチマーク、汚染耐性のため継続的に更新。
- [AIME 2025 / Humanity's Last Exam (HLE)](https://agi.safe.ai/) - エリート数学 / 博士レベルの一般推論。
- [Terminal-Bench](https://www.tbench.ai/) - CLI エージェント評価。Codex CLI 77.3%。
- [Wolfram LLM Benchmarking Project](https://www.wolfram.com/llm-benchmarking-project/) - 英語仕様から Wolfram Language へのコード生成。

---

## 🖥️ Computer Use / デスクトップエージェント

*OS レベルでデスクトップソフトウェアを見て・操作し・自動化するエージェント。ブラウザ専用エージェントは [🌐 ブラウザと Web エージェント](#-ブラウザと-web-エージェント) 参照。*

- [Claude Computer Use](https://www.anthropic.com/) - 🆕 Anthropic の「Desktop Intelligence」—— Claude が画面を見、マウス / キーボードで任意のソフトウェアを自動化。
- [OpenAI Operator](https://openai.com/) - 🆕 予約、フォーム入力、ウェブタスク自動化用のブラウザエージェント。
- [Google Project Mariner](https://deepmind.google/) - 🆕 Gemini 駆動のマルチタスク AI、並列タスクとルーチン学習。
- [Microsoft Copilot Agents](https://www.microsoft.com/en-us/microsoft-copilot/) - 🆕 Microsoft 365 スタック上の自律バックグラウンドエージェント。
- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) - コンピュータへの自然言語インターフェース—— LLM にローカルでコードを実行させる。![GitHub stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter?style=flat-square)
- [Manus AI](https://manus.im/) - 🇨🇳 🆕 クラウド・ローカルハイブリッドモデルの自律汎用 AI エージェント。調査・コーディング・複雑なマルチステップタスクを処理。
- [Genspark](https://www.genspark.ai/) - 🆕 mixture-of-agents アーキテクチャのオールインワン自律ワークエージェント。電話も掛けられる。
- [Perplexity Computer](https://www.perplexity.ai/) - 🆕 マルチモデルオーケストレーションとローカルファイルアクセスを備えた調査向けデスクトップエージェント。
- [Beam AI](https://beam.ai/) - 🆕 成功事例に基づきロジックを洗練させる自己学習デスクトップエージェント。

---

## 🌐 ブラウザと Web エージェント

*実ブラウザを介して Web と対話するエージェント—— ナビゲーション、クリック、スクレイピング、マルチページワークフローをこなすフレームワークとインフラ。*

- [Browser Use](https://github.com/browser-use/browser-use) - 2026 年にオープンソースブラウザエージェントの事実上の標準。92K star。![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square)
- [Stagehand](https://github.com/browserbase/stagehand) - Browserbase 製の「ブラウザエージェント用 SDK」—— 型付きの `act` / `extract` / `observe` プリミティブを Playwright の上に提供。MIT。![GitHub stars](https://img.shields.io/github/stars/browserbase/stagehand?style=flat-square)
- [Steel Browser](https://github.com/steel-dev/steel-browser) - 🆕 AI エージェント用オープンソースブラウザ API —— セッション永続化とプロキシローテーションを備えたサンドボックス Chromium。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=flat-square)
- [Skyvern](https://github.com/Skyvern-AI/skyvern) - LLM とコンピュータ・ビジョンでブラウザベースワークフローを自動化。AGPL-3.0。![GitHub stars](https://img.shields.io/github/stars/Skyvern-AI/skyvern?style=flat-square)
- [AgentQL](https://github.com/tinyfish-io/agentql) - クエリ言語 + Playwright 統合でセマンティックな Web 抽出。動的 / 乱雑なページでもロバスト。![GitHub stars](https://img.shields.io/github/stars/tinyfish-io/agentql?style=flat-square)
- [Hyperbrowser MCP](https://github.com/hyperbrowserai/mcp) - 🆕 ホステッドのヘッドレスブラウザフリートを MCP サーバーとして公開。標準ツールインターフェースで Claude / GPT / LangChain にプラグイン。![GitHub stars](https://img.shields.io/github/stars/hyperbrowserai/mcp?style=flat-square)
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - 🆕 マイクロソフト公式の Playwright サーバーを MCP ツールとして公開。プロダクショングレードの自動化。![GitHub stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat-square)
- [MultiOn](https://www.multion.ai/) - ステップ推論 + メモリを内蔵したホステッド型ブラウザエージェントプラットフォーム。クローズドコード。
- [Browserbase](https://www.browserbase.com/) - AI エージェント専用のヘッドレスブラウザインフラ —— ステルス、セッション永続化、captcha 処理、オブザーバビリティ。

---

## 🗣️ 音声とマルチモーダルエージェント

*音声対応 ・ マルチモーダル AI エージェントプラットフォーム。*

- [ElevenLabs](https://elevenlabs.io/) - 業界トップの AI 音声合成、クローン、会話 AI。
- [Vapi](https://github.com/VapiAI/server-sdk-python) - 音声 AI エージェントを構築・テスト・展開するプラットフォーム。![GitHub stars](https://img.shields.io/github/stars/VapiAI/server-sdk-python?style=flat-square)
- [Retell AI](https://www.retellai.com/) - プロダクション対応の会話型音声 AI エージェント。
- [Bland AI](https://www.bland.ai/) - 企業向け AI 電話プラットフォーム。
- [LiveKit Agents](https://github.com/livekit/agents) - 音声・ビデオ・データを含むリアルタイムマルチモーダル AI エージェント。![GitHub stars](https://img.shields.io/github/stars/livekit/agents?style=flat-square)
- [Pipecat](https://github.com/pipecat-ai/pipecat) - 音声・マルチモーダル会話 AI のオープンソースフレームワーク。![GitHub stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=flat-square)
- [Vocode](https://github.com/vocodedev/vocode-python) - 💤 **Stale**（2024-11 以降更新なし）。音声ベース LLM エージェントライブラリ。![GitHub stars](https://img.shields.io/github/stars/vocodedev/vocode-python?style=flat-square)
- [Bolna](https://github.com/bolna-ai/bolna) - エンドツーエンドのオープンソース音声 AI。![GitHub stars](https://img.shields.io/github/stars/bolna-ai/bolna?style=flat-square)
- [Cartesia](https://www.cartesia.ai/) - 🆕 超低遅延のリアルタイム会話型音声 AI。
- [Meta Voice AI](https://ai.meta.com/) - 🆕 旧 PlayHT/Play.ai チームの技術を Meta AI ・ AI キャラクター、ウェアラブルに統合。Play.ai は 2025-12-31 にサービス終了。
- [Sesame](https://www.sesame.com/) - 🆕 感情理解と自然会話を備えた音声 AI コンパニオン。

---

## 📱 パーソナル AI エージェント

- [OpenClaw](https://github.com/openclaw/openclaw) - 🆕 スキル・メモリ・マルチチャネルメッセージング、Dreaming、Canvas/A2UI、ACP コーディング harness を備えた個人向け AI エージェントプラットフォーム。![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat-square)
- [Rabbit R1](https://www.rabbit.tech/) - ラージアクションモデルを搭載した個人 AI デバイス。
- [Limitless](https://www.limitless.ai/) - 見・言い・聞いたものをパーソナライズした AI（旧 Rewind）。
- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) - コンピュータへの自然言語インターフェース。![GitHub stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter?style=flat-square)
- [01 Light](https://github.com/OpenInterpreter/01) - 💤 **Stale**（2024-11 以降更新なし）。オープンソースの音声コンピュータインターフェース。![GitHub stars](https://img.shields.io/github/stars/OpenInterpreter/01?style=flat-square)
- [Leon](https://github.com/leon-ai/leon) - 自サーバ上に住むオープンソース個人アシスタント。![GitHub stars](https://img.shields.io/github/stars/leon-ai/leon?style=flat-square)
- [Khoj](https://github.com/khoj-ai/khoj) - ノートやドキュメント、画像を機械的にスキャンして会話できる「第二の脳」。![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj?style=flat-square)
- [Humane AI Pin](https://humane.com/) - スクリーンレス、アンビエントコンピューティングのウェアラブル AI デバイス。
- [Arahi AI](https://arahi.ai/) - 🆕 個人生産性 + ビジネス自動化アシスタント。
- [Lindy AI](https://www.lindy.ai/) - 🆕 メール・カレンダー・ワークフロー自動化のノーコード AI エージェント。
- [MuleRun](https://www.mulerun.ai/) - 🆕 繰り返しタスクとバックグラウンド自動化の常駐エージェント。

---

## 📱 モバイルエージェント

*Android / iOS を操作する GUI エージェント。デスクトップ Computer Use の次のフロンティア。*

- [Mobile-Agent](https://github.com/X-PLUG/MobileAgent) - 🇨🇳 アリババ製の代表的なマルチモーダル電話操作エージェントファミリー（v1 → v3、Mobile-Agent-E、V も）。Android ベンチマークで SOTA。![GitHub stars](https://img.shields.io/github/stars/X-PLUG/MobileAgent?style=flat-square)
- [AppAgent](https://github.com/mnotgod96/AppAgent) - 💤 タップやスワイプでスマートフォンアプリを操作するテンセント製マルチモーダルエージェント。初期の影響ある実装。![GitHub stars](https://img.shields.io/github/stars/mnotgod96/AppAgent?style=flat-square)
- [Apple Intelligence](https://www.apple.com/apple-intelligence/) - iOS / iPadOS / macOS のオンデバイスエージェント層。App Intents と画面インテリジェントを OS 全体で提供。
- [Samsung Galaxy AI / Bixby 2.0](https://www.samsung.com/global/galaxy/galaxy-ai/) - Galaxy S26 に携載された Gauss 駆動のオンデバイスエージェント機能。
- [Google Gemini for Android](https://gemini.google/) - Android で Google Assistant を置き換える全面 Gemini 駆動のアプリ認識アクション。システム意図と Workspace を含む。
- [Magma](https://microsoft.github.io/Magma/) - Microsoft Research のマルチモーダルエージェント基盤モデル。UI / ロボティクス / 物理動作を統一。

---

## 🏢 エンタープライズエージェントプラットフォーム

- [Salesforce Agentforce](https://www.salesforce.com/agentforce/) - エンタープライズ CRM 用自律 AI エージェント —— 営業・サービス・マーケティング。
- [Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio) - エンタープライズの Copilot とエージェント構築・カスタマイズ。
- [Gemini Enterprise Agent Platform](https://cloud.google.com/blog/products/ai-machine-learning/introducing-gemini-enterprise-agent-platform) - 🆕 **2026-04-22**（Google Cloud Next '26）。Vertex AI がエンタープライズエージェントの構築・拡大・ガバナンス・最適化ハブへ進化。Gemini 3.1 Pro/Flash、Lyria 3 に加え、サードパーティモデル（Claude Opus / Sonnet / Haiku）もサポート。
- [Google Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) - Google Cloud で企業要件の生成 AI エージェントを構築・展開。
- [Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents/) - 複数ステップのタスクを社内システムをまたいで実行。
- [ServiceNow AI Agents](https://www.servicenow.com/products/ai-agents.html) - 🆕 企業 IT サービスマネジメント用 AI エージェント + AI Control Tower。
- [IBM watsonx Orchestrate](https://www.ibm.com/products/watsonx-orchestrate) - 企業アプリをまたいで作業を自動化する AI アシスタントプラットフォーム。
- [Oracle AI Agents](https://www.oracle.com/artificial-intelligence/) - 🆕 Oracle Fusion Cloud ERP と統合された企業 AI エージェント。
- [Moveworks](https://www.moveworks.com/) - あらゆるシステムで動作する AI のエンタープライズコパイロットプラットフォーム。
- [UiPath Agentic Automation](https://www.uipath.com/) - 🆕 RPA ボット資産にエージェント推論を重ねたインテリジェントプロセス自動化。
- [AgentX](https://www.agentx.so/) - チャットボットをプラグアンドプレイで提供しスケーラブルな AI 自動化を提供する企業エージェントソリューション。
- [OutSystems](https://www.outsystems.com/) - 🆕 ミッションクリティカルなアプリとエージェントガバナンスを素早く構築する AI 開発プラットフォーム。
- [Sema4.ai](https://sema4.ai/) - 🆕 Python ファースト、ガバナンス内蔵の企業 AI エージェントプラットフォーム。

---

## 📊 エージェント評価とオブザーバビリティ

- [LangSmith](https://www.langchain.com/langsmith) - LangChain 公式のデバッグ / 評価 / モニタリングプラットフォーム。
- [LangSmith SDK](https://github.com/langchain-ai/langsmith-sdk) - クライアント SDK。![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langsmith-sdk?style=flat-square)
- [Langfuse](https://github.com/langfuse/langfuse) - オープンソース LLM エンジニアリングプラットフォーム: オブザーバビリティ + 評価 + プロンプト管理。![GitHub stars](https://img.shields.io/github/stars/langfuse/langfuse?style=flat-square)
- [Helicone](https://github.com/Helicone/helicone) - オープンソース LLM オブザーバビリティ。![GitHub stars](https://img.shields.io/github/stars/Helicone/helicone?style=flat-square)
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - オープンソース LLM オブザーバビリティ + 評価。![GitHub stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=flat-square)
- [Braintrust](https://www.braintrust.dev/) - LLM 評価 + 最適化プラットフォーム。
- [LMArena (旧 LMSYS Chatbot Arena)](https://lmarena.ai/) - 🆕 クラウドソース型 LLM ベンチマーク。
- [Patronus AI](https://www.patronus.ai/) - 🆕 自動 LLM 評価 + レッドチームプラットフォーム。
- [DeepEval](https://github.com/confident-ai/deepeval) - Pytest スタイルの LLM 評価フレームワーク。組み込み 14+ メトリック。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/confident-ai/deepeval?style=flat-square)
- [Agenta](https://github.com/agenta-ai/agenta) - 🆕 オールインワンオープンソース LLMOps。![GitHub stars](https://img.shields.io/github/stars/agenta-ai/agenta?style=flat-square)
- [AutoEvals](https://github.com/braintrustdata/autoevals) - ベストプラクティスの LLM 評価スコアラーライブラリ。Braintrust 製。![GitHub stars](https://img.shields.io/github/stars/braintrustdata/autoevals?style=flat-square)
- [BenchClaw](https://github.com/Agnuxo1/benchclaw) - ⚠️ **Unverified**。8 個の awesome リストのうち 7 個で却下、単独メンテナチームで2 star。**可視性のための掲載**。![GitHub stars](https://img.shields.io/github/stars/Agnuxo1/benchclaw?style=flat-square)
- [PromptEden](https://www.prompteden.com) - ⚠️ **Unverified**。商用 SaaS で、ChatGPT / Claude / Gemini / Perplexity / Copilot / Grok がどうブランドを説明するかをモニタリング。同一 PR が 1 日以内に 10 個の awesome リストに提出された。**可視性のための掲載**。

---

## 🔬 AI 研究ツール

- [Hugging Face Transformers](https://github.com/huggingface/transformers) - モデルとトレーニングツールの事実上の標準ライブラリ。![GitHub stars](https://img.shields.io/github/stars/huggingface/transformers?style=flat-square)
- [vLLM](https://github.com/vllm-project/vllm) - 高スループット LLM 推論・サービング。![GitHub stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat-square)
- [SGLang](https://github.com/sgl-project/sglang) - 高性能 LLM 推論エンジン。![GitHub stars](https://img.shields.io/github/stars/sgl-project/sglang?style=flat-square)
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - C/C++ 高性能 LLM 推論。![GitHub stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=flat-square)
- [Ollama](https://github.com/ollama/ollama) - ローカルで LLM を走らせる最も簡単な方法。![GitHub stars](https://img.shields.io/github/stars/ollama/ollama?style=flat-square)
- [LM Studio](https://lmstudio.ai/) - デスクトップでローカル LLM を動かす GUI、複数プロバイダ。
- [OpenRouter](https://openrouter.ai/) - 1 つの API で 100+ LLM を一括利用。
- [Unsloth](https://github.com/unslothai/unsloth) - 2 倍高速、VRAM 70% 削減して LLM をファインチューニング。![GitHub stars](https://img.shields.io/github/stars/unslothai/unsloth?style=flat-square)
- [MLX](https://github.com/ml-explore/mlx) - Apple Silicon 上の機械学習フレームワーク。![GitHub stars](https://img.shields.io/github/stars/ml-explore/mlx?style=flat-square)
- [Weights & Biases](https://wandb.ai/) - ML 実験追跡 + モデル管理。
- [Label Studio](https://github.com/HumanSignal/label-studio) - マルチ型データアノテーションプラットフォーム。![GitHub stars](https://img.shields.io/github/stars/HumanSignal/label-studio?style=flat-square)
- [DSPy](https://github.com/stanfordnlp/dspy) - プロンプトではなくプログラミングして言語モデルを使うフレームワーク。![GitHub stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square)

---

## 📚 学習リソース

### 論文

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) - ReAct パターンを定義した重要な論文。
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) - LLM が外部ツールの使い方を自主的に学ぶ。
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) - LLM を使った信じられる人間らしい行動エージェント。
- [LLM-based Autonomous Agents Survey](https://arxiv.org/abs/2308.11432) - LLM ベースの自律エージェントの包括的サーベイ。
- [The Rise and Potential of LLM Based Agents](https://arxiv.org/abs/2309.07864) - LLM エージェントの台頭と可能性。

### コースとチュートリアル

- [LangChain Academy](https://academy.langchain.com/) - LangGraph を含む LangChain 公式コース。
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) - 主要フレームワーク / プロトコルをカバーする AI ショートコース。
- [LLM Agents MOOC (Berkeley)](https://llmagents-learning.org/f24) - UC Berkeley の LLM エージェントコース。
- [Microsoft Agent Framework Docs](https://learn.microsoft.com/en-us/agent-framework/) - 🆕 Microsoft 統合エージェントフレームワークの公式ドキュメント。
- [Hugging Face Agents Course](https://github.com/huggingface/agents-course) - smolagents / LangGraph / Llama-Index でプロダクションエージェントを構築する 5 ユニットの無料コース。![GitHub stars](https://img.shields.io/github/stars/huggingface/agents-course?style=flat-square)
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) - ツール使用、Computer Use、エージェントパターン、プロンプトエンジニアリング、Claude Code レシピの公式ノートブックス。![GitHub stars](https://img.shields.io/github/stars/anthropics/anthropic-cookbook?style=flat-square)
- [Google Gemini Cookbook](https://github.com/google-gemini/cookbook) - grounding、関数呼び出し、マルチモーダル、ライブ音声をカバーする Gemini API 公式例。![GitHub stars](https://img.shields.io/github/stars/google-gemini/cookbook?style=flat-square)
- [LLM Course (Maxime Labonne)](https://github.com/mlabonne/llm-course) - 基礎からファインチューニングまでのエンドツーエンド LLM カリキュラム、Colab ノートブック付き。79K star。![GitHub stars](https://img.shields.io/github/stars/mlabonne/llm-course?style=flat-square)
- [Anthropic Courses](https://github.com/anthropics/courses) - Anthropic 公式のプロンプトエンジニアリング、実世界プロンプト、評価、ツール使用のコース。![GitHub stars](https://img.shields.io/github/stars/anthropics/courses?style=flat-square)

### キュレートされたリスト

- [awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents) - 💤 **Stale**（2025-02 以降更新なし）。E2B 製、プレ 2026 の参考資料。![GitHub stars](https://img.shields.io/github/stars/e2b-dev/awesome-ai-agents?style=flat-square)
- [awesome-llm-agents](https://github.com/kaushikb11/awesome-llm-agents) - LLM ベースのエージェントリソース。![GitHub stars](https://img.shields.io/github/stars/kaushikb11/awesome-llm-agents?style=flat-square)
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - 🆕 MCP サーバー実装リスト。![GitHub stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat-square)

---

## 🇨🇳 中国 AI エコシステム

*中国本土のチームによる、または主に中国市場を対象とする重要プロジェクト。中国スタックは、独自のフレームワーク、モデル、開発者文化を持つ並行エコシステムとしてさらに独自色を強めているため掲載。*

*中国ラボの基盤モデル（Qwen / DeepSeek / GLM / Doubao / Kimi / Hunyuan / ERNIE）は [🧠 基盤モデル](#-基盤モデル-2026) の下に直接記載。*

### エージェントプラットフォームとフレームワーク

- [Dify](https://github.com/langgenius/dify) - ビジュアルエージェントビルダー付きオープンソース LLM アプリ開発プラットフォーム。中国テックで支配的なローコードエージェントキャンバス。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Lobe Chat](https://github.com/lobehub/lobe-chat) - マルチエージェントチャットワークスペース + プラグイン / エージェントマーケットプレイス。トップクラスの TypeScript AI プロジェクト。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/lobehub/lobe-chat?style=flat-square)
- [Cozeloop](https://github.com/coze-dev/cozeloop) - 🆕 ByteDance Coze チームによるオープンソースエージェント最適化プラットフォーム。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/coze-dev/cozeloop?style=flat-square)
- [AgentScope](https://github.com/modelscope/agentscope) - アリババ ModelScope のマルチエージェントフレームワーク + ビジュアルデバッグ + 分散実行。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/modelscope/agentscope?style=flat-square)
- [Bisheng](https://github.com/dataelement/bisheng) - オープンエンタープライズ LLM DevOps プラットフォーム：ワークフローエディタ、RAG、エージェントオーケストレーション、ファインチューニング、評価。Apache-2.0。![GitHub stars](https://img.shields.io/github/stars/dataelement/bisheng?style=flat-square)
- [MetaGPT](https://github.com/geekan/MetaGPT) - LLM に SOP 役割（PM / アーキテクト / エンジニア）を割り振るマルチエージェント。DeepWisdom。![GitHub stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat-square)

### RAG / ナレッジ

- [FastGPT](https://github.com/labring/FastGPT) - ナレッジベースを中心に設計された LLM プラットフォーム: データ取り込み、RAG、ビジュアルワークフロー。![GitHub stars](https://img.shields.io/github/stars/labring/FastGPT?style=flat-square)
- [QAnything](https://github.com/netease-youdao/QAnything) - 💤 NetEase Youdao 製の任意のローカルドキュメントを対象にした質問応答。![GitHub stars](https://img.shields.io/github/stars/netease-youdao/QAnything?style=flat-square)
- [RAGFlow](https://github.com/infiniflow/ragflow) - スキャン PDF、テーブル、図表に強い深いドキュメント理解 RAG エンジン。![GitHub stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square)
- [LightRAG](https://github.com/HKUDS/LightRAG) - 香港大学 HKUDS の軽量グラフ RAG エンジン。![GitHub stars](https://img.shields.io/github/stars/HKUDS/LightRAG?style=flat-square)

### パーソナルと生産性

- [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) - AI ワークスペースエージェント付きオープンソース Notion 代替。AGPL-3.0。![GitHub stars](https://img.shields.io/github/stars/AppFlowy-IO/AppFlowy?style=flat-square)
- [Manus AI](https://manus.im/) - 汎用自律エージェント（北京 Butterfly Effect）。2026 年中国テックで最も注目されたエージェント製品の一つ。
- [Coze (扣才)](https://www.coze.cn/) - ByteDance のノーコードエージェントビルダー。中国本土中心、国際版は coze.com。
- [通义千問 Agent](https://tongyi.aliyun.com/) - アリババの大衆向けコンシューマーエージェント。淘宝 / DingTalk / Quark に統合。
- [Doubao Agents](https://www.doubao.com/) - ByteDance の Doubao モデルファミリーをその上に携載したフラッグシップコンシューマーアシスタント。

### 開発者ツール

- [Kilo Code](https://www.kilocode.com/) - 2026 中国コミュニティで人気の Cursor 代替。デフォルトモデル: MiniMax。
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - 中国開発者サークルで最もインストールされているオープンソースデスクトップ LLM クライアント —— マルチプロバイダ会話 + ナレッジベース。![GitHub stars](https://img.shields.io/github/stars/CherryHQ/cherry-studio?style=flat-square)
- [ScienceOne 100 / 磐石100](https://english.cas.cn/newsroom/cas-in-media/202604/t20260429_1158251.shtml) - 🆕 中国科学院の科学推論エージェントシステム。50+ 中科院研究所、100+ 研究シナリオ、付属 2,000+ 研究ツール。

---

## 📝 比較 — サイドバイサイド表

*2026 年に最もよく出てくる「どれを選ぶ？」の判断マトリクス。*

### 🏗️ エージェントフレームワーク（オープンソース向け）

| フレームワーク | 言語 | マルチエージェント | 状態 / グラフ | ストリーミング | License | 適している用途 |
|------------|------|------------|----------------|----------------|---------|----------|
| [LangGraph](https://github.com/langchain-ai/langgraph) | Python / JS | ✅ ネイティブ | ✅ 一級社会 | ✅ | MIT | プロダクションステートフルワークフロー |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Python | ✅ ロールベース | ⚠️ タスクグラフ | ✅ | MIT | ロールプレイエージェントチーム |
| [AutoGen / Microsoft Agent Framework](https://github.com/microsoft/autogen) | Python / .NET | ✅ 会話型 | ⚠️ Group Chat | ✅ | CC-BY-4.0 / MIT | エンタープライズマルチエージェント |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Python | ✅ handoff | ❌ | ✅ | MIT | OpenAI ネイティブ本番 |
| [Mastra](https://github.com/mastra-ai/mastra) | TypeScript | ✅ | ✅ workflows | ✅ | Elastic-2.0 | TypeScript ファースト |
| [Google ADK](https://github.com/google/adk-python) | Python / Java | ✅ 階層 | ⚠️ | ✅ | Apache-2.0 | Gemini + Vertex AI |
| [DSPy](https://github.com/stanfordnlp/dspy) | Python | ⚠️ モジュール経由 | ⚠️ プログラム型 | ✅ | MIT | プログラム的プロンプト最適化 |
| [Phidata / Agno](https://github.com/phidatahq/phidata) | Python | ✅ teams | ❌ | ✅ | MPL-2.0 | メモリ付きマルチモーダルエージェント |

### 🧪 サンドボックス（エージェント生成コードを実行）

| サンドボックス | ホスティング | コールドスタート | 言語 | 永続化 | License | 適している用途 |
|--------------|--------------|------|------|---------|---------|----------|
| [E2B](https://github.com/e2b-dev/E2B) | クラウド（マネージド） | ~150ms | Python / Node / shell | セッション単位 | Apache-2.0 | OpenAI Agents SDK / 本番 |
| [Daytona](https://github.com/daytonaio/daytona) | クラウド / セルフ | ~500ms | 多言語 | 永続ワークスペース | AGPL-3.0 | 長期実行型タスク |
| [Modal](https://modal.com/) | クラウド（マネージド） | ~200ms | Python | 関数単位 | プロプラエタリ | GPU + サーバーレスエージェント |
| [Microsandbox](https://github.com/superradcompany/microsandbox) | ローカル microVM | ~100ms | 多言語 | セッション単位 | Apache-2.0 | プライバシー重視ローカル |
| [SandboxFusion](https://github.com/bytedance/SandboxFusion) | セルフ | ~300ms | 20+ 言語 | 一時的 | Apache-2.0 | 評価 / ベンチマークパイプライン |

### 🌐 ブラウザエージェントスタック

| スタック | アプローチ | ホスティング | 強み | License |
|----------|------------|--------------|------|---------|
| [Browser Use](https://github.com/browser-use/browser-use) | Vision + DOM（Playwright） | セルフ | 92K star、最大コミュニティ | MIT |
| [Stagehand](https://github.com/browserbase/stagehand) | 型付き act/extract/observe | Browserbase / セルフ | 型・構造化出力 | MIT |
| [Steel Browser](https://github.com/steel-dev/steel-browser) | ヘッドレス API | セルフ / クラウド | セッション・プロキシ・キャプチャ対応 | Apache-2.0 |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | ビジョンファースト | セルフ | 動的ページに強い | AGPL-3.0 |
| [AgentQL](https://github.com/tinyfish-io/agentql) | クエリ言語 | SDK + セルフ | セマンティックなセレクタ | MIT |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | MCP ネイティブ | セルフ | MCP クライアントでプラグイン | Apache-2.0 |

### 📊 評価とオブザーバビリティ

| ツール | セルフ | OpenTelemetry | 評価スイート | プロンプト管理 | License |
|------|--------|----------|------------|------------|---------|
| [Langfuse](https://github.com/langfuse/langfuse) | ✅ | ✅ | ✅ | ✅ | MIT |
| [Helicone](https://github.com/Helicone/helicone) | ✅ | ✅ | ⚠️ 基本 | ✅ | Apache-2.0 |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | ✅ | ✅ | ✅ | ⚠️ | Elastic-2.0 |
| [LangSmith](https://www.langchain.com/langsmith) | ❌（クラウドのみ） | ✅ | ✅ | ✅ | プロプラエタリ |
| [Braintrust](https://www.braintrust.dev/) | ❌（クラウドのみ） | ✅ | ✅ | ✅ | プロプラエタリ |
| [DeepEval](https://github.com/confident-ai/deepeval) | ✅（ライブラリ） | ⚠️ Confident 経由 | ✅ | ❌ | Apache-2.0 |
| [Agenta](https://github.com/agenta-ai/agenta) | ✅ | ✅ | ✅ | ✅ | Apache-2.0 |
| [OpenLLMetry](https://github.com/traceloop/openllmetry) | ✅（計装） | ✅ ネイティブ | ❌ | ❌ | Apache-2.0 |

### 💻 コーディングエージェント——ヘッドライン選択

| ツール | サーフェース | オープンソース | 無料層 | SWE-bench | 適している用途 |
|------|----------|------------|--------|-----------|----------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | CLI / IDE | ❌ | ⚠️ Pro | 80.9% | 長期エンジニアリング |
| [Codex CLI](https://github.com/openai/codex) | CLI | ✅ | ✅ | n/a（Terminal-Bench 77.3%） | OpenAI ネイティブ shell |
| [Cursor](https://www.cursor.com/) | IDE | ❌ | ✅（限定的） | n/a | ペアプログラミング体験 |
| [Cline](https://github.com/cline/cline) | VS Code 拡張 | ✅ | ✅（BYO） | n/a | OSS IDE 代替 |
| [Aider](https://github.com/Aider-AI/aider) | CLI | ✅ | ✅（BYO） | Polyglot で強い | Git 意識リファクタリング |
| [Devin 3.0](https://www.cognition.ai/) | クラウド | ❌ | ❌ | トップ | ハンズオフ長期タスク |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | セルフ | ✅ | ✅ | 競争力あり | セルフ型 SWE エージェント |

*表は 2026-05-05 に検証済み。数値の変更はソース付きで PR を送付してください。*

---

## 🌟 2026 年に注目すべきエージェントプロジェクト

*2026 年の AI エージェント状況を形作ったシグネチャーと出来事。*

- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol/servers) - エージェントツール連携のユニバーサル標準となった。Linux Foundation へ寄贈された。![GitHub stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat-square)
- [A2A Protocol](https://github.com/google/A2A) - 🆕 Google の A2A プロトコルで 150+ パートナーとクロスフレームワーク連携を可能にした。![GitHub stars](https://img.shields.io/github/stars/google/A2A?style=flat-square)
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - SWE-bench 80.9% で 2026 年のターミナル型コーディングエージェントの選択肢となった。
- [Kiro](https://kiro.dev/) - 🆕 AWS が 10 タスク同時管理可能な自律コーディングエージェントをローンチ。
- [Devin 3.0](https://www.cognition.ai/) - 🆕 動的再プラン、自己修復コード、レガシーコードベース移行を含む進化。
- [Microsoft Agent Framework](https://learn.microsoft.com/en-us/agent-framework/) - 🆕 AutoGen + Semantic Kernel が統一企業エージェントプラットフォームとして統合。
- [OpenAI Codex CLI](https://github.com/openai/codex) - OpenAI のオープンソースターミナルエージェント参入。![GitHub stars](https://img.shields.io/github/stars/openai/codex?style=flat-square)
- [Browser Use](https://github.com/browser-use/browser-use) - AI エージェントが Web と自然に対話できるようにしたブレイクスルー。![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square)
- [Claude Computer Use](https://www.anthropic.com/) - 🆕 Desktop Intelligence により Claude が画面を見てあらゆるソフトウェアをコントロール。
- [Manus AI](https://manus.im/) - 🇨🇳 🆕 調査、コーディング、複雑ワークフローを処理できる汎用自律エージェント。
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - オープンソース AI ソフトウェアエンジニアリングプラットフォームが広く採用された。![GitHub stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square)
- [Dify](https://github.com/langgenius/dify) - 🇨🇳 ローコード LLM エージェントプラットフォームが主流に達した。![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square)
- [Cline](https://github.com/cline/cline) - VS Code の自律コーディングエージェントがコミュニティで急長。![GitHub stars](https://img.shields.io/github/stars/cline/cline?style=flat-square)
- [Mem0](https://github.com/mem0ai/mem0) - AI のメモリ層がエージェントアーキテクチャの不可欠な要素になった。![GitHub stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square)
- [Sora サービス終了](https://openai.com/) - 🆕 OpenAI が 2026 年 4 月に Sora を停止、エンタープライズ AI と推論への戦略転換を示した。
- [Kling VIDEO 3.0](https://kling.ai/) - 🇨🇳 🆕 快手製動画生成が Sora 停止後の AI 動画プラットフォームをリード。
- [Cohere + Aleph Alpha 合併](https://siliconangle.com/2026/04/24/ai-startups-cohere-aleph-alpha-merge-600m-new-funding/) - 🆕 **2026-04-24**。カナダとドイツの AI 企業が約 $20B 評価額で合併、Schwarz Group から $600M シリーズ E。跨大西洋「主権 AI」パワーハウス。
- [ScienceOne 100 / 磐石100](https://english.cas.cn/newsroom/cas-in-media/202604/t20260429_1158251.shtml) - 🇨🇳 🆕 **2026-04-28~29**。中国科学院が専門的な科学 AI システムをローンチ。2,000+ 研究ツール、50+ CAS 研究所。
- [Google が Anthropic に $40B 投資](https://aibusiness.com/generative-ai/google-could-invest-another-40-billion-anthropic) - 🆕 **2026-04**。初期 $10B + 業績に応じて最大 $30B。5 年間で 5GW の計算キャパシティを含む。

---

## 📅 2026 AI タイムライン

*2026 年の AI 業界の重要マイルストーンと出来事。*

| 日付 | 出来事 | カテゴリ |
|------|--------|-------|
| **2026-01** | AMD Ryzen AI 400 シリーズを CES で発表 — 60 TOPS NPU 搭載の主流 AI PC | ハードウェア |
| **2026-02** | Claude Opus 4.6 リリース — エージェントチーム能力 | モデル |
| **2026-02** | Claude Sonnet 4.6 リリース — 1M トークンコンテキスト、エージェント型検索 | モデル |
| **2026-02** | Gemini 3.1 Pro リリース | モデル |
| **2026-02** | Qwen3.5 シリーズをローンチ — ネイティブマルチモーダル、エージェント型コーディング | モデル |
| **2026-02** | Qwen3-Coder-Next リリース — 80B MoE コーディングエージェントモデル | モデル |
| **2026-02** | Cursor が 8 並列エージェントをサポート | ツール |
| **2026-02** | GitHub Copilot がエージェントモードとモデルアクセスを拡充 | ツール |
| **2026-03** | Gemini 3.1 Flash Lite を開発者向けにリリース | モデル |
| **2026-03** | Mistral Forge ローンチ — カスタム LLM トレーニングプラットフォーム | プラットフォーム |
| **2026-03** | Microsoft Agent Framework（AutoGen + Semantic Kernel）が GA ターゲット | フレームワーク |
| **2026-03** | DeepSeek が最新 NVIDIA チップで訓練された新モデルを発表 | モデル |
| **2026-03** | MCP 2026 ロードマップを公開 — プロダクションスケーリングとガバナンスに重点 | プロトコル |
| **2026-03** | Sora サービス終了を予告（アプリは 4 月 26 日に閉鎖） | 出来事 |
| **2026-04-02** | Qwen3.6-Plus プロプラエタリフラッグシップをアリババがローンチ | モデル |
| **2026-04-03** | Microsoft AI Agent Governance Toolkit をリリース（オープンソース） | ツール |
| **2026-04-06** | Microsoft Agent Framework を正式発表（AutoGen + Semantic Kernel 統合） | フレームワーク |
| **2026-04-07** | Zhipu AI が GLM-5.1 をオープンソース化 — 744B MoE、華為昂騰で訓練 | モデル |
| **2026-04-08~09** | Meta Muse Spark をリリース — Meta Superintelligence Labs の最初のモデル | モデル |
| **2026-04** | Claude Mythos Preview — ゲート型サイバーセキュリティ研究モデル（BenchLM 99、SWE-bench 93.9%） | モデル |
| **2026-04** | Sora アプリを正式シャットダウン | 出来事 |
| **2026-04-14** | Gemini Robotics ER-1.6 をアップグレード — 空間推論を強化 | ロボティクス |
| **2026-04-15** | Qwen3.6-35B-A3B をオープンソース化（Apache 2.0） | モデル |
| **2026-04-16** | Claude Opus 4.7 リリース — SWE-bench Verified 87.6%、`/think xhigh` 推論 | モデル |
| **2026-04-18** | Qwen3.6-Max-Preview ローンチ — コーディングベンチマークでトップ中国モデル | モデル |
| **2026-04-20~21** | Moonshot AI が Kimi K2.6 をリリース — 1T MoE、1,000-エージェントスワーム | モデル |
| **2026-04-22** | Qwen3.6-27B をアリババがオープンソース化 — 27B 密マルチモーダル | モデル |
| **2026-04-23** | Tencent が Hunyuan Hy3 Preview をオープンソース化 — 295B/21B MoE、256K コンテキスト | モデル |
| **2026-04-23** | Claude Managed Agents Memory パブリックベータ — セッションを越えたエージェントメモリ | ツール |
| **2026-04-23** | OpenAI が GPT-5.5 をリリース — エージェント型コーディングと推論の大幅アップグレード | モデル |
| **2026-04-24** | DeepSeek V4 Pro および Flash をリリース — 1.6T MoE、1M コンテキスト、MIT ライセンス | モデル |
| **2026-04-24** | Cohere がドイツの Aleph Alpha と約 $20B 評価額で合併 + $600M 資金調達 | 業界 |
| **2026-04-27** | アリババ Tianma AI 画像-動画生成モデルがベータ入り | モデル |
| **2026-04-27** | LangGraph v0.3.19 リリース、LangGraph Swarm 事前ビルドエージェント | フレームワーク |
| **2026-04-28** | NVIDIA Nemotron 3 Nano Omni をリリース — 30B マルチモーダル | モデル |
| **2026-04-28~29** | CAS ScienceOne 100 / 磐石100 ローンチ — 50+ 研究所向け科学 AI | モデル |
| **2026-04-30** | OpenAI が Trusted Access for Cyber (TAC) プログラムを通じて GPT-5.5-Cyber の提供を開始 | モデル |
| **2026-04-30** | OpenAI が [「エージェント構築の実践ガイド」](https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/) を公開 | リソース |
| **2026-05-01** | Anthropic が Claude Security をパブリックベータでリリース — Opus 4.7 駆動のコードベース脆弱性スキャナー | ツール |
| **2026-05** | Macquarie Bank が 7 か月で Gemini Enterprise を使って 13 万時間を節約したと報告 | 業界 |
| **2026-05** | Google が対応車両に Gemini をロールアウトし、Google Assistant を置き換える（英語ファースト、米国から） | 業界 |
| **2026-04** | Gartner は 2026 年末までに企業アプリの 40% が AI エージェントを組み込むと予測 | 業界 |
| **2026-04** | Google が Anthropic へ最大 $40B の投資をコミット（初期 $10B） | 業界 |
| **2026 進行中** | A2A Protocol のパートナー組織が 150+ に増加 | プロトコル |
| **2026 進行中** | 開発者の 85% が AI コーディングツールを常用 | 業界 |
| **2026 進行中** | エンタープライズエージェント AI の導入が加速 — "Agents as a Service" が台頭 | 業界 |

---

## 貢献

[CONTRIBUTING.md](CONTRIBUTING.md) をご読みください。**スパム防止の品質ゲート**は中、英、日の 3 言語版すべてに適用されます: 自己宣伝タイプの並列提出 PR は一律拒否されます。

## License

MIT © [Zijian Ni](https://github.com/Zijian-Ni)

---

*Made with ❤️ by [Zijian Ni](https://github.com/Zijian-Ni) · 2026。日本語版は英語版と同期します。不一致がある場合は英語版を正とします。*

