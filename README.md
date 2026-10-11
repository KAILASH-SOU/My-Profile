
<!-- Dual-target profile: Systems Software + Python SDE -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:76B900,50:168AAD,100:306998&height=230&section=header&text=Kailash&fontSize=76&fontColor=FFFFFF&fontAlignY=36&desc=Systems%20Software%20%7C%20Compiler%20%26%20ML%20%7C%20Python%20Engineering&descAlignY=58&descSize=17" width="100%" alt="Kailash — Systems Software, Compiler and ML, Python Engineering" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1200&color=76B900&center=true&vCenter=true&width=760&lines=Building+efficient+C%2B%2B+compiler+and+inference+systems;Engineering+reliable+Python+backends+and+APIs;Connecting+ML+ideas+with+practical+software" alt="Engineering focus" />
  <br/><br/>
  <a href="https://github.com/KAILASH-SOU"><img src="https://komarev.com/ghpvc/?username=KAILASH-SOU&label=PROFILE%20VIEWS&color=76B900&style=for-the-badge" alt="Profile views" /></a>
  <a href="https://github.com/KAILASH-SOU?tab=repositories"><img src="https://img.shields.io/badge/Explore-Projects-168AAD?style=for-the-badge&logo=github&logoColor=white" alt="Explore projects" /></a>
</div>

---

## About Me

I'm a B.Tech student at **VNIT Nagpur (2023–2027)**, majoring in Electrical & Electronics Engineering and minoring in Computer Science & Engineering. I enjoy working across two complementary areas of software engineering:

- **Systems, Compiler & ML:** C/C++, compiler passes, computational graphs, inference runtime optimization, memory planning, and performance.
- **Python & Backend Engineering:** APIs, asynchronous task pipelines, databases, event-driven systems, and applied-AI services.
- **Problem solving:** Codeforces Specialist; 1,000+ DSA problems solved across LeetCode, Codeforces, and CodeChef.

I like understanding how systems work internally and turning that understanding into software that is measurable, maintainable, and useful.

> Build for correctness. Measure performance. Design for reliability.

## Featured Projects

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">LiteTensor — C++17 Graph Compiler & Inference Runtime</h3>
      <p align="center"><img src="https://img.shields.io/badge/Focus-Compiler%20%26%20ML-76B900?style=for-the-badge" alt="Compiler and ML" /></p>
      <p>A computational-graph compiler and inference runtime focused on graph optimization and memory efficiency.</p>
      <ul>
        <li>Built a DAG intermediate representation and optimization pipeline.</li>
        <li>Implemented operator fusion and constant folding; the project reports a 40% reduction in execution nodes.</li>
        <li>Built static liveness-based memory planning with 64-byte-aligned scratch-buffer offsets; reports 58% lower peak activation RAM and no dynamic <code>malloc/free</code> during inference.</li>
        <li>Implemented cache-conscious loop ordering and zero-copy tensor abstractions.</li>
        <li>Reported sub-millisecond latency and tested with 22 Google Test cases.</li>
      </ul>
      <p><strong>Stack:</strong> C++17, CMake, Google Test</p>
      <a href="https://github.com/KAILASH-SOU/GraphCompiler">View LiteTensor repository</a>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Enterprise GraphRAG Platform</h3>
      <p align="center"><img src="https://img.shields.io/badge/Focus-Python%20%26%20Backend-168AAD?style=for-the-badge" alt="Python and backend" /></p>
      <p>A multi-tenant knowledge-graph retrieval backend for cross-document and multi-hop reasoning.</p>
      <ul>
        <li>Engineered entity resolution using vector similarity and LLM verification.</li>
        <li>Used hierarchical graph summaries to reduce LLM token usage by approximately 90%.</li>
        <li>Built AST middleware to inject tenant-isolation constraints into Neo4j Cypher queries.</li>
        <li>Combined API services, graph/vector databases, and containerized deployment.</li>
      </ul>
      <p><strong>Stack:</strong> Python, FastAPI, Neo4j, Qdrant, PostgreSQL, Docker</p>
      <a href="https://github.com/KAILASH-SOU/Enterprise-GraphRAG-Engine">View GraphRAG repository</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Autonomous Codebase Refactoring Agent</h3>
      <p>A Python-based refactoring workflow using AST analysis, isolated subprocess validation, test execution, and rollback handling.</p>
      <ul>
        <li>Separated compute-heavy agent tasks from the web server with asynchronous workers.</li>
        <li>Streamed execution telemetry and diffs through WebSockets.</li>
      </ul>
      <p><strong>Stack:</strong> Python, FastAPI, Celery, Redis, AST, WebSockets</p>
      <a href="https://github.com/KAILASH-SOU/Autonomous-Refactoring-Agent">View refactoring agent repository</a>
    </td>
    <td width="50%" valign="top">
      <h3>Local-First Incident Command System</h3>
      <p>A local-first incident and diagnostic workflow designed to preserve availability during network outages.</p>
      <ul>
        <li>Built a telemetry ingestion API and structured-log workflow.</li>
        <li>Used local model execution and a multi-agent RAG workflow to synthesize logs and historical post-mortems.</li>
      </ul>
      <p><strong>Stack:</strong> Python, FastAPI, Ollama, RAG, structured logs</p>
      <a href="https://github.com/KAILASH-SOU/Incident-Command-System">View Incident Command repository</a>
    </td>
  </tr>
</table>

## Technical Skills

<div align="center">
  <h3>Systems, C/C++ & Developer Tools</h3>
  <img src="https://skillicons.dev/icons?i=cpp,c,linux,cmake,git&perline=8" alt="C, C++, Linux, CMake, Git" />
  <br/><br/>
  <h3>Python, Backend & Data</h3>
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,mongodb,redis,docker&perline=8" alt="Python, FastAPI, PostgreSQL, MongoDB, Redis, Docker" />
</div>

- **Languages:** C++, C, Python, SQL
- **Compiler & ML systems:** Computational DAG IR, compiler passes, operator fusion, constant folding, static memory planning, inference runtime optimization
- **Python & backend:** FastAPI, Streamlit, REST APIs, WebSockets, asynchronous processing, Celery
- **AI/ML:** Machine Learning, Deep Learning, RAG, LangChain, LangGraph, LangSmith, agentic workflows
- **Databases:** PostgreSQL, MySQL, MongoDB, Redis, Qdrant, Neo4j
- **Core CS:** DSA, OOP, Operating Systems, Computer Networks, DBMS, Compiler Design
- **Tools:** Docker, Git, GitHub, CMake, Google Test

## Competitive Programming & Achievements

<div align="center">
  <a href="https://codeforces.com/profile/Kailash_Choudhari"><img src="https://codeforces-readme-stats.vercel.app/api/card?username=Kailash_Choudhari&theme=dark" alt="Codeforces stats" /></a>
  <a href="https://leetcode.com/u/Kailash_Choudhari/"><img src="https://leetcard.jacoblin.cool/Kailash_Choudhari?theme=dark&font=Inter&ext=activity" alt="LeetCode stats" /></a>
</div>

- **Codeforces:** Specialist; Rank **963** in Codeforces Round 1110 among 14,000+ participants.
- **LeetCode:** Rank **1,351** in Contest 475 among 28,000+ participants.
- **CodeChef:** Rank **361** in Starters 190 among 14,000+ participants.
- **Problem solving:** 1,000+ DSA problems solved across LeetCode, Codeforces, and CodeChef.
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
  <img src="https://github-readme-stats.vercel.app/api?username=KAILASH-SOU&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=76B900&icon_color=168AAD" alt="GitHub statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KAILASH-SOU&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=168AAD" alt="Top languages" />
  <br/><br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=KAILASH-SOU&theme=dark&hide_border=true&background=0D1117" alt="GitHub contribution streak" />
</div>

<div align="center">
  <sub>Compiler and runtime experiments, reliable Python services, and continuous learning.</sub>
</div>
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:76B900,100:168AAD&height=100&section=footer" width="100%" alt="" />
