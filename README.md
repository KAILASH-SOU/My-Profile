<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0F172A,50:0D9488,100:6366F1&height=240&section=header&text=Kailash&fontSize=80&fontColor=FFFFFF&animation=twinkling&fontAlignY=40&desc=System%20Software%20%7C%20Compilers%20%7C%20ML%20Systems%20%7C%20FPGA&descAlignY=62&descSize=20" width="100%" alt="Kailash" />

<a href="https://github.com/KAILASH-SOU">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=2DD4BF&center=true&vCenter=true&width=820&lines=Graph+compiler+%2B+inference+runtime+in+C%2B%2B17;Low-latency+C%2B%2B20+trading+engine+with+lock-free+queues;FPGA-enabled+deep+learning+for+DC+arc+fault+detection;Codeforces+Specialist+%7C+1%2C000%2B+problems+solved;Seeking+System+Software+Engineering+roles" alt="Typing animation" />
</a>

<br/>

<a href="https://github.com/KAILASH-SOU"><img src="https://img.shields.io/badge/GitHub-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://www.linkedin.com/in/kailash-choudhary-55b0b1280/"><img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:soukailash46@gmail.com"><img src="https://img.shields.io/badge/Email-DB2777?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://codeforces.com/profile/Kailash_Choudhari"><img src="https://img.shields.io/badge/Codeforces-Specialist-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
<a href="https://leetcode.com/u/Kailash_Choudhari/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=KAILASH-SOU&label=PROFILE%20VIEWS&color=0D9488&style=flat-square" alt="Profile views" />

</div>

---

##  About Me

Final-year B.Tech student at **VNIT Nagpur** (Electrical & Electronics Engineering, minor in CSE), applying to **System Software Engineering** roles. I like understanding how things work from the silicon up: compilers, memory, runtimes, hardware acceleration, and the code that makes ML run fast.

| | |
|---|---|
|  **System Software** | C++17/20, compiler design, optimization passes, memory planning, lock-free data structures |
|  **Compiler + ML** | Computational graphs, operator fusion, constant folding, inference runtimes |
|  **Hardware + DL** | FPGA-accelerated deep learning, embedded inference, fault detection |
|  **Backend + AI** | FastAPI, Celery, Redis, GraphRAG, agentic workflows |
|  **Problem Solving** | Codeforces Specialist, 1,000+ problems solved |

> *Understand the problem. Engineer the solution. Measure the result.*

<div align="center">
<img src="https://skillicons.dev/icons?i=cpp,c,py,cmake,linux,git,docker,postgres,redis,mysql,mongodb,neo4j,fastapi&theme=dark" alt="Skills" />
</div>

---

##  Final Year Project

### ⚡ FPGA-Enabled Deep Learning for DC Series Arc Fault Detection

Series arc faults in DC systems (solar PV, EV charging, DC microgrids) are a fire-safety hazard and are hard to catch with conventional protection because the current signature is subtle. This project applies **deep learning on FPGA hardware** to detect them with low latency, suited to real-time protection.

- Deep learning model for classifying DC series arc fault signatures from current signals.
- Hardware-accelerated inference on **FPGA** for deterministic, low-latency detection.
- Sits at the intersection of **ML, embedded hardware, and systems-level optimization**, which is the same mindset behind my compiler and runtime work.

<div align="center">
<img src="https://img.shields.io/badge/Deep%20Learning-6366F1?style=flat-square" />
<img src="https://img.shields.io/badge/FPGA-0D9488?style=flat-square" />
<img src="https://img.shields.io/badge/Real--Time%20Inference-DB2777?style=flat-square" />
<img src="https://img.shields.io/badge/Fault%20Detection-F59E0B?style=flat-square" />
</div>

---

##  Projects

###  C++ Projects

#### 1. LiteTensor: C++17 Graph Compiler & Inference Runtime
<a href="https://github.com/KAILASH-SOU/GraphCompiler"><img src="https://img.shields.io/badge/VIEW%20REPOSITORY-0D9488?style=for-the-badge&logo=github&logoColor=white" /></a>

A computational-graph compiler and inference runtime built for optimization, memory efficiency, and execution speed.

- Designed a computational **DAG IR** and optimization pipeline.
- **Operator fusion:** `MatMul + Bias + ReLU → FusedMatMulBiasReLU`.
- **Constant folding** cut execution nodes by **40%**.
- **Static liveness-based memory planner** (linear-scan interval analysis) with 64-byte-aligned scratch-buffer reuse: **58% lower peak activation RAM** and **zero dynamic malloc/free** during inference.
- Cache-conscious `i-k-j` loop ordering and zero-copy tensor abstractions.
- Sub-millisecond latency, verified with **22 automated unit tests**.

![C++17](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Google Test](https://img.shields.io/badge/Google%20Test-4285F4?style=flat-square)
![Compiler](https://img.shields.io/badge/Compiler%20Design-6366F1?style=flat-square)

#### 2. High-Performance Low-Latency Trading Engine
<a href="https://github.com/KAILASH-SOU/High-Performance-Low-Latency-Trading-Engine"><img src="https://img.shields.io/badge/VIEW%20REPOSITORY-F59E0B?style=for-the-badge&logo=github&logoColor=white" /></a>

A C++20 trading engine built around systems performance.

- **Price-time priority order book** and matching engine.
- **Lock-free queues** and **memory pools** to avoid contention and allocation on the hot path.
- **TCP networking** layer and **performance benchmarking** harness.

![C++20](https://img.shields.io/badge/C%2B%2B20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Lock-Free](https://img.shields.io/badge/Lock--Free%20Queues-DB2777?style=flat-square)
![Memory Pools](https://img.shields.io/badge/Memory%20Pools-0D9488?style=flat-square)
![TCP](https://img.shields.io/badge/TCP%20Networking-6366F1?style=flat-square)

<!-- TODO: add any other C++ repos from your GitHub here, same format as above -->

---

###  Current Projects

#### 3. Enterprise GraphRAG Platform
<a href="https://github.com/KAILASH-SOU/Enterprise-GraphRAG-Engine"><img src="https://img.shields.io/badge/VIEW%20REPOSITORY-2563EB?style=for-the-badge&logo=github&logoColor=white" /></a>

Multi-tenant knowledge-graph retrieval backend for cross-document search and multi-hop reasoning.

- Entity-resolution pipeline using vector similarity plus LLM verification.
- **Leiden community detection** for hierarchical graph summaries, cutting LLM token usage by about **90%**.
- Custom **AST middleware** that injects tenant-isolation constraints into Neo4j Cypher queries.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-7C3AED?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

#### 4. Autonomous Codebase Refactoring Agent
<a href="https://github.com/KAILASH-SOU/Autonomous-Refactoring-Agent"><img src="https://img.shields.io/badge/VIEW%20REPOSITORY-7C3AED?style=for-the-badge&logo=github&logoColor=white" /></a>

Self-healing refactoring system built on AST analysis, isolated validation, and async workers.

- AST-based analysis and code transformation.
- Syntax and test validation in isolated subprocesses, with **automatic rollback** to prevent regressions.
- Async pipeline on FastAPI, Celery, and Redis Pub/Sub, streaming telemetry, diffs, and PRs over WebSockets.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-6366F1?style=flat-square)

#### 5. Local-First Incident Command System
<a href="https://github.com/KAILASH-SOU/Incident-Command-System"><img src="https://img.shields.io/badge/VIEW%20REPOSITORY-DB2777?style=for-the-badge&logo=github&logoColor=white" /></a>

Offline-capable incident-management and diagnostic system for investigating network outages.

- Telemetry-ingestion engine in Python and FastAPI.
- Local model execution with **Ollama** for privacy and offline use.
- Hybrid multi-agent RAG workflow that combines past post-mortems with runtime logs into remediation plans.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-171717?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0D9488?style=flat-square)

---

###  More Projects

Credit-card fraud detection (DT, RF, XGBoost, LightGBM), a content-based movie recommender, frontend projects, and more.

<div align="center">
<a href="https://github.com/KAILASH-SOU?tab=repositories">
  <img src="https://img.shields.io/badge/BROWSE%20ALL%20REPOSITORIES-0F172A?style=for-the-badge&logo=github&logoColor=2DD4BF" alt="All repositories" />
</a>
</div>

---

##  Competitive Programming

<div align="center">

<a href="https://codeforces.com/profile/Kailash_Choudhari"><img src="https://codeforces-readme-stats.vercel.app/api/card?username=Kailash_Choudhari&theme=dark" alt="Codeforces" /></a>
<a href="https://leetcode.com/u/Kailash_Choudhari/"><img src="https://leetcard.jacoblin.cool/Kailash_Choudhari?theme=dark&font=Inter&ext=activity" alt="LeetCode" /></a>

</div>

| Platform | Highlight | Profile |
|---|---|---|
| **Codeforces** | Specialist · Rank **963** in Round 1110 (14,000+ participants) | [Kailash_Choudhari](https://codeforces.com/profile/Kailash_Choudhari) |
| **LeetCode** | Rank **1,351** in Contest 475 (28,000+ participants) | [Kailash_Choudhari](https://leetcode.com/u/Kailash_Choudhari/) |
| **CodeChef** | Rank **361** in Starters 190 (14,000+ participants) | |

-  **1,000+ problems** solved across LeetCode, Codeforces, and CodeChef.
-  **Top 5** in the B.Tech 2027 batch in DSA course evaluation, **Top 3** in the CSE minor.
-  **NatWest Code for Purpose:** qualified Round 1 among 5,000+ national participants.
- ➗ Winner of the "Who is the Boss" mathematical challenge by AXIS Club, VNIT Nagpur.

---

##  Technical Skills

| Area | Skills |
|---|---|
| **Languages** | C++ (17/20), C, Python, SQL |
| **Systems & Compilers** | IRs, optimization passes, operator fusion, constant folding, liveness-based memory planning, cache-aware loops, lock-free structures |
| **Hardware & DL** | FPGA-based inference, deep learning, real-time signal classification |
| **Backend** | FastAPI, REST, WebSockets, Celery, Redis Pub/Sub, event-driven design |
| **ML & AI** | RAG, GraphRAG, LangChain, LangGraph, vector search, knowledge graphs, agentic workflows |
| **Databases & Tools** | PostgreSQL, MySQL, MongoDB, Neo4j, Redis, Docker, Git, Linux, CMake |
| **CS Core** | DSA, OS, Computer Networks, DBMS, OOP, Compiler Design |

---

##  Education

**Visvesvaraya National Institute of Technology (VNIT), Nagpur** · B.Tech 2023–2027
- Major: Electrical & Electronics Engineering, CGPA **8.15**
- Minor: Computer Science & Engineering, CGPA **8.50**

**Rajasthan Board:** Class XII **95%** · Class X **97.67%**

---

##  GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=KAILASH-SOU&show_icons=true&theme=tokyonight&hide_border=true&title_color=2DD4BF&icon_color=818CF8" alt="Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KAILASH-SOU&layout=compact&theme=tokyonight&hide_border=true&title_color=2DD4BF" alt="Top languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=KAILASH-SOU&theme=tokyonight&hide_border=true" alt="Streak" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=KAILASH-SOU&theme=tokyonight&no-frame=true&row=1&column=7" alt="Trophies" />

</div>

---

<div align="center">

### Let's Connect

<a href="mailto:soukailash46@gmail.com"><img src="https://img.shields.io/badge/Email-DB2777?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/kailash-choudhary-55b0b1280/"><img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://codeforces.com/profile/Kailash_Choudhari"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" /></a>
<a href="https://leetcode.com/u/Kailash_Choudhari/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>

<sub>Building efficient software and exploring systems from the inside out.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:0D9488,100:6366F1&height=110&section=footer" width="100%" alt="" />

</div>
