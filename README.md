# x402 Agent Payment Ecosystem

> x402 是一个开放的中立标准，使 AI Agent 能够自主发现、支付和访问服务与内容。本文档整理了 [x402 官方生态页面](https://www.x402.org/ecosystem) 上的所有项目，按功能方向分类。

---

## 📦 核心协议与基础设施

### Coinbase x402

Coinbase 官方维护的 x402 协议实现，是整个生态的技术核心。提供 Node.js、Python、Go 等多语言 SDK，支持 HTTP 和 MCP 协议集成。作为生态背后的主要推动者，Coinbase 将 x402 与其开发者平台 (CDP) 深度整合，为开发者提供稳定的协议基础和工具链支持。

**官网**: https://github.com/coinbase/x402

### x402list.fun

社区维护的 x402 项目目录，汇总生态中的各类项目。为开发者提供一站式入口，便于发现和比较不同解决方案。是了解 x402 生态全貌的良好起点。

**官网**: https://x402list.fun

### x402scan.com

x402 区块链浏览器，用于查看链上的 x402 交易记录。提供交易追踪、统计分析等功能，帮助了解协议的实际使用情况和生态发展动态。

**官网**: https://x402scan.com

### x402 Playground

x402 协议的在线测试工具，开发者可以在此快速验证协议实现。提供交互式的协议调试功能，方便开发者学习和测试。

**官网**: https://www.x402playground.com/

### x402lint

x402 代码检查工具，帮助开发者发现和修复协议实现中的问题。自动检测代码中的常见错误，提高协议实现的兼容性和正确性。

**官网**: https://x402lint.com

### x402 Example Gallery

官方示例代码库，收集了各种场景下的 x402 实现示例。涵盖客户端、服务端、MCP 集成等多个方面，是学习 x402 的最佳资源。

**官网**: https://github.com/coinbase/x402/tree/main/examples/typescript

### X402 Kit (AIMOverse)

AIMOverse 社区开发的 x402 集成工具包，简化 Agent 与 x402 协议的交互过程。提供开箱即用的组件，降低开发门槛。

**GitHub**: https://github.com/AIMOverse/x402-kit

---

## 💰 支付与钱包

### FluxA

面向 AI Agent 的支付钱包解决方案，允许用户充值 USDC 并授权 Agent 在设定预算内自动支付。FluxA 提供完整的 Agent 钱包功能，包括支付限额、托管策略和 x402 协议支持。作为生态中较成熟的产品，FluxA 专注于 Agent 经济场景，支持 MCP 协议集成。

**官网**: https://fluxapay.xyz

### thirdweb

知名的 Web3 基础设施平台，已集成 x402 支付能力。提供智能合约模板、钱包 SDK 和开发者工具，降低 Web3 应用开发门槛。thirdweb 的集成使开发者可以快速为 DApp 添加 x402 支付功能，无需自行实现复杂的支付逻辑。

**官网**: https://thirdweb.com

### Bitrefill

老牌加密货币充值卡平台，支持用加密货币购买各类礼品卡和充值服务。虽然主要面向传统 Crypto 用户，但已集成 x402 扩展其支付能力。为加密用户提供便捷的法币等价物获取渠道。

**官网**: https://www.bitrefill.com

### Asterpay

加密支付解决方案提供商，支持多种加密货币支付方式。致力于降低 Crypto 支付门槛，为商户和用户提供流畅的支付体验。生态覆盖范围逐步扩大。

**官网**: https://asterpay.io

### Otto AI Agent Swarm

面向 AI Swarm 的钱包解决方案，支持多 Agent 协作财务管理。提供 AI Agent 专用的钱包功能，包括自动支出授权和预算控制。文档详细说明了与 x402 协议的集成方式。

**官网**: https://docs.ottowallet.xyz/introduction/otto-ai-swarm

### ClawPay MCP

MCP 协议下的支付解决方案，为 AI Agent 提供标准化的支付接口。简化 Agent 与支付系统的集成流程，降低开发复杂度。

**官网**: https://www.npmjs.com/package/clawpay-mcp

### solana-pay-x402

Solana 生态的 x402 支付适配器，使 Solana 上的应用也能支持 x402 协议。扩展了 x402 的链上支持范围。

**官网**: https://www.npmjs.com/package/solana-pay-x402

### MerchantGuard

商户风控解决方案，为接受加密支付的商户提供反欺诈服务。集成 x402 为安全服务提供标准化计费，帮助商户降低欺诈风险。

**官网**: https://www.merchantguard.ai

### zauth

x402 身份认证解决方案，提供 Agent 身份验证服务。解决 Agent 身份可信度问题，为交易提供信任基础。支持与多种钱包和身份系统集成。

**官网**: https://zauthx402.com

### Proxy402

x402 支付代理服务，简化支付流程的中间件。开发者可以通过简单的 API 调用实现支付功能，无需深入了解底层区块链细节。

**官网**: https://x402.secure.t54.ai/

---

## 🤖 Agent 平台

### Agent Camo

专注于 Agent 隐私保护的平台，为 AI Agent 提供身份匿名化和操作加密服务。在保护用户隐私的前提下支持 x402 支付，解决 Agent 行为的隐私顾虑。为 Agent 提供安全的工作环境。

**官网**: https://agentcamo.xyz

### Agoragentic

新兴的 Agent 市场项目，致力于构建 Agent 间的交易生态。提供 x402 协议支持，使 Agent 能够自主发现和购买其他 Agent 的服务。处于早期发展阶段，有望成为 Agent 经济的基础设施。

**官网**: https://agoragentic.com/api/x402/info

### AIsa

专注于 AI Agent 支付的平台，为 Agent 提供身份认证和支付能力。集成 x402 协议实现自动扣款，支持按需付费模式。目标用户为需要 Agent 执行付费任务的开发者。

**官网**: https://aisa.one

### AiMo Network

AI Agent 网络平台，构建 Agent 间的协作和交易生态。x402 协议用于支持 Agent 间的服务调用支付，促进 Agent 经济的流通。为 Agent 提供发现和交易的网络。

**官网**: https://aimo.network

### Laso Finance

DeFi 与 AI Agent 的结合平台，探索 Agent 自动参与 DeFi 交易的场景。x402 用于支付 Gas 费用和交易手续费，同时支持 DeFi 收益的自动化管理。

**官网**: https://agents.laso.finance

### AI Security Guard

AI Agent 安全服务提供商，为 Agent 操作提供安全审计和风险控制。集成 x402 实现安全服务的标准化付费模式，为 Agent 提供安全保障。

**官网**: https://aisecurityguard.io

### Questflow

自动化工作流平台，支持 x402 支付的工作流编排。允许用户创建付费自动化任务，Agent 可以自主触发支付并执行工作流。

**官网**: https://questflow.ai

### Fluora

AI Agent 平台，集成 x402 实现 Agent 服务的变现。为 Agent 提供商业化能力，支持各类 AI 服务的付费调用。

**官网**: https://www.fluora.ai/

### use-agently.com

Agent 开发平台，提供 Agent 构建和部署能力。集成 x402 支持 Agent 服务的变现需求，为开发者提供完整的 Agent 商业化方案。

**官网**: https://use-agently.com

---

## 📡 API / MCP 变现

### AdEx AURA API

去中心化广告网络 AdEx 的 API 变现方案，支持内容创作者通过 API 提供广告服务。x402 协议用于广告曝光和点击的自动计费，提供透明的收益结算。为内容创作者提供新的变现渠道。

**官网**: https://guide.adex.network/

### AdPrompt x402 API

营销和广告 API 平台，提供各类营销工具的 API 服务。通过 x402 支持按调用付费，帮助营销人员快速接入自动化工具。涵盖广告投放、素材生成等多个营销场景。

**官网**: https://www.adprompt.ai/x402-api

### Agnic.AI

AI API 变现平台，允许 AI 服务提供者将 API 能力变现。x402 实现自动化的 API 调用计费，降低付费门槛。支持多种 AI 模型的 API 变现需求。

**官网**: https://agnic.ai/x402

### Bloomfilter

数据 API 平台，提供各类数据查询服务。x402 用于数据访问的按次付费，支持开发者快速获取所需数据。涵盖市场数据、用户行为等多种数据类型。

**官网**: https://bloomfilter.xyz/docs

### ActionGate

API 网关服务，支持 x402 支付协议的 API 访问控制。为开发者提供简化的付费 API 部署方案，支持多种后端服务的快速集成。

**官网**: https://api.actiongate.xyz/docs

### Atomic Rail

API 变现平台，专注于开发者工具的付费化。提供完整的支付、计费和用户管理功能，支持 API 的快速商业化。

**官网**: https://www.atomicrail.com

### QuickNode

区块链基础设施提供商，节点服务支持 x402 支付。为开发者提供付费的 RPC 节点访问，用于区块链交互和数据查询。

**官网**: https://quicknode.com

### Neynar

开发者友好的 NFT 和身份基础设施，支持 x402 支付。为 NFT 市场、身份认证等应用提供付费 API 服务。

**官网**: https://neynar.com

### Nevermined

数据和服务变现平台，支持 x402 协议的数据交易。为 AI 模型训练、数据集销售等场景提供标准化支付方案。

**官网**: https://nevermined.io

### Pinata

IPFS 存储服务，支持 x402 付费访问。提供去中心化存储的按量付费模式，适合大规模数据存储和分发场景。

**官网**: https://402.pinata.cloud/

### Numbers Protocol

去中心化数据协议，支持 x402 支付的数据验证和溯源服务。为数字内容提供所有权证明和数据完整性验证。

**官网**: https://numbersprotocol.io/

### Firecrawl

网页数据采集工具，支持 x402 付费采集。开发者可以付费自动化采集大规模网页数据，支持清洗后的结构化输出。

**官网**: https://firecrawl.dev

### Zyte API

网页数据提取服务，支持 x402 支付的数据采集。为机器学习和其他数据密集型应用提供付费的网页数据获取方案。

**官网**: https://www.zyte.com/

### PostEra

化学数据分析 API，支持 x402 支付的分子数据分析服务。为药物研发和材料科学提供数据查询和分析能力。

**官网**: https://postera.ai

### Cascade

数据层服务，支持 x402 付费的数据存储和检索。为应用提供去中心化的数据持久化方案。

**官网**: https://cascade.fyi

---

## 🎮 游戏与娱乐

### Kodo

AI 创意工具平台，专注于动漫风格的图像和视频生成。支持 x402 付费使用，为创意工作者提供 AI 生成能力。模型包括 RYU.01 等高质量动漫引擎系列。

**官网**: https://www.kodo.fun

### AI Frens (Treasure)

Treasure 生态游戏平台，探索游戏内 AI Agent 的变现模式。x402 支持游戏道具和服务的购买，为游戏内购买提供标准化支付方案。

**官网**: https://aifrens.lol

### Genbase.fun

链游平台，集成 x402 实现游戏内支付。为玩家提供流畅的链游支付体验，支持游戏资产的自由交易。

**官网**: https://genbase.fun

### Nuwa AI

AI 内容创作平台，支持 AI 生成内容的变现。通过 x402 实现内容访问的自动付费，为创作者提供变现渠道。

**官网**: https://nuwa.dev/

### Stakevia

加密货币质押平台，探索 Agent 自动参与质押的变现模式。支持 x402 支付相关的费用结算和收益分配。

**官网**: https://stakevia.xyz

### Ubounty

游戏化任务平台，支持 x402 支付的任务奖励。为品牌和开发者提供任务分发和支付的完整解决方案。

**官网**: https://ubounty.ai

---

## 🔐 安全与风控

### Augur

DeFi 预测市场风控工具，为预测市场提供风险评估服务。x402 用于风险查询服务的付费，支持市场风险的量化评估。

**官网**: https://augurrisk.com/

### AltLayer

Layer 2 扩容解决方案，支持 x402 支付的状态证明服务。为区块链应用提供可验证的状态查询能力。

**官网**: https://altlayer.io/

### Obol

分布式验证服务，支持 x402 支付的去中心化验证。为区块链网络提供分布式签名和验证能力。

**官网**: https://obol.tech

### DappLooker AI

DApp 数据分析平台，支持 x402 付费的数据查询。为开发者提供链上数据分析、仪表板等工具。

**官网**: https://dapplooker.ai/

### DiamondClaws DeFi Intelligence

DeFi 智能分析平台，x402 支付支持的 DeFi 风险评估服务。为投资者提供 DeFi 项目的风险分析和建议。

**官网**: https://diamondclaws.io

### Trusta.AI

区块链安全服务，支持 x402 支付的地址风险评估。为交易平台和用户提供地址安全检查服务。

**官网**: https://app.trustalabs.ai/attest

### Proofivy

证明验证服务，x402 支付支持的零知识证明验证。为隐私保护应用提供证明验证的标准化接口。

**官网**: https://proofivy.com

---

## 🛠️ 开发者工具

### x402-go

Go 语言实现的 x402 SDK，方便 Go 开发者快速集成支付功能。提供完整的客户端和服务端支持，是构建高性能 x402 服务的理想选择。

**GitHub**: https://github.com/mark3labs/x402-go

### MCP Server Example

Coinbase 官方的 MCP 协议 x402 示例，演示如何通过 MCP 提供付费 API 服务。展示 Agent 如何通过 MCP 调用需要支付的外部服务。

**GitHub**: https://github.com/coinbase/x402/tree/main/examples/typescript/mcp

### Node Servers (Hono, Express, Advanced)

官方 Node.js 服务器示例，涵盖 Hono 和 Express 框架的 x402 集成。为 Web 开发者提供详细的实现参考。

**GitHub**: https://github.com/coinbase/x402/tree/main/examples/typescript/servers

### Axios & Fetch Clients

官方 HTTP 客户端示例，展示如何在现有代码中集成 x402 支付。提供 Axios 和原生 Fetch 两种实现的参考代码。

**GitHub**: https://github.com/coinbase/x402/tree/main/examples/typescript/clients

### Mogami

高性能代理服务，支持 x402 的云原生部署。提供 Java 客户端和服务端 SDK，方便 Java 生态的开发者集成。

**官网**: https://mogami.tech/

### API Paywall Cookbook

开源的 API 变现指南，提供多种语言和框架的 x402 集成示例。为开发者提供实战级的变现方案参考。

**GitHub**: https://github.com/fabriciogava/api-paywall-cookbook

### Imference

Agent 开发框架，集成 x402 支持 Agent 服务的变现。为构建商业化 Agent 提供完整的技术方案。

**官网**: https://imference.com

### Subnano

轻量级 Agent 运行时，支持 x402 支付的服务调用。为资源受限环境提供高效的 Agent 部署方案。

**官网**: https://subnano.me/

### Slingshot

快速构建工具集，支持 x402 的快速集成。为初创项目提供敏捷开发的支持能力。

**官网**: https://slingshot.sh

---

## 🔍 数据与分析

### x402 Market

x402 服务市场，聚合各类 x402 付费 API 供开发者发现和使用。提供服务的分类、搜索和评价功能，是 x402 生态的服务目录。

**官网**: https://x402.world.fun

### x402station

x402 服务聚合平台，帮助发现和接入各类 x402 支付服务。提供一键集成和开发者工具，降低使用门槛。

**官网**: https://x402station.com/

### x402-wall

x402 支付墙实现，展示如何为网站添加付费访问控制。提供多种集成方式，适合内容创作者和开发者快速实现变现。

**官网**: https://x402wall.fun/how-it-works

### 402.load.network

x402 协议的网络分析工具，提供协议使用情况的统计和监控。帮助开发者了解 x402 在网络中的实际运行状态。

**官网**: https://402.load.network

### Ordiscan

比特币 Ordinals 浏览器，探索 x402 在 Ordinals 生态的应用。提供交易追踪和数据分析能力。

**官网**: https://ordiscan.com

### Robtex

互联网数据统计服务，支持 x402 支付的带宽和数据查询。为网络监控提供付费数据接口。

**官网**: https://x402.robtex.com

### x402r

x402 协议的状态查询工具，验证支付和授权状态。为服务提供方提供快速的状态确认能力。

**官网**: https://x402r.org

### Run402

x402 服务运行平台，提供托管的 x402 支付处理能力。简化支付集成，无需自行维护支付基础设施。

**官网**: https://run402.com

---

## 📱 社交与通讯

### twit.sh

推特机器人和工具平台，支持 x402 支付的服务调用。为社交媒体自动化提供付费能力。

**官网**: https://twit.sh

### SocioLogic

社交媒体分析 API，x402 支付的社交数据查询服务。为营销和分析提供付费的社交数据接口。

**官网**: https://www.sociologic.ai/x402-rng

### tip.md

MCP 服务器的 x402 支付集成，展示如何通过 MCP 提供付费服务。为模型上下文协议用户提供支付方案。

**官网**: https://www.tip.md/documentation?tab=mcp-server

### Snack Money API

开发者工具 API，支持 x402 支付的开发者资源访问。为软件开发者提供付费的工具和服务调用。

**官网**: https://api.snack.money/docs

### DJD Agent Score

Agent 评估服务，x402 支付支持的 AI Agent 评分。为 Agent 选择和评估提供量化指标。

**官网**: https://djd-agent-score.fly.dev

---

## 🎯 其他项目

### 1Pay.ing

微支付平台，支持按分付费的网页访问控制。简化小額支付的接入流程，适合内容变现场景。

**官网**: https://1pay.ing

### 1Shot API

n8n 工作流 API 平台，支持 x402 变现 n8n 工作流。允许用户将自动化工作流封装为付费服务。

**官网**: https://1shotapi.com

### AEON

支付协议，x402 生态的支付解决方案之一。提供标准化的支付接口和开发者工具。

**官网**: https://aeon.xyz/AIPayment

### Ampersend

支付基础设施，支持 x402 的批量支付处理。为企业提供大规模的支付解决方案。

**官网**: https://ampersend.ai

### auor.io (Oreo)

AI Agent 服务平台，探索 Agent 的商业化模式。集成 x402 支持 Agent 服务的变现。

**官网**: https://auor.io

### AurraCloud

云服务提供商，x402 支付的云资源访问。为开发者提供按需付费的云服务。

**官网**: https://aurracloud.com/x402

### BlackSwan

数据分析平台，x402 支付的商业智能服务。为企业提供数据分析和洞察能力。

**官网**: https://blackswan.wtf

### BlockRun.AI

区块链数据服务，支持 x402 支付的链上数据查询。为 DeFi 和链上分析提供数据接口。

**官网**: https://blockrun.ai

### Bino (IoTeX)

IoTeX 生态的 Agent 工具，支持 x402 支付的服务调用。用于 IoTeX 区块链上的自动化任务。

**GitHub**: https://github.com/iotexproject/binoSwarm

### ClawdVine

工具和资源聚合平台，x402 支付支持的工具库。为开发者提供付费的开发工具和服务。

**官网**: https://clawdvine.sh

### CodeNut

开发者文档平台，x402 付费访问的编程教程。为学习者提供付费的优质编程资源。

**官网**: https://www.codenut.ai/x402

### Cybercentry

网络安全服务，x402 支付的网络安全评估。为企业提供安全审计和风险评估服务。

**官网**: https://cybercentry.gitbook.io/cybercentry/documents/x402-cybercentry

### Ekai Labs

AI 实验室平台，探索 AI 技术的商业化应用。集成 x402 支持 AI 服务的变现。

**官网**: https://ekailabs.xyz

### Einstein AI

AI 助手服务，x402 付费的对话和能力调用。为用户提供 AI 助手的高级功能访问。

**官网**: https://einstein.ai

### EntRoute

路由服务，支持 x402 支付的智能路由。为分布式系统提供流量分配和付费管理。

**官网**: https://entroute.com

### Faremeter

费用计算工具，x402 支付支持的成本估算服务。为项目预算提供自动化的成本分析。

**官网**: https://faremeter.xyz

### Farnsworth

开发者工具，x402 付费的开发和部署服务。为开发者提供一站式的开发平台。

**官网**: https://ai.farnsworth.cloud

### Foldset

文档工具，x402 付费的技术文档服务。为团队提供协作化的文档管理能力。

**官网**: https://foldset.com

### Gloria AI

AI 聊天服务，x402 付费的 AI 对话能力。为用户提供高级 AI 聊天的访问权限。

**官网**: https://gloria-ai.com

### Grove API

数据服务，x402 支付的数据访问接口。为应用提供标准化的数据查询能力。

**官网**: https://grove.sh

### Heurist Mesh

AI 计算网络，支持 x402 支付的分布式 AI 算力。为 AI 训练和推理提供按需付费的计算资源。

**官网**: https://heurist.ai

### ICPay

支付解决方案，x402 集成的支付处理服务。为商户提供简化的加密支付接入。

**官网**: https://icpay.cloud

### invy

开发者平台，x402 支付的开发工具和服务。为开发者提供完整的开发工具链。

**官网**: https://invy.ai

### KAMIYO

AI 服务平台，支持 x402 的 AI 能力变现。为 AI 服务提供者提供商业化平台。

**官网**: https://kamiyo.io

### Kevros

去中心化服务市场，x402 支付的去中心化服务交易。为用户提供去中心化的服务发现和购买。

**官网**: https://kevros.io

### Kobaru

自动化平台，x402 付费的工作流自动化服务。为企业和个人提供流程自动化能力。

**官网**: https://www.kobaru.io/

### Kurier

消息服务，x402 支付的通讯服务。为应用提供可靠的消息传递能力。

**官网**: https://kurier.io

### Latinum Agentic Commerce

商业化 Agent 平台，x402 支持的 Agent 商业化服务。为 Agent 提供完整的变现解决方案。

**官网**: https://latinum.io

### Locus

位置服务，x402 支付的地理位置数据查询。为应用提供位置相关的付费数据服务。

**官网**: https://locus.sh

### MCPay

MCP 支付集成工具，简化 MCP 协议的支付能力接入。为 MCP 服务提供者快速添加支付功能。

**官网**: https://mcpay.dev

### Meridian

支付路由服务，x402 支付的多通道路由优化。为支付提供智能路由和成本优化。

**官网**: https://meridianprotocol.io

### Meson x402

支付通道服务，x402 集成的支付网络。为加密支付提供快速确认和低手续费。

**Chrome**: https://chromewebstore.google.com/detail/meson-x402/ppdppbgbdlnnmompceomhadjminblalp

### Minifetch

轻量级数据获取工具，x402 付费的数据抓取服务。为开发者提供高效的网页数据获取能力。

**官网**: https://minifetch.com

### Moltalyzer

分析工具，x402 支付的数据分析服务。为业务决策提供数据支持。

**官网**: https://moltalyzer.com

### Mycelia Signal

信号服务，x402 支付的信号数据查询。为交易和投资提供付费的信号数据。

**官网**: https://mycelia.signal.ai

### OOBE Protocol & Synapse

协议服务，支持 x402 的跨链交互。为多链应用提供统一的支付和交互接口。

**官网**: https://oobe protocol.com

### Oops!402

工具集合，x402 相关的实用工具集合。为开发者提供各类辅助工具和服务。

**官网**: https://oops402.com

### Onchain

链上数据服务，x402 支付的区块链数据查询。为开发者提供链上数据的付费访问。

**官网**: https://onchain.com

### Orac

预言机服务，x402 支付的数据源接入。为智能合约提供可靠的外部数据服务。

**官网**: https://orac.network

### PEAC Protocol

支付协议，x402 生态的支付标准实现。提供标准化的支付接口和开发者工具。

**官网**: https://x402.peacprotocol.org

### PredictOS

操作系统服务，x402 付费的云端系统访问。为开发者提供远程操作系统环境。

**官网**: https://predictos.com

### Primer

支付基础设施，x402 集成的支付处理服务。简化支付流程的开发和维护。

**官网**: https://primer.systems

### QuickSilver

质押服务，x402 支付的权益证明管理。为持币者提供自动化的质押管理服务。

**官网**: https://quicksilver.liquid.gov

### RelAI

RelAI 是一个 AI 关系服务，集成 x402 提供付费的关系智能分析。为社交应用和 CRM 系统提供关系洞察能力。

**官网**: https://relai.ai

### Rencom

通讯服务，x402 付费的企业通讯解决方案。为企业提供安全可靠的通讯平台。

**官网**: https://x402.rencom.ai

### Rug Munch Intelligence

DeFi 风险情报，x402 支付的风险评估数据。为投资者提供项目安全评估和预警服务。

**官网**: https://cryptorugmunch.app/api/agent/v1/status

### SerenAI x402 Gateway

AI 网关服务，x402 集成的 AI 能力入口。提供统一的 AI 服务访问和支付管理。

**官网**: https://serenai.io

### SLAMai

AI 服务平台，x402 付费的 AI 能力调用。聚合多种 AI 模型提供统一的访问接口。

**官网**: https://www.slamai.xyz/

### Slinky Layer

Layer 2 服务，x402 支付的扩容解决方案。为应用提供高性能的链下计算服务。

**官网**: https://slinkylayer.com

### Soundside

音频服务，x402 付费的音频处理 API。为应用提供音频转码、编辑等能力。

**官网**: https://soundside.io

### Spraay x402 Gateway

网关服务，x402 集成的 API 网关。提供流量管理、认证和支付的一体化解决方案。

**官网**: https://docs.spraay.app

### TokenMesa

代币服务，x402 支付的代币管理服务。为项目提供代币发行和管理的完整方案。

**官网**: https://www.tokenmesa.com

### tollbooth

API 限流服务，x402 付费的流量控制。为 API 提供商实现按量付费的访问控制。

**官网**: https://tollbooth.sh

### Tweazy

工具平台，x402 付费的实用工具集合。提供各类开发和生活工具的付费访问。

**GitHub**: https://github.com/aaronjmars/tweazy

### ZeroPay

支付平台，x402 集成的零手续费支付解决方案。探索加密支付的零成本模式。

**官网**: https://zpaynow.com

### zkStash

存储服务，x402 付费的去中心化存储。为应用提供私密、安全的分布式存储能力。

**官网**: https://zkstash.ai

### x402-engine

x402 协议引擎，简化 x402 实现的工具库。提供高层次的抽象加速开发。

**官网**: https://x402engine.app

### x402-watch

监控工具，x402 支付状态和交易监控。为服务提供方提供实时支付状态追踪。

**GitHub**: https://github.com/logiccrafterdz/x402-watch

---

## 📊 生态总结

### 优势

- **协议开放**: 由 Coinbase 主导但保持开放性，任何人都可以免费使用
- **标准化**: 统一使用 HTTP 402 响应码，与现有 Web 架构无缝集成
- **Agent 原生**: 专为 AI Agent 设计，支持自动授权支付和预算控制
- **多链支持**: 适配多条区块链，USDC 为主要结算资产

### 瓶颈

- **稳定币依赖**: 目前主要支持 USDC 等稳定币，无法直接处理法币
- **链上延迟**: 区块链确认需要时间，小额支付不够经济
- **生态认知度**: 大部分开发者尚未了解 x402，需要更多推广
- **合规模糊**: 多数项目缺乏明确的 KYC/AML 政策

### 头部项目

| 项目 | 用户基础 | 成熟度 | 特点 |
|------|----------|--------|------|
| FluxA | ⭐⭐⭐ | 高 | Agent 钱包完整解决方案 |
| thirdweb | ⭐⭐⭐ | 高 | Web3 基础设施龙头 |
| Bitrefill | ⭐⭐⭐ | 高 | 老牌加密支付平台 |
| n8n (1shotapi) | ⭐⭐ | 中 | 工作流变现先驱 |
| Firecrawl | ⭐⭐ | 中 | 数据采集变现 |

---

## 📚 相关资源

- x402 官网: https://www.x402.org
- x402 文档: https://docs.x402.org
- x402 白皮书: https://www.x402.org/x402-whitepaper.pdf
- Coinbase CDP: https://www.coinbase.com/developer-platform

---

*本目录基于 x402 官方生态页面 (https://www.x402.org/ecosystem) 整理，共收录 140+ 项目，最后更新于 2026-03-11*
