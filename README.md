
<!-- GitHub Profile: Software Engineering + System Software Engineering -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=76B900&height=180&section=header&text=Kailash&fontSize=60&fontColor=FFFFFF&fontAlignY=38" width="100%" alt="Kailash" />

  <h2>Software Engineering | System Software Engineering</h2>

  <p>
    Interested in building efficient software, compiler systems,
    ML runtimes, and scalable Python backends.
  </p>

  <p>
    <a href="https://github.com/KAILASH-SOU">
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="https://www.linkedin.com/in/kailash-55b0b1280/">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:soukailash46@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

  <p>
    <img src="https://komarev.com/ghpvc/?username=KAILASH-SOU&label=Profile%20Views&color=76B900&style=flat-square" alt="Profile views" />
  </p>
</div>

---

## About Me

I'm a B.Tech student at **Visvesvaraya National Institute of Technology (VNIT), Nagpur**, majoring in Electrical & Electronics Engineering and minoring in Computer Science & Engineering.

I'm interested in **Software Engineering and System Software Engineering**, with a focus on understanding how software works internally and building efficient, reliable systems.

- **System Software & Compilers:** C++, compiler passes, computational graphs, memory planning, and inference runtime optimization.
- **Python & Backend Engineering:** FastAPI, REST APIs, asynchronous processing, databases, and event-driven systems.
- **Machine Learning & AI:** ML inference, GraphRAG, retrieval systems, and agentic workflows.
- **Problem Solving:** Codeforces Specialist with 1,000+ DSA problems solved across LeetCode, Codeforces, and CodeChef.

> Build for correctness. Measure performance. Design for reliability.

## Featured Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">LiteTensor — C++17 Graph Compiler & Inference Runtime</h3>

      <p align="center">
        <img src="https://img.shields.io/badge/C%2B%2B-17-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++17" />
        <img src="https://img.shields.io/badge/Compiler-Optimization-76B900?style=flat-square" alt="Compiler optimization" />
        <img src="https://img.shields.io/badge/ML-Inference-168AAD?style=flat-square" alt="ML inference" />
      </p>

      A computational-graph compiler and inference runtime focused on graph optimization, memory efficiency, and execution performance.

      - Designed a computational DAG intermediate representation and optimization pipeline.
      - Implemented operator fusion (`MatMul + Bias + ReLU`) and constant folding, reducing execution nodes by **40%**.
      - Developed a static liveness-based memory planner using linear-scan interval analysis.
      - Reused 64-byte-aligned scratch-buffer offsets, reducing peak activation RAM by **58%** with zero dynamic `malloc/free` allocations during inference.
      - Implemented cache-conscious `i-k-j` loop ordering and non-owning zero-copy tensor abstractions.
      - Achieved reported sub-millisecond execution latency and validated correctness with **22 automated unit tests**.

      **Technologies:** C++17, Compiler Passes, Operator Fusion, Memory Planning, CMake, Google Test

      <p>
        <a href="https://github.com/KAILASH-SOU/GraphCompiler">
          <img src="https://img.shields.io/badge/View_Repository-76B900?style=for-the-badge&logo=github&logoColor=white" alt="View LiteTensor repository" />
        </a>
      </p>
    </td>

    <td width="50%" valign="top">
      <h3 align="center">Enterprise GraphRAG Platform</h3>

      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/Neo4j-018BFF?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j" />
      </p>

      A multi-tenant knowledge-graph retrieval backend that enables advanced cross-document search and multi-hop reasoning.

      - Engineered an entity-resolution pipeline using vector similarity and LLM verification to merge duplicate aliases.
      - Implemented the Leiden community detection algorithm to generate hierarchical graph summaries.
      - Reduced LLM token usage by approximately **90%** through precomputed graph summaries.
      - Developed custom AST middleware that injects tenant-isolation constraints into Neo4j Cypher queries.

      **Technologies:** Python, FastAPI, Streamlit, Neo4j, Qdrant, PostgreSQL, Docker

      <p>
        <a href="https://github.com/KAILASH-SOU/Enterprise-GraphRAG-Engine">
          <img src="https://img.shields.io/badge/View_Repository-168AAD?style=for-the-badge&logo=github&logoColor=white" alt="View GraphRAG repository" />
        </a>
      </p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Autonomous Codebase Refactoring Agent</h3>

      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/AST-Analysis-168AAD?style=flat-square" alt="AST analysis" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
      </p>

      An automated code-refactoring system that analyzes source code, validates changes, and helps prevent regressions.

      - Built AST-based refactoring workflows with sandboxed execution.
      - Validated syntax and test suites in isolated subprocesses.
      - Implemented self-healing rollbacks to prevent regressions.
      - Designed an asynchronous, event-driven pipeline using Celery and Redis Pub/Sub.
      - Streamed execution telemetry, unified diffs, and pull requests over WebSockets.

      **Technologies:** Python, FastAPI, Streamlit, Celery, AST, Redis, WebSockets

      <p>
        <a href="https://github.com/KAILASH-SOU/Autonomous-Refactoring-Agent">
          <img src="https://img.shields.io/badge/View_Repository-168AAD?style=for-the-badge&logo=github&logoColor=white" alt="View refactoring agent repository" />
        </a>
      </p>
    </td>

    <td width="50%" valign="top">
      <h3 align="center">Local-First Incident Command System</h3>

      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/RAG-AI-76B900?style=flat-square" alt="RAG" />
      </p>

      A local-first incident-management and diagnostic system designed to support investigation workflows during network outages.

      - Engineered a telemetry-ingestion API using Python and FastAPI.
      - Integrated Ollama for local model execution to support data privacy and offline availability.
      - Built a hybrid multi-agent RAG workflow for incident investigation.
      - Synthesized historical post-mortems and runtime logs into actionable remediation plans.

      **Technologies:** Python, FastAPI, Ollama, RAG, Structured Logs

      <p>
        <a href="https://github.com/KAILASH-SOU/Incident-Command-System">
          <img src="https://img.shields.io/badge/View_Repository-168AAD?style=for-the-badge&logo=github&logoColor=white" alt="View Incident Command repository" />
        </a>
      </p>
    </td>
  </tr>
</table>

---

## Technical Skills

<div align="center">
  <h3>Systems Programming & Developer Tools</h3>
  <img src="https://skillicons.dev/icons?i=cpp,c,linux,cmake,git&perline=8" alt="C, C++, Linux, CMake and Git" />

  <br/><br/>

  <h3>Python, Backend & Databases</h3>
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,mongodb,redis,docker&perline=8" alt="Python, FastAPI, PostgreSQL, MongoDB, Redis and Docker" />
</div>

### Programming Languages
- C++, C, Python, SQL

### System Software & Compiler Engineering
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
- LangChain, LangGraph, LangSmith
- Agentic Workflows
- Vector Search and Knowledge Graphs

### Databases & Infrastructure
- PostgreSQL, MySQL, MongoDB
- Redis, Qdrant, Neo4j
- Docker, Git, GitHub
- CMake and Google Test

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
- **Problem Solving:** Solved **1,000+ DSA problems** across LeetCode, Codeforces, and CodeChef.
- **NatWest Code for Purpose:** Qualified Round 1 among 5,000+ national participants.
- **Academic Excellence:** Ranked among the Top 5 students in the B.Tech 2027 batch in DSA course evaluation and secured a Top 3 rank in the CSE minor.
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

## Connect With Me

<div align="center">
  <a href="https://github.com/KAILASH-SOU">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/kailash-55b0b1280/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:soukailash46@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://codeforces.com/profile/Kailash_Choudhari">
    <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" />
  </a>
  <a href="https://leetcode.com/u/Kailash_Choudhari/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" />
  </a>
</div>

<div align="center">
  <br/>
  <img src="https://github-readme-stats.vercel.app/api?username=KAILASH-SOU&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=76B900&icon_color=168AAD" alt="GitHub statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KAILASH-SOU&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=168AAD" alt="Most used languages" />
  <br/><br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=KAILASH-SOU&theme=dark&hide_border=true&background=0D1117" alt="GitHub contribution streak" />
</div>

<div align="center">
  <sub>Building efficient software, exploring systems from the inside out, and learning through hands-on engineering.</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=76B900&height=100&section=footer" width="100%" alt="" />
