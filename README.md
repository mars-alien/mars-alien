<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Royal%20Sachan&fontSize=54&fontColor=ffffff&fontAlignY=34&desc=Backend%20%C2%B7%20Full-Stack%20%C2%B7%20Applied%20AI&descAlignY=54&descSize=18" width="100%" alt="banner" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=36BCF7&center=true&vCenter=true&width=520&height=45&lines=CSE+Student+at+IIIT+Manipur;Backend+%26+Full-Stack+Engineer;Applied+AI+%2F+RAG+%7C+LLMs;Building+Scalable+%26+Secure+Systems)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://royals-three.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/royalsachan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:royalsachaniiitm@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/spider-)

<img src="https://komarev.com/ghpvc/?username=mars-alien&style=flat-square&color=36BCF7&label=Profile+Views" alt="profile views" />
<img src="https://img.shields.io/badge/Open%20to-Backend%20%2F%20AI%20Roles-2F9E6E?style=flat-square" alt="open to work" />

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 🧭 About

> Final-year CSE student at **IIIT Manipur**, building secure, scalable backend systems — and the retrieval/agent layers on top of them.

I work across **Spring Boot, FastAPI, Node.js and PostgreSQL/MongoDB**, with production-shaped experience in **RAG pipelines, multi-agent systems and LLM tooling**, backed by a strong algorithmic foundation.

<table>
<tr>
<td width="50%" valign="top">

**🔐 Security & API design**
JWT auth + RBAC across **20+ REST endpoints** and 3 user roles — hardened with rate limiting, CORS and Helmet.js.

</td>
<td width="50%" valign="top">

**⚡ Performance**
Cut response time **~30%** on high-traffic endpoints through PostgreSQL indexing and query optimisation.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧠 Retrieval engineering**
Hybrid **BM25 + HNSW** retriever with Reciprocal Rank Fusion (BAAI/bge-m3, 1024-dim) in Weaviate, evaluated with RAGAS.

</td>
<td width="50%" valign="top">

**🔬 Research**
End-to-end **multi-bit watermarking for LLMs** — deterministic hashing, adaptive logit biasing, Z-score detection.

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📰 PaperTrail
**Multi-Article RAG Research Assistant**
*Paste news URLs → ask anything → get cited, streamed answers.*

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Weaviate-3B82F6?style=flat-square&logo=weaviate&logoColor=white" /> <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />

- **Hybrid retrieval** — BM25 (35%) + dense HNSW (65%) over BGE-small embeddings
- **Cross-encoder reranking** — `ms-marco-MiniLM` narrows top 24 → top 6
- **SSE streaming** answers with per-claim source citations
- Intent routing escalates summary/comparison queries to a stronger model

[![Repo](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mars-alien/paper-trail)
[![Live](https://img.shields.io/badge/Live_Demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://paper-trail-sigma-ten.vercel.app/)
[![API](https://img.shields.io/badge/API_Docs-46E3B7?style=flat-square&logo=render&logoColor=black)](https://paper-trail-g0xr.onrender.com/docs)

</td>
<td width="50%" valign="top">

### 🎟️ Nexus
**Event Companion Platform**
*Discover events near you, join groups, get promoted off the waitlist.*

<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" /> <img src="https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

- **Sub-100ms** distance-ranked search via PostGIS geospatial indexing
- **JWT refresh-token rotation** for stateless, revocable sessions
- Role-based group join approval + automated waitlist promotion
- Flyway-managed migrations, containerised and deployed on Render

[![Repo](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mars-alien/nexus)
[![Live](https://img.shields.io/badge/Live_Demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://nexus-royal.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌿 EcoRoute
**Intelligent Delivery Route Optimizer**
*Cluster orders geographically, sequence stops, cut fuel and emissions.*

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" /> <img src="https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

- **K-Means++ clustering → Nearest-Neighbour TSP**, written from scratch in pure Python — no ML-library wrappers
- Haversine distance + linear ETA model over MongoDB `2dsphere` indexes
- Optimisation core has zero FastAPI/Motor imports — fully unit-testable
- Role-split UI: admin dispatch console + driver route map

[![Repo](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mars-alien/EcoRoute)

</td>
<td width="50%" valign="top">

### 🏛️ Valura AI Arena
**Multi-Agent Financial Analyst Ecosystem**
*Eight Agno agents answering client-book questions — provably in scope.*

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Agno-6D28D9?style=flat-square&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />

- **96.00 / 96 offline**; 96.00 and 94.88 on two unseen books, 100% availability
- `ScopedBook` view makes cross-client data leakage *inexpressible*, not merely discouraged
- Deterministic router + policy checks run **before** any model call — abstention never depends on model confidence
- Every figure computed in Python and cited by record id, so citations come from retrieval rather than assertion

<img src="https://img.shields.io/badge/Private_Repo-6E7681?style=flat-square&logo=github&logoColor=white" />

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 🛠️ Tech Stack

<div align="center">

**Languages & Core**

[![My Skills](https://skillicons.dev/icons?i=java,python,js,ts,cpp,c&theme=dark)](https://skillicons.dev)

**Backend & Databases**

[![My Skills](https://skillicons.dev/icons?i=spring,fastapi,nodejs,express,postgres,mongodb,redis&theme=dark)](https://skillicons.dev)

**Frontend**

[![My Skills](https://skillicons.dev/icons?i=react,vite,tailwind,html,css&theme=dark)](https://skillicons.dev)

**DevOps & Tooling**

[![My Skills](https://skillicons.dev/icons?i=docker,aws,git,github,githubactions,postman,linux,vscode&theme=dark)](https://skillicons.dev)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-3B82F6?style=for-the-badge&logo=weaviate&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 💼 Experience & Education

<table>
<tr>
<td width="55%" valign="top">

**💻 Backend Developer Intern**
Atal Innovation Centre, Delhi
`Jun 2024 – Jan 2025`

</td>
<td width="45%" valign="top">

**🎓 B.Tech, Computer Science & Engineering**
IIIT Manipur
`Sep 2023 – Aug 2027`

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 🏆 Achievements

<table>
<tr>
<td width="50%" valign="top">

🥈 **AIR 2 — Engineer's Ring of Honour 2025**
Naukri.com, among IIT / IIIT / NIT participants — scholarship awarded and featured in *Times of India*

</td>
<td width="50%" valign="top">

🌍 **Rank 5,204 globally — Meta Hacker Cup 2025**
Cleared Round 1 among hundreds of thousands of competitors

</td>
</tr>
<tr>
<td width="50%" valign="top">

📡 **Top 3 proposals at IIIT Manipur**
5G Innovation Hackathon 2025, Dept. of Telecommunications, Govt. of India

</td>
<td width="50%" valign="top">

🎯 **Qualified GATE CS 2026** · 💻 **350+ DSA problems**
Across LeetCode, Codeforces, CodeChef and GeeksforGeeks

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 📊 GitHub Stats

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=mars-alien&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="stats" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mars-alien&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&exclude_repo=gamebase&hide=objective-c,c" alt="top languages" />

<br/>

<img height="165em" src="https://streak-stats.demolab.com?user=mars-alien&theme=tokyonight&hide_border=true" alt="streak" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=mars-alien&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="trophies" />

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

<div align="center">

### 💬 Let's build something

Open to **backend, full-stack and applied-AI** roles — and to interesting problems in retrieval, agents and distributed systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://royals-three.vercel.app)
[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/royalsachan)
[![Email](https://img.shields.io/badge/Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:royalsachaniiitm@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" width="100%" alt="footer" />

</div>
