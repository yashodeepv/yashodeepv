<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00B4D8&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B%2C+I'm+Yashodeep+Vaidya;Principal+Architect+%7C+Distributed+Systems;Small+Language+Models+%7C+Compilers+%7C+Core+Data" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yashodeepv&label=Profile+Views&color=00b4d8&style=flat-square" alt="Profile views" />
  <a href="https://linkedin.com/in/yashodeepv"><img src="https://img.shields.io/badge/LinkedIn-yashodeepv-0077B5?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:yashodeepv@gmail.com"><img src="https://img.shields.io/badge/Email-yashodeepv@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Mumbai%2C+India-FF9933?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Experience-16%2B+Years-10B981?style=flat-square" alt="Experience" />
</p>

---

## 🧭 Executive Summary

I am a **Principal Software Engineer and Architect** with 16+ years designing mission-critical distributed systems, canonical data catalogs, and automated execution platforms. My background spans tier-one capital markets risk engines (Morgan Stanley, UBS, GoldenSource) and high-scale travel platforms (Priceline).

- 🏛️ **System Architecture:** Distributed data modeling, multi-feed entity resolution, server-driven UI engines, and event-driven microservices.
- 🤖 **Applied AI & ML Systems:** Domain-specific Small Language Models (SLMs) from scratch, knowledge distillation, and deterministic LLM verification pipelines.
- 📐 **Engineering Leadership:** Multi-year target state roadmaps, Technical Reference Documents (TRDs), and cross-organizational governance across Web, Mobile, Data, and ML teams.
- 🦀 **Creative Tech & Education:** Building visual mathematics, logic animation engines, and strategy content across YouTube channels including **Learn with Crabby** and **Chess with Crabby**.

---

## ⚖️ Architectural Tenets

1. **Explicit Trade-Offs Over Best Practices:** No architecture is universally good. Latency, consistency, operational overhead, and developer velocity must be weighed against concrete business constraints.
2. **Schemas as Contracts:** Loosely typed data across distributed boundaries is technical debt. Rigorous schemas, backward compatibility checks, and contract testing prevent distributed failure.
3. **Frugal AI Over Brute Force:** Avoid deploying massive parameter models where deterministic heuristics, compiler transforms, or fine-tuned SLMs achieve higher throughput at a fraction of the unit cost.
4. **Decouple Deployments from Releases:** Core business platforms should empower product teams through metadata-driven runtimes, shifting routine changes out of heavyweight release pipelines.

---

## 🏗️ Core Platform & System Highlights

### 1. Metadata-Driven Dynamic Execution Engine
* **The Problem:** Cross-platform feature releases (Web, iOS, Android) were constrained by multi-sprint deployment cycles and cross-team dependencies.
* **The Architecture:** Designed a metadata-driven backend runtime paired with an agentic configuration-authoring engine.
* **The Impact:** Shifted application composition to dynamic configuration, cutting feature release cycles from months to hours with zero code deployments or server restarts.

### 2. Master Room ID & Cross-Supplier Entity Resolution
* **The Problem:** Resolving and deduplicating unstructured hotel room inventory across multiple disparate supplier feeds lacking common identifiers.
* **The Architecture:** Led the build-versus-buy evaluation (benchmarking third-party engines against internal platforms) and designed a scalable multi-stage text-matching pipeline bypassing brute-force LLM inference at scale.
* **The Impact:** Eliminated duplicate room inventory across search and booking funnels to protect conversion and pricing integrity.

### 3. Production AI Verification & Drift Detection Guardrails
* **The Problem:** Non-deterministic generative outputs and hallucinations in customer-facing content pipelines.
* **The Architecture:** Built automated evaluation pipelines on Google Vertex AI using primary-plus-judge verification models, structured JSON schema enforcement, and statistical drift detection.
* **The Impact:** Established automated release-readiness gating for unstructured text and image classification workloads.

### 4. Capital Markets Market Risk & Regulatory Engines
* **The Problem:** Processing massive transaction volumes under strict regulatory latency and data lineage mandates (BCBS 239).
* **The Architecture:** Architected stress-testing calculation engines and instrument reference data pipelines processing tens of billions of records daily across distributed grid infrastructure.
* **The Impact:** Guaranteed sub-second calculation SLAs and immutable auditability for global trading desks.

---

## 🔬 Systems Research & Open Source

| Project | Domain | Architectural Snapshot |
| :--- | :--- | :--- |
| [**baby-programmer-slm**](https://github.com/yashodeepv/baby-programmer-small-language-model) | Compilers & SLMs | A custom ~25.8M parameter decoder-only Transformer built from scratch to translate natural language into verified AArch64 assembly. Implements an intermediate representation (IR) engine with dual execution-oracle verification (312k+ executions, zero unverified samples). |
| [**design-patterns**](https://github.com/yashodeepv/design-patterns) | Architecture & Clean Code | Production-grade reference implementations of Gang-of-Four design patterns and enterprise integration idioms in modern Java. Serves as companion material for systems design sessions. |
| [**vm-provisioning-service**](https://github.com/yashodeepv/vm-provisioning-service) | Cloud Infrastructure | Asynchronous compute provisioning engine featuring containerized deployments, relational state machines, and real-time operational telemetry. |

---

## 🛠️ Technical Stack & Toolchain

### Systems & Languages
![Java](https://img.shields.io/badge/Java_17+-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)

### Distributed Platforms & Middleware
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

### Enterprise Data Stores
![Oracle Exadata](https://img.shields.io/badge/Oracle_Exadata-F80000?style=flat-square&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Greenplum](https://img.shields.io/badge/Greenplum-00A98F?style=flat-square&logo=vmware&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![DB2](https://img.shields.io/badge/IBM_DB2-1F70C1?style=flat-square&logo=ibm&logoColor=white)

### Applied AI & Verification
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Google_Vertex_AI-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

---

## 📺 Channels, Visual Education & Strategy

Beyond enterprise systems, I design automated visual explainers and instructional channels focused on deep systems thinking, mathematical problem-solving, and strategy:

| Channel / Initiative | Focus Area | Core Content |
| :--- | :--- | :--- |
| [**Architecture & Systems (@yashodeepv)**](https://www.youtube.com/channel/UCLhqLCyhnI9S4-A-gTvQ3ig) | Systems Architecture & Code | Deconstructing enterprise design patterns, event-driven trade-offs, and building small language models from scratch. |
| **Learn with Crabby** | Logic, Math & Geometry | High-engagement visual animations exploring geometric proofs, recreational mathematics, and algorithmic puzzles. |
| **Chess with Crabby** | Positional Strategy & Tactics | Tactical pattern recognition, calculation trees, and endgame evaluation. |

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yashodeepv&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&cache_seconds=86400" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=yashodeepv&show_icons=true&theme=tokyonight&hide_border=true&layout=compact&cache_seconds=86400" alt="Top Languages" width="40%" />
</p>

---

<p align="center">
  <i>"Architecture is not about making systems complex: it is about uncovering the underlying simplicity that makes scale manageable."</i>
</p>
