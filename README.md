# x402 Agent Payment Ecosystem

> x402 是一个开放的中立标准，使 AI Agent 能够自主发现、支付和访问服务与内容。本文档整理了 x402 生态中的主要项目，按功能方向分类。

---

## 📦 核心基础设施

### Coinbase x402

Coinbase 官方维护的 x402 协议实现，是整个生态的技术核心。提供 Node.js、Python、Go 等多语言 SDK，支持 HTTP 和 MCP 协议集成。作为生态背后的主要推动者，Coinbase 将 x402 与其开发者平台 (CDP) 深度整合，为开发者提供稳定的协议基础和工具链支持。

**官网**: https://github.com/coinbase/x402

---

### thirdweb

知名的 Web3 基础设施平台，已集成 x402 支付能力。提供丰富的智能合约模板和开发者工具，降低 Web3 应用开发门槛。thirdweb 的集成使开发者可以快速为 DApp 添加 x402 支付功能，无需自行实现复杂的支付逻辑。

**官网**: https://portal.thirdweb.com/payments/x402/client

---

### x402list.fun

社区维护的 x402 项目目录，汇总生态中的各类项目。为开发者提供一站式入口，便于发现和比较不同解决方案。是了解 x402 生态全貌的良好起点。

**官网**: https://x402list.fun

---

### x402scan.com

x402 区块链浏览器，用于查看链上的 x402 交易记录。提供交易追踪、统计分析等功能，帮助了解协议的实际使用情况和生态发展动态。

**官网**: https://x402scan.com

---

## 💰 支付与钱包

### FluxA Pay

面向 AI Agent 的支付钱包解决方案，允许用户充值 USDC 并授权 Agent 在设定预算内自动支付。FluxA 提供完整的 Agent 钱包功能，包括支付限额、托管策略和 x402 协议支持。作为生态中较成熟的产品，FluxA 专注于 Agent 经济场景，支持 MCP 协议集成。

**官网**: https://fluxapay.xyz

**相关文档**: https://docs.fluxapay.xyz/wallet/

---

### Valuya Guard (Gorilla)

基于 x402 的支付授权中间件，专注于 n8n 工作流变现。通过 Privy 进行非托管密钥管理，集成 Monerium (EURe) 支持 SEPA 即时转账。提供零手续费政策，支持多种 Web 框架的适配器，适合个人开发者和小型团队快速实现工作流变现。

**官网**: https://pay.gorilla.build

**GitHub**: https://github.com/gorillafund/valuya-guard

---

### Bitrefill

老牌加密货币充值卡平台，支持用加密货币购买各类礼品卡和充值服务。虽然主要面向传统 Crypto 用户，但已集成 x402 扩展其支付能力。为加密用户提供便捷的法币等价物获取渠道。

**官网**: https://www.bitrefill.com

---

### Asterpay

加密支付解决方案提供商，支持多种加密货币支付方式。致力于降低 Crypto 支付门槛，为商户和用户提供流畅的支付体验。生态覆盖范围逐步扩大。

**官网**: https://asterpay.io

---

### Otto Wallet

面向 AI Swarm 的钱包解决方案，支持多 Agent 协作财务管理。提供 AI Agent 专用的钱包功能，包括自动支出授权和预算控制。文档详细说明了与 x402 协议的集成方式。

**官网**: https://docs.ottowallet.xyz/introduction/otto-ai-swarm

---

### Clawpay MCP

MCP 协议下的支付解决方案，为 AI Agent 提供标准化的支付接口。简化 Agent 与支付系统的集成流程，降低开发复杂度。

**官网**: https://www.npmjs.com/package/clawpay-mcp

---

## 🤖 Agent 平台

### n8n + 1shotapi

n8n 工作流自动化平台通过 1shotapi 集成 x402 支付能力，使工作流可以被变现。用户可以将 n8n 工作流封装为付费服务，按调用次数或订阅模式收费。适合自动化工作者的变现需求。

**文档**: https://docs.1shotapi.com/automation/n8n.html#monetize-n8n-workflows-with-x402

---

### Agent Camo

专注于 Agent 隐私保护的平台，为 AI Agent 提供身份匿名化和操作加密服务。在保护用户隐私的前提下支持 x402 支付，解决 Agent 行为的隐私顾虑。

**官网**: https://agentcamo.xyz

---

### Agoragentic

新兴的 Agent 市场项目，致力于构建 Agent 间的交易生态。提供 x402 协议支持，使 Agent 能够自主发现和购买其他 Agent 的服务。处于早期发展阶段。

**官网**: https://agoragentic.com/api/x402/info

---

### AISA

专注于 AI Agent 支付的平台，为 Agent 提供身份认证和支付能力。集成 x402 协议实现自动扣款，支持按需付费模式。目标用户为需要 Agent 执行付费任务的开发者。

**官网**: https://aisa.one

---

### AI Mo Network

AI Agent 网络平台，构建 Agent 间的协作和交易生态。x402 协议用于支持 Agent 间的服务调用支付，促进 Agent 经济的流通。

**官网**: https://aimo.network

---

### Laso Finance

DeFi 与 AI Agent 的结合平台，探索 Agent 自动参与 DeFi 交易的场景。x402 用于支付 Gas 费用和交易手续费。

**官网**: https://agents.laso.finance

---

### AI Security Guard

AI Agent 安全服务提供商，为 Agent 操作提供安全审计和风险控制。集成 x402 实现安全服务的标准化付费模式。

**官网**: https://aisecurityguard.io

---

## 📡 API / MCP 变现

### AdEx AURA

去中心化广告网络 AdEx 的 API 变现方案，支持内容创作者通过 API 提供广告服务。x402 协议用于广告曝光和点击的自动计费，提供透明的收益结算。

**官网**: https://guide.adex.network/

---

### AdPrompt

营销和广告 API 平台，提供各类营销工具的 API 服务。通过 x402 支持按调用付费，帮助营销人员快速接入自动化工具。

**官网**: https://www.adprompt.ai/x402-api

---

### Agnic.ai

AI API 变现平台，允许 AI 服务提供者将 API 能力变现。x402 实现自动化的 API 调用计费，降低付费门槛。

**官网**: https://agnic.ai/x402

---

### Bloomfilter

数据 API 平台，提供各类数据查询服务。x402 用于数据访问的按次付费，支持开发者快速获取所需数据。

**官网**: https://bloomfilter.xyz/docs

---

### ActionGate

API 网关服务，支持 x402 支付协议的 API 访问控制。为开发者提供简化的付费 API 部署方案。

**官网**: https://api.actiongate.xyz/docs

---

### AtomicRail

API 变现平台，专注于开发者工具的付费化。提供完整的支付、计费和用户管理功能。

**官网**: https://www.atomicrail.com

---

## 🎮 游戏与娱乐

### Kodo.fun

AI Agent 游戏平台，将游戏与 AI Agent 结合。玩家可以部署 Agent 进行游戏操作，x402 用于游戏内购买和交易。

**官网**: https://www.kodo.fun

---

### AI Frens (Treasure)

Treasure 生态游戏平台，探索游戏内 AI Agent 的变现模式。x402 支持游戏道具和服务的购买。

**官网**: https://aifrens.lol

---

### Genbase.fun

链游平台，集成 x402 实现游戏内支付。为玩家提供流畅的链游支付体验。

**官网**: https://genbase.fun

---

### Nuwa AI

AI 内容创作平台，支持 AI 生成内容的变现。通过 x402 实现内容访问的自动付费。

**官网**: https://nuwa.dev/

---

## 🔐 安全与风控

### MerchantGuard

商户风控解决方案，为接受加密支付的商户提供反欺诈服务。集成 x402 为安全服务提供标准化计费。

**官网**: https://www.merchantguard.ai

---

### Augur

DeFi 预测市场风控工具，为预测市场提供风险评估服务。x402 用于风险查询服务的付费。

**官网**: https://augurrisk.com/

---

### Zauth

x402 身份认证解决方案，提供 Agent 身份验证服务。解决 Agent 身份可信度问题，为交易提供信任基础。

**官网**: https://zauthx402.com

---

## 🛠️ 开发者工具

### x402-go

Go 语言实现的 x402 SDK，方便 Go 开发者快速集成支付功能。提供完整的客户端和服务端支持。

**GitHub**: https://github.com/mark3labs/x402-go

---

### x402-node

Node.js 官方 SDK，TypeScript 支持完善。是大多数 Web 开发者集成 x402 的首选方案。

**GitHub**: https://github.com/coinbase/x402

---

### MCP (Model Context Protocol)

Coinbase 官方的 MCP 集成，使 x402 可以在 MCP 协议下工作。方便 Agent 通过 MCP 调用付费 API。

**GitHub**: https://github.com/coinbase/x402/tree/main/examples/typescript/mcp

---

### Firecrawl

网页数据采集工具，支持 x402 付费采集。开发者可以付费自动化采集大规模网页数据。

**官网**: https://firecrawl.dev

---

### IoTeX Bino

IoTeX 生态的 Agent 工具，支持 x402 支付。用于 IoTeX 区块链上的自动化任务执行。

**GitHub**: https://github.com/iotexproject/binoSwarm

---

## 🔍 分析与工具

### 402.load.network

x402 协议的网络分析工具，提供协议使用情况的统计和监控。帮助开发者了解 x402 在网络中的实际运行状态。

**官网**: https://402.load.network

---

### x402 Playground

x402 协议的在线测试工具，开发者可以在此快速验证协议实现。提供交互式的协议调试功能。

**官网**: https://www.x402playground.com/

---

### x402 Lint

x402 代码检查工具，帮助开发者发现和修复协议实现中的问题。提高代码质量和协议兼容性。

**官网**: https://x402lint.com

---

## 📊 生态总结

### 优势

- 协议开放：由 Coinbase 主导但保持开放性
- 标准化：统一 HTTP 402 响应码，易于集成
- Agent 原生：专为 AI Agent 设计，支持自动授权支付

### 瓶颈

- 稳定币依赖：仅支持 USDC 等稳定币，无法直接处理法币
- 链上延迟：需要区块链确认，小额支付不够经济
- 认知度低：大部分开发者尚未了解 x402
- 合规模糊：多数项目缺乏明确的 KYC/AML 政策

### 头部项目

| 项目 | 用户基础 | 成熟度 |
|------|----------|--------|
| FluxA | ⭐⭐⭐ | 高 |
| Valuya Guard | ⭐⭐ | 中 |
| thirdweb | ⭐⭐⭐ | 高 |
| n8n (1shotapi) | ⭐⭐ | 中 |

---

## 📚 相关资源

- x402 官网: https://www.x402.org
- x402 文档: https://docs.x402.org
- x402 白皮书: https://www.x402.org/x402-whitepaper.pdf
- Coinbase CDP: https://www.coinbase.com/developer-platform

---

*本目录基于 x402 官方生态页面整理，最后更新于 2026-03-11*
