from pathlib import Path

readme = r'''<!-- NVIDIA-oriented GitHub Profile README -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=76B900&height=230&section=header&text=Kailash&fontSize=76&fontColor=FFFFFF&fontAlignY=36&desc=Systems%20Software%20%7C%20Compilers%20%7C%20Performance%20Engineering&descAlignY=58&descSize=18" width="100%" alt="Kailash — Systems Software, Compilers, Performance Engineering" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=76B900&center=true&vCenter=true&width=720&lines=Exploring+how+software+executes+under+the+hood;Building+C%2B%2B+compiler+and+inference+systems;Optimizing+memory%2C+compute%2C+and+runtime+performance" alt="Systems software focus" />
  <br/><br/>
  <a href="https://github.com/KAILASH-SOU"><img src="https://komarev.com/ghpvc/?username=KAILASH-SOU&label=PROFILE%20VIEWS&color=76B900&style=for-the-badge" alt="Profile views" /></a>
  <a href="https://github.com/KAILASH-SOU?tab=repositories"><img src="https://img.shields.io/badge/Projects-Explore-76B900?style=for-the-badge&logo=github&logoColor=white" alt="Explore projects" /></a>
</div>

---

## About Me

I'm a B.Tech student at **VNIT Nagpur (2023–2027)**, majoring in Electrical & Electronics Engineering and minoring in Computer Science & Engineering. I'm interested in the layers that make software fast and reliable: **compiler design, runtime systems, memory management, operating systems, and performance engineering**.

- **Current direction:** Systems software, C/C++, compiler pipelines, and inference runtimes.
- **Engineering interests:** Intermediate representations, optimization passes, memory planning, cache locality, and runtime behavior.
- **Problem solving:** Codeforces Specialist; 1,000+ DSA problems solved across LeetCode, Codeforces, and CodeChef.
- **Also build:** Backend infrastructure and applied-AI systems.

> Understand the execution path. Measure the bottleneck. Optimize with evidence.

## Featured Project

<div align="center">
  <h3>LiteTensor — C++17 Graph Compiler & Inference Runtime</h3>
  <p><em>A compact computational-graph compiler and inference runtime focused on graph optimization and memory efficiency.</em></p>
  <img src="https://img.shields.io/badge/C%2B%2B-17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++17" />
  <img src="https://img.shields.io/badge/Compiler-Passes-76B900?style=for-the-badge" alt="Compiler passes" />
  <img src="https://img.shields.io/badge/Testing-Google_Test-4285F4?style=for-the-badge" alt="Google Test" />
</div>

**Highlights from the project**
- Designed a computational DAG intermediate representation and optimization pipeline.
- Implemented **operator fusion** (`MatMul + Bias + ReLU`) and constant folding; the project reports a **40% reduction in execution nodes**.
- Built a static liveness-based memory planner using linear-scan interval analysis, reusing **64-byte-aligned** scratch-buffer offsets; the project reports **58% lower peak activation RAM** and no dynamic `malloc/free` during inference.
- Implemented cache-conscious `i-k-j` loop ordering and non-owning zero-copy tensor abstractions.
- Reported sub-millisecond execution latency and validated correctness with **22 automated Google Test unit tests**.

<a href="https://github.com/KAILASH-SOU?tab=repositories"><img src="https://img.shields.io/badge/Explore%20Code%20%26%20Projects-76B900?style=for-the-badge&logo=github&logoColor=white" alt="Explore code and projects" /></a>

---

## Systems & Software Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>LiteTensor — Graph Compiler & Inference Runtime</h3>
      <p>Compiler IR, graph optimization, operator fusion, constant folding, static memory planning, cache-aware kernels.</p>
      <p><strong>Stack:</strong> C++17, CMake, Google Test</p>
      <a href="https://github.com/KAILASH-SOU?tab=repositories">Find project in repositories</a>
    </td>
    <td width="50%" valign="top">
      <h3>Enterprise GraphRAG Platform</h3>
      <p>Multi-tenant knowledge-graph retrieval with entity resolution, hierarchical graph summaries, and tenant-isolation middleware.</p>
      <p><strong>Stack:</strong> Python, FastAPI, Neo4j, Qdrant, PostgreSQL, Docker</p>
      <a href="https://github.com/KAILASH-SOU/Enterprise-GraphRAG-Engine">Repository</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Autonomous Codebase Refactoring Agent</h3>
      <p>AST-based refactoring with isolated validation, test execution, rollback handling, and asynchronous execution telemetry.</p>
      <p><strong>Stack:</strong> Python, FastAPI, Celery, Redis, AST, WebSockets</p>
      <a href="https://github.com/KAILASH-SOU/Autonomous-Refactoring-Agent">Repository</a>
    </td>
    <td width="50%" valign="top">
      <h3>Local-First Incident Command System</h3>
      <p>Telemetry ingestion and local diagnostic workflows designed to remain useful when network access is unavailable.</p>
      <p><strong>Stack:</strong> Python, FastAPI, Ollama, RAG, structured logs</p>
      <a href="https://github.com/KAILASH-SOU?tab=repositories">Find project in repositories</a>
    </td>
  </tr>
</table>

## Technical Skills

<div align="center">
  <h3>C / C++ & Systems</h3>
  <img src="https://skillicons.dev/icons?i=cpp,c,linux,cmake,git&perline=8" alt="C, C++, Linux, CMake, Git" />
  <br/><br/>
  <h3>Backend & Data Infrastructure</h3>
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,mongodb,redis,docker&perline=8" alt="Python, FastAPI, PostgreSQL, MongoDB, Redis, Docker" />
</div>

- **Languages:** C++, C, Python, SQL
- **Systems & CS:** Data Structures and Algorithms, OOP, Operating Systems, Computer Networks, DBMS, Compiler Design
- **Compiler/runtime project work:** Computational DAG IR, compiler passes, operator fusion, constant folding, static liveness-based memory planning, cache-conscious loop ordering, zero-copy tensor abstractions
- **Backend & AI:** FastAPI, Streamlit, REST APIs, WebSockets, RAG, LangChain, LangGraph, LangSmith, agentic workflows
- **Databases:** PostgreSQL, MySQL, MongoDB, Redis, Qdrant, Neo4j
- **Tools:** Docker, Git, GitHub, CMake, Google Test

## Competitive Programming & Achievements

<div align="center">
  <a href="https://codeforces.com/profile/Kailash_Choudhari"><img src="https://codeforces-readme-stats.vercel.app/api/card?username=Kailash_Choudhari&theme=dark" alt="Codeforces stats" /></a>
  <a href="https://leetcode.com/u/Kailash_Choudhari/"><img src="https://leetcard.jacoblin.cool/Kailash_Choudhari?theme=dark&font=Inter&ext=activity" alt="LeetCode stats" /></a>
</div>

- **Codeforces:** Specialist; Rank **963** in Codeforces Round 1110 among 14,000+ participants.
- **LeetCode:** Rank **1,351** in Contest 475 among 28,000+ participants.
- **CodeChef:** Rank **361** in Starters 190 among 14,000+ participants.
- **DSA:** 1,000+ problems solved across LeetCode, Codeforces, and CodeChef.
- **NatWest Code for Purpose:** Qualified Round 1 among 5,000+ national participants.
- **Academics:** Top 5 in the B.Tech 2027 batch in DSA course evaluation; Top 3 in the CSE minor.
- **Mathematics:** Won the “Who is the Boss” mathematical challenge organized by AXIS Club, VNIT Nagpur.

## Education

**Visvesvaraya National Institute of Technology (VNIT), Nagpur**  
B.Tech, 2023–2027  
- Major: Electrical & Electronics Engineering — CGPA **8.15**
- Minor: Computer Science & Engineering — CGPA **8.50**

**Rajasthan Board of Secondary Education**
- Class XII: **95%**
- Class X: **97.67%**

## Connect

<div align="center">
  <a href="https://github.com/KAILASH-SOU"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/kailash-55b0b1280/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:soukailash46@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://codeforces.com/profile/Kailash_Choudhari"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
  <a href="https://leetcode.com/u/Kailash_Choudhari/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
</div>

<div align="center">
  <br/>
  <img src="https://github-readme-stats.vercel.app/api?username=KAILASH-SOU&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=76B900&icon_color=76B900" alt="GitHub statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KAILASH-SOU&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=76B900" alt="Top languages" />
  <br/><br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=KAILASH-SOU&theme=dark&hide_border=true&background=0D1117" alt="GitHub contribution streak" />
</div>

<div align="center">
  <sub>Building a stronger foundation in systems software, one experiment and benchmark at a time.</sub>
</div>
<img src="https://capsule-render.vercel.app/api?type=waving&color=76B900&height=100&section=footer" width="100%" alt="" />
'''

path = Path("/mnt/data/README_NVIDIA_Systems_Software.md")
path.write_text(readme, encoding="utf-8")
print(f"Created {path} ({len(readme):,} characters)")
