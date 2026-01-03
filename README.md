# 👋 Hi, I'm Wasif Ul Islam Shah

## 🧠 Protocol Engineer & Senior Software Engineer

I'm a **Protocol Engineer and Senior Software Engineer** with **4+ years of Rust** and **10+ years of backend experience**, specializing in **privacy-preserving and real-time systems**.

I design high-performance blockchain infrastructure across **Solana and Substrate**, with hands-on expertise in protocol-level DeFi systems including **collateralized stablecoins (CDPs)**, **oracle-driven pricing**, **liquidation mechanisms**, **confidential execution**, **zero-knowledge systems**, and **cross-chain interoperability**.

My recent work focuses on **Decentralized Confidential Computing using Arcium MPC**, including encrypted input handling, confidential execution flows, and verifiable on-chain settlement for Solana programs.

I complement my technical work with strong finance fundamentals, having completed the **CFA Institute Investment Foundations® Certificate**, covering market structure, risk, portfolio construction, and ethics—knowledge that directly informs protocol incentive design and execution models.

Previously, I worked on large-scale real-time messaging systems at Botim, building low-latency, fault-tolerant backend services in Rust and gRPC.

---

## 🔬 Recent Technical Focus

- Building **Solana DeFi protocols** including **CDP stablecoins**, **lending protocols**, **asset exchanges**, and **token vesting systems**.
- Currently leading architecture and protocol development of **FintraDex**, a next-generation **orderbook DEX** on Substrate/Polkadot, integrating **Risc0 zkVM** for trustless, zero-knowledge off-chain order matching and verifiable settlement.
- Implementing **ISMP + Hyperbridge** interoperability for cross-chain trading across Substrate, Solana, and EVM.
- Delivered production Solana applications using **compressed NFTs (cNFTs)**, including minting flows, on-chain metadata handling, and cost-efficient asset management.

---

## 🚀 Featured Work

### 🔐 **Senior Software Engineer – [FintraDex](https://fintradex.io/)**  
> Next-generation **orderbook DEX** for decentralized finance

- Leading **architecture and protocol development** of FintraDex, built on **Substrate/Polkadot**.
- Integrating **Risc0 zkVM** for **trustless, zero-knowledge off-chain order matching** and verifiable settlement.
- Actively implementing **ISMP + Hyperbridge** to enable **cross-chain interoperability** with Substrate, Solana, and EVM ecosystems.

---

### 🏦 **The Compound – [thecompound.cc](https://thecompound.cc/)**
> Production Solana application with compressed NFTs

- Delivered a **production Solana application** using **compressed NFTs (cNFTs)**, including minting flows, on-chain metadata handling, and cost-efficient asset management.
- Leveraged **Solana compression primitives** to enable scalable, cost-effective NFT minting and management at scale.
- Implemented comprehensive **minting workflows** and **on-chain metadata handling** for efficient asset lifecycle management.

---

### 💰 **Solana DeFi Engineering (Independent Protocol Builds)**

#### **WS Stablecoin — Solana CDP Stablecoin Protocol**  
> [GitHub Repository](https://github.com/wasif1024/ws-stablecoin) | Solana-based stablecoin protocol with CDP system

- Designed and implemented a **SOL-collateralized CDP stablecoin** on Solana using **Rust + Anchor 0.30.1**.
- Integrated **Pyth Network oracles** (PriceUpdateV2) for real-time SOL/USD price feeds, enabling accurate collateral valuation and health factor calculations.
- Implemented comprehensive **liquidation mechanisms** with automated health factor monitoring, liquidation bonus calculations (10% default), and debt repayment flows.
- Built secure **PDA-based account architecture** for configuration, collateral tracking, and stablecoin mint management.
- Features **Token-2022 support** with program-controlled mint authority and freeze capabilities.
- Implemented **overcollateralization system** (200% default) with configurable liquidation threshold (50%) and minimum health factor validation.
- Core instructions include: deposit & mint, redeem & withdraw, liquidation, and admin configuration management.
- Comprehensive error handling for price validation, health factor checks, and protocol safety enforcement.

#### **WS Lending — Solana Decentralized Lending Protocol**  
> [GitHub Repository](https://github.com/wasif1024/ws-lending) | Production-ready lending protocol with share-based accounting

- Designed and implemented a **production-ready decentralized lending protocol** on Solana using **Rust + Anchor 0.30.1**.
- Built sophisticated **share-based accounting system** enabling efficient interest accrual without constant on-chain updates, using continuous compounding with exponential growth.
- Supports **dual asset lending** (SOL and USDC) with deposits, withdrawals, borrowing, and repayment flows.
- Integrated **Pyth Network oracle** for real-time price feeds with staleness checks, enabling accurate collateral valuation and liquidation calculations.
- Implemented **automated liquidation mechanisms** with health factor monitoring, close factor calculations, and liquidation bonus incentives.
- Features **PDA-based treasury accounts** for secure token management and automated interest accrual on deposits and borrows.
- Core instructions include: deposit, withdraw, borrow, repay, and liquidate with comprehensive validation and error handling.
- Interest accrues continuously using exponential compounding formula, ensuring fair and accurate interest calculations for both depositors and borrowers.

#### **WS Swap — Solana Asset Exchange Prototype**  
> [GitHub Repository](https://github.com/wasif1024/ws-swap) | Token swap protocol with PDA-secured vaults

- Implemented **token swap flows** and conversion logic to explore pricing paths, execution costs, and account modeling on Solana.
- Built **PDA-secured vaults** to securely hold tokens during swap operations, preventing unauthorized access.
- Designed **swap offer system** allowing users to create and accept token swap offers for various Solana tokens.
- Leveraged **Anchor framework** for efficient and secure Solana program development with comprehensive instruction handlers.

#### **WS Vesting — Solana Token Vesting Protocol**
- Built on-chain vesting schedules with cliff logic and secure token release using PDAs and Token-2022.

---

### 🏢 **Senior Rust Engineer – Astra Tech (Botim Messaging Platform)**
> High-throughput, real-time messaging backend systems

- Contributed to large-scale consumer messaging infrastructure.
- Designed and implemented **low-latency Rust + gRPC services**, focusing on performance, correctness, and fault tolerance.
- Built and optimized **event-driven pipelines** for messaging, presence, and system coordination in production.

---

### 🛠️ **Senior Rust Engineer – Taif UI Jaud**
> Consulting & Product Development

- Architected and delivered blockchain and backend systems for international clients, specializing in Rust, Solana, and privacy-preserving protocols.
- **Designity**: Designed and shipped an Anchor-based Solana program for tamper-evident reviews, with PDA modeling, Node.js APIs, and workflow orchestration.
- **Hoopas**: Developed and maintained Solana NFT smart contracts using Metaplex; project live on Magic Eden.

---

### ⚡ **Lead Rust Engineer – Invo Technology**
> Blockchain-integrated application architecture

- Designed and implemented a scalable **Rust microservices architecture**.
- Built high-performance async APIs using **Actix-Web**, with strong focus on reliability and clean architecture.
- Integrated **Subxt** for off-chain to on-chain interactions with a Substrate-based blockchain.
- Implemented event-driven pipelines with **Kafka and Redis**, and deployed services via **Docker/Kubernetes on AWS**.

---

## 🛠️ Core Technologies & Expertise

### **Blockchain & Web3**
- **Solana**: Anchor framework, Token-2022, Light Protocol, compressed NFTs (cNFTs)
- **Substrate**: Runtime pallets, governance, ISMP
- **Interoperability**: ISMP + Hyperbridge
- **Zero-Knowledge Proofs**: Risc0 zkVM, zk-SNARKs, Pinocchio
- **Confidential Computing**: Arcium MPC
- **DeFi Protocols**: CDP stablecoins, lending protocols, asset exchanges, oracle integration, liquidation mechanisms

### **Backend & Infrastructure**
- **Rust**: Tokio, Actix-Web, Subxt, gRPC
- **Event-driven systems**: Kafka, Redis
- **Databases**: PostgreSQL, Redis, MySQL
- **Cloud & DevOps**: Docker, Kubernetes, AWS, GCP

---

## 🎓 Certifications

- **CFA Institute** – Investment Foundations® Certificate
- **Polkadot Blockchain Academy (PBA-X)**, Wave 5
- **Certified Solana Builder** — HackQuest × Solana Foundation

---

## 📫 Get In Touch

- **LinkedIn**: [Wasif Ul Islam Shah](https://www.linkedin.com/in/wasif-shah-13002799/)
- **GitHub**: [@wasif1024](https://github.com/wasif1024)
- **Email**: wasif1024@gmail.com
- **Mobile**: +971(58)-6899257
- **WhatsApp**: +92(345)-4767257
- **Telegram**: @wasif1024

I'm always open to discussing **protocol engineering, DeFi systems, confidential computing, and blockchain infrastructure**. Let's build the future of decentralized finance together. 🚀
