
<!-- ===================================================== -->
<!-- KAILASH | SOFTWARE ENGINEERING + SYSTEM SOFTWARE       -->
<!-- ===================================================== -->

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:0D9488,100:6366F1&height=190&section=header&text=Kailash&fontSize=64&fontColor=FFFFFF&fontAlignY=38" width="100%" alt="Kailash" />

  <h2>Software Engineering | System Software Engineering</h2>

  <p>
    Interested in compiler design, machine learning systems,
    efficient C++ software, and scalable Python backends.
  </p>

  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=3000&pause=1200&color=0D9488&center=true&vCenter=true&width=650&lines=Building+efficient+software;Exploring+compilers+and+ML+systems;Engineering+reliable+Python+backends" alt="Animated engineering interests" />

  <br/>

  <a href="https://github.com/KAILASH-SOU">
    <img src="https://img.shields.io/badge/GitHub-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/kailash-55b0b1280/">
    <img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:soukailash46@gmail.com">
    <img src="https://img.shields.io/badge/Email-DB2777?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

  <br/><br/>

  <img src="https://komarev.com/ghpvc/?username=KAILASH-SOU&label=PROFILE%20VIEWS&color=0D9488&style=flat-square" alt="Profile views" />

</div>

---

## About Me

I'm a B.Tech student at **Visvesvaraya National Institute of Technology (VNIT), Nagpur**, majoring in Electrical & Electronics Engineering and minoring in Computer Science & Engineering.

I'm interested in **Software Engineering and System Software Engineering**, with a focus on building efficient, reliable software and understanding how systems work internally.

- **System Software:** C++, compiler design, optimization passes, memory planning, and runtime performance.
- **Compiler & ML:** Computational graphs, operator fusion, constant folding, and inference runtimes.
- **Python & Backend:** FastAPI, REST APIs, asynchronous processing, databases, and event-driven systems.
- **Applied AI:** Machine learning, GraphRAG, retrieval systems, and agentic workflows.
- **Problem Solving:** Codeforces Specialist with 1,000+ DSA problems solved.

> Understand the problem. Engineer the solution. Measure the result.

## Featured Projects

### 1. LiteTensor — C++17 Graph Compiler & Inference Runtime

<a href="https://github.com/KAILASH-SOU/GraphCompiler">
  <img src="https://img.shields.io/badge/VIEW%20REPOSITORY-0D9488?style=for-the-badge&logo=github&logoColor=white" alt="View LiteTensor repository" />
</a>

A computational-graph compiler and inference runtime focused on optimization, memory efficiency, and execution performance.

**Key engineering work**

- Designed a computational DAG intermediate representation and optimization pipeline.
- Implemented operator fusion: `MatMul + Bias + ReLU → FusedMatMulBiasReLU`.
- Developed constant folding, reducing execution nodes by **40%**.
- Implemented a static liveness-based memory planner using linear-scan interval analysis.
- Reused 64-byte-aligned scratch-buffer offsets, reducing peak activation RAM by **58%** with zero dynamic `malloc/free` allocations during inference.
- Implemented cache-conscious `i-k-j` loop ordering and zero-copy tensor abstractions.
- Reported sub-millisecond execution latency and validated correctness with **22 automated unit tests**.

**Tech stack**

![C++17](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Compiler](https://img.shields.io/badge/Compiler%20Design-6366F1?style=flat-square)
![ML](https://img.shields.io/badge/ML%20Inference-0D9488?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Google Test](https://img.shields.io/badge/Google%20Test-4285F4?style=flat-square)

### 2. Enterprise GraphRAG Platform

<a href="https://github.com/KAILASH-SOU/Enterprise-GraphRAG-Engine">
  <img src="https://img.shields.io/badge/VIEW%20REPOSITORY-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="View GraphRAG repository" />
</a>

A multi-tenant knowledge-graph retrieval backend enabling cross-document search and multi-hop reasoning.

**Key engineering work**

- Built an entity-resolution pipeline using vector similarity and LLM verification.
- Implemented the Leiden community detection algorithm to generate hierarchical graph summaries.
- Reduced LLM token usage by approximately **90%** through precomputed graph summaries.
- Developed custom AST middleware to inject tenant-isolation constraints into Neo4j Cypher queries.

**Tech stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-7C3AED?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### 3. Autonomous Codebase Refactoring Agent

<a href="https://github.com/KAILASH-SOU/Autonomous-Refactoring-Agent">
  <img src="https://img.shields.io/badge/VIEW%20REPOSITORY-7C3AED?style=for-the-badge&logo=github&logoColor=white" alt="View refactoring agent repository" />
</a>

An automated code-refactoring system using AST analysis, isolated validation, asynchronous workers, and rollback handling.

**Key engineering work**

- Analyzed and transformed source code using Abstract Syntax Trees.
- Validated syntax and test suites in isolated subprocesses.
- Implemented self-healing rollbacks to prevent regressions.
- Built an asynchronous pipeline using FastAPI, Celery, and Redis Pub/Sub.
- Streamed execution telemetry, unified diffs, and pull requests over WebSockets.

**Tech stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-6366F1?style=flat-square)

### 4. Local-First Incident Command System

<a href="https://github.com/KAILASH-SOU/Incident-Command-System">
  <img src="https://img.shields.io/badge/VIEW%20REPOSITORY-DB2777?style=for-the-badge&logo=github&logoColor=white" alt="View Incident Command repository" />
</a>

A local-first incident-management and diagnostic system designed to support investigations during network outages.

**Key engineering work**

- Built a telemetry-ingestion engine using Python and FastAPI.
- Integrated Ollama for local model execution to support privacy and offline availability.
- Developed a hybrid multi-agent RAG diagnostic workflow.
- Combined historical post-mortems and runtime logs into actionable remediation plans.

**Tech stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-171717?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0D9488?style=flat-square)

---

## Technical Skills

### Programming Languages

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square)

### Systems & Compiler Engineering

- Compiler Design and Optimization Passes
- Computational Graphs and Intermediate Representations
- Operator Fusion and Constant Folding
- Static Liveness-Based Memory Planning
- Cache-Conscious Loop Optimization
- Inference Runtime Optimization

### Python & Backend Engineering

- FastAPI and Streamlit
- RESTful APIs and WebSockets
- Asynchronous Processing
- Celery and Redis Pub/Sub
- Event-Driven Backend Systems

### Machine Learning & Applied AI

- Machine Learning and Deep Learning
- Retrieval-Augmented Generation (RAG)
- LangChain, LangGraph, and LangSmith
- Agentic Workflows
- Vector Search and Knowledge Graphs

### Databases & Tools

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

### Core Computer Science

- Data Structures and Algorithms
- Object-Oriented Programming
- Operating Systems
- Computer Networks
- Database Management Systems
- Compiler Design

---

## Competitive Programming & Achievements

<div align="center">

  <a href="https://codeforces.com/profile/Kailash_Choudhari">
    <img src="https://codeforces-readme-stats.vercel.app/api/card?username=Kailash_Choudhari&theme=dark" alt="Codeforces statistics" />
  </a>

  <a href="https://leetcode.com/u/Kailash_Choudhari/">
    <img src="https://leetcard.jacoblin.cool/Kailash_Choudhari?theme=dark&font=Inter&ext=activity" alt="LeetCode statistics" />
  </a>

</div>

- **Codeforces:** Specialist; Rank **963** in Codeforces Round 1110 among 14,000+ participants.
- **LeetCode:** Rank **1,351** in Contest 475 among 28,000+ participants.
- **CodeChef:** Rank **361** in Starters 190 among 14,000+ participants.
- **Problem Solving:** 1,000+ problems solved across LeetCode, Codeforces, and CodeChef.
- **NatWest Code for Purpose:** Qualified Round 1 among 5,000+ national participants.
- **Academic Excellence:** Top 5 in the B.Tech 2027 batch in DSA course evaluation; Top 3 in the CSE minor.
- **Mathematical Aptitude:** Won the "Who is the Boss" mathematical challenge organized by AXIS Club, VNIT Nagpur.

---

## Education

**Visvesvaraya National Institute of Technology (VNIT), Nagpur**

Bachelor of Technology | 2023–2027

- Major: Electrical & Electronics Engineering — CGPA **8.15**
- Minor: Computer Science & Engineering — CGPA **8.50**

**Rajasthan Board of Secondary Education**

- Class XII: **95%**
- Class X: **97.67%**

---

## GitHub Analytics

<div align="center">

  <img src="https://github-readme-stats.vercel.app/api?username=KAILASH-SOU&show_icons=true&theme=tokyonight&hide_border=true&title_color=2DD4BF&icon_color=818CF8" alt="GitHub statistics" />

  <br/><br/>

  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KAILASH-SOU&layout=compact&theme=tokyonight&hide_border=true&title_color=2DD4BF" alt="Most used languages" />

  <br/><br/>

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=KAILASH-SOU&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

</div>

---

## Connect With Me

<div align="center">

  <a href="https://github.com/KAILASH-SOU">
    <img src="https://img.shields.io/badge/GitHub-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>

  <a href="https://www.linkedin.com/in/kailash-55b0b1280/">
    <img src="https://img.shields.io/badge/LinkedIn-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>

  <a href="mailto:soukailash46@gmail.com">
    <img src="https://img.shields.io/badge/Email-DB2777?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

  <a href="https://codeforces.com/profile/Kailash_Choudhari">
    <img src="https://img.shields.io/badge/Codeforces-0EA5E9?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" />
  </a>

  <a href="https://leetcode.com/u/Kailash_Choudhari/">
    <img src="https://img.shields.io/badge/LeetCode-F59E0B?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" />
  </a>

</div>

<div align="center">
  <br/>
  <sub>Building efficient software, exploring systems from the inside out, and learning through hands-on engineering.</sub>
  <br/><br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:0D9488,100:6366F1&height=100&section=footer" width="100%" alt="" />
</div>
