<div align="center">

# 👋 Hi, I'm Ngô Phước Đại

### ** Backend Developer / Fullstack Developer / Blockchain Developer / AI Engineer**

*Building high-throughput backend microservices, privacy-conscious AI retrieval platforms, and security-focused software.*

[Portfolio](https://github.com/ngophuocdai) • [LinkedIn](https://linkedin.com/in/phuoc-dai-ngo) • [Email](mailto:ngophuocdai0805@gmail.com)

---

</div>

## 🧑‍💻 About Me

I am a Data Science student at the **University of Transport Ho Chi Minh City** with experience in backend microservices architecture, applied cryptography, and AI model execution pipelines.

My engineering work sits at the intersection of **AI Systems**, **Distributed Backend Architecture**, and **Software Security & Privacy**. I specialize in building event-driven NestJS microservices, gRPC/Kafka communication backbones, on-device multimodal AI retrieval engines, and cryptographic verification ledgers.

- 🎓 **Education**: B.S. in Data Science, University of Transport Ho Chi Minh City *(Sep 2023 – Present)*
- 💼 **Experience**: Backend Developer Intern at **Smart Generation Of Digital** *(Jul 2024 – Jul 2026)*
- 🎯 **Core Focus**: Distributed Systems (gRPC/Kafka/NestJS) • AI Inference Optimization (ONNX) • Security & ABAC (CASL/E2EE) • Privacy-by-Design & On-Device AI

---

## 🚀 Featured Projects

### 🔎 AuraSeek — Multimodal AI Retrieval Platform (2026)
*🏆 Second Prize, Student Scientific Research & Innovation Contest (2026)*

> **Flagship Project**: Combining Computer Vision, On-Device AI Inference, Multimodal Embeddings, and High-Performance Desktop Engineering.

- **Multimodal Semantic AI Engine**: Built a semantic retrieval system integrating Object Detection, Face Recognition, and CLIP-style multimodal embeddings for indexing large-scale image collections. Supports text-to-image, image-to-image, and hybrid search queries.
- **Privacy-by-Design & On-Device Inference**: Designed a local **on-device AI inference pipeline** to perform feature extraction directly on the host machine, eliminating data leakage risks and preserving user privacy.
- **High-Performance Desktop UI**: Developed a responsive desktop application (Tauri + React) featuring virtualized grid rendering, infinite loading, and real-time state synchronization for smooth browsing across thousands of high-resolution images.
- **Tech Stack**: `Python` • `Rust` • `Tauri` • `React` • `Computer Vision` • `Multimodal Embeddings` • `PyTorch`

---

### 📦 SGOD Secure High-Throughput Upload Microservice (2024 – 2026)
*Production-ready file management microservice with AES-256-GCM envelope encryption and MinIO/S3 object storage integration.*

- **AES-256-GCM Envelope Encryption**: Designed a cryptographic storage layer performing envelope key generation and AES-256-GCM encryption before persisting files to MinIO/S3, ensuring complete data privacy against cloud admin inspection.
- **Multi-Stage Validation & Deduplication**: Built a multi-stage validation pipeline verifying MIME types, magic headers, and SHA-256 content hashes to deduplicate binary uploads and prevent malicious file execution.
- **K6 Performance Verification**: Verified system throughput and latency using **K6 load testing**, maintaining a high request success rate and approximately **600 ms P95 response latency** under high concurrency.
- **Kafka Orchestration & Compensation Layer**: Integrated Kafka event producers for downstream media processing and implemented transactional rollback compensation in NestJS to clean up MinIO objects if database metadata writes fail.
- **Tech Stack**: `NestJS` • `TypeScript` • `MinIO/S3` • `Kafka` • `AES-256-GCM` • `MongoDB` • `gRPC` • `K6`

---

### 📈 Crypto Financial Intelligence & ONNX Predictor Platform (2025 – Present)
*Real-time cryptocurrency analytics, PyTorch Mamba ONNX inference, and reactive charting dashboard.*

- **Multi-Head ONNX AI Execution**: Compiled a PyTorch Mamba temporal sequence predictor (**CryptoMamba**) to `.onnx` and loaded it directly inside the NestJS backend via `onnxruntime-node`, executing CPU-optimized multi-head predictions (returns, 3-class trend, and ATR price bands).
- **Dual-Zone Predictor Fallback Engine**: Engineered a fallback mechanism in TypeScript to resolve Out-of-Distribution model freezing during severe market volatility: when the regression head outputs values within a flat boundary, a classification head is evaluated for trend direction.
- **Asynchronous Pipelines & Reactive Dashboard**: Offloaded high-frequency market API polling via **BullMQ** background queues and dynamic Redis caching. Built a React 19 dashboard streaming real-time WebSocket chart updates using Recharts and D3.js.
- **Tech Stack**: `NestJS` • `Python` • `ONNX Runtime` • `React 19` • `Vite` • `BullMQ` • `Redis` • `Socket.io` • `Recharts` • `D3.js`

---

### 🛡️ Hybrid Malware Detection System (2025)
*Multi-stage security scanning combining static signature analysis and machine learning.*

- **Dual-Engine Scanning Pipeline**: Built a hybrid malware detection system pairing YARA static signature matching with an AI classifier for Portable Executable (PE) binaries.
- **Verified Benchmark Performance**: Achieved **94.6% accuracy** and **94.5% F1-score** on the public PE Malware Machine Learning Dataset.
- **Zero-Trust In-Memory Scanning**: Designed a multi-stage scanning pipeline adhering to Zero-Trust principles and using in-memory execution to isolate unverified binaries during analysis.
- **Monitoring Web Portal**: Developed a web interface for asynchronous file submission, real-time scan monitoring, and threat analysis visualization.
- **Tech Stack**: `Python` • `YARA` • `Scikit-learn` • `Machine Learning` • `Security Engineering` • `Web Interface`

---

### 💬 Chat-UTH Real-Time Communication System (2024 – 2025)
*Production-grade monolithic real-time communication platform with E2EE, Kafka event pipeline, and AI chatbots.*

- **High-Concurrency Messaging**: Developed a real-time messaging engine supporting 1:1 and group chats with cursor-based pagination, reactions, and multi-device sync. Benchmarked WebSocket channels under 100 Virtual User load tests, locating peak throughput boundaries (~90-110 msg/s) and optimizing MongoDB indices to eliminate write locks.
- **Kafka Pipeline & End-to-End Encryption**: Implemented Kafka event producers/consumers to decouple push notifications (Firebase) from transport logic. Integrated group key management for E2EE messaging, Elasticsearch for message indexing, and Prometheus telemetry.
- **Academic AI Chatbots**: Integrated Google GenAI and HuggingFace Transformers for context-aware academic assistant chatbots with conversation history persistence.
- **Tech Stack**: `NestJS` • `TypeScript` • `Socket.io` • `Kafka` • `MongoDB` • `Elasticsearch` • `E2EE` • `GenAI` • `Prometheus`

---

### 📰 Near Real-Time News Aggregation & Search Platform (2026)
*Scalable news aggregation, role-based access control, and full-text retrieval system.*

- **Dual-Database Search Architecture**: Designed search architecture utilizing MongoDB for document persistence and Elasticsearch for near real-time full-text indexing with autocomplete.
- **Modular Backend & RBAC**: Built a modular backend supporting role-based access control (RBAC), BullMQ asynchronous task processing, and personalized content delivery.
- **Tech Stack**: `TypeScript` • `Microservices` • `MongoDB` • `Elasticsearch` • `Redis` • `BullMQ` • `React`

---

## 💼 Professional Experience

### **Backend Developer Intern** — Smart Generation Of Digital
*Ho Chi Minh City, Vietnam • July 2024 – July 2026*

- **Microservices & API Gateway (BFF)**: Developed distributed backend services using NestJS (CQRS/DDD), gRPC Protobuf contracts, Kafka event streaming, and API Gateway BFF routing with circuit breaker and retry mechanisms.
- **Secure Object Storage Microservice**: Developed an `upload-service` integrating MinIO/S3 object storage, multi-stage file validation, and AES-256-GCM envelope encryption to reduce malicious upload risks.
- **K6 Performance Verification**: Benchmarked the upload service via **K6 load testing**, maintaining a high request success rate and approximately **600 ms P95 response latency** under load.
- **Blockchain Compliance & Audit Ledger**: Contributed to EVM smart contract integration (Solidity, Hardhat) for `ProofOfErasure` logs and data integrity audits on decentralized arrays.
- **CASL ABAC & Identity**: Implemented Attribute-Based Access Control (ABAC) using CASL schemas mapped over gRPC metadata alongside OAuth 2.0 and JWT/JWKS identity verification.
- **AI-Assisted Workflow**: Applied prompt engineering, AI code review tools, and automated debugging within daily development cycles.

---

## 🏆 Academic Achievements

- 🏆 **Second Prize** — Student Scientific Research & Innovation Contest *(2026)* — *AuraSeek Platform*
- 🏆 **Second Prize, Best Presentation Award** — National Scientific Conference on AI, Blockchain and Metaverse Applications in Marketing *(June 2025)*

---

## 🛠️ Technical Skills

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>🧠 AI & Machine Learning Systems</h3>
      <ul>
        <li><b>Inference & Retrieval</b>: ONNX Runtime, Mamba Sequence Models, Multimodal Retrieval, Semantic Search, Computer Vision</li>
        <li><b>AI Workflow Tools</b>: Prompt Engineering, AI-Assisted System Architecture, Claude, Cursor, Codex, Antigravity</li>
      </ul>
      <h3>⚙️ Backend & Distributed Systems</h3>
      <ul>
        <li><b>Languages</b>: TypeScript, Python, Rust</li>
        <li><b>Architecture</b>: Microservices, gRPC (Protobuf), REST, Kafka Event Streaming, NestJS (CQRS, DDD), API Gateway (BFF)</li>
        <li><b>Databases & Infrastructure</b>: MongoDB, Redis Cluster, Elasticsearch, BullMQ, MinIO/S3</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <h3>🔒 Security & Applied Cryptography</h3>
      <ul>
        <li><b>Identity & Authorization</b>: CASL (ABAC), OAuth 2.0, JWT/JWKS (ES256K), gRPC Metadata Guards</li>
        <li><b>Security Principles</b>: AES-256-GCM Envelope Encryption, Privacy-by-Design, Zero-Trust, E2EE</li>
        <li><b>EVM Smart Contracts</b>: Solidity, Hardhat, Ethers.js (Proof of Erasure, Audit Trails)</li>
      </ul>
      <h3>💻 Frontend & Visualization</h3>
      <ul>
        <li><b>Web & Desktop</b>: React 19, Next.js, Tauri, Tailwind CSS, Vite</li>
        <li><b>Data & Real-Time</b>: Recharts, D3.js, WebSockets (Socket.io), Virtualized Grids</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📊 GitHub Overview

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ngophuocdai&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Ngo Phuoc Dai's GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ngophuocdai&layout=compact&theme=dark&hide_border=true" alt="Top Languages" width="48%" />

</div>

---

## 📫 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Phuoc%20Dai%20Ngo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/phuoc-dai-ngo)
[![Email](https://img.shields.io/badge/Email-ngophuocdai0805%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ngophuocdai0805@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ngophuocdai-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ngophuocdai)

</div>
