<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Royal%20Sachan&fontSize=54&fontColor=ffffff&fontAlignY=34&desc=Backend%20%C2%B7%20Full-Stack%20%C2%B7%20Applied%20RAG&descAlignY=54&descSize=18" width="100%" alt="banner" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=36BCF7&center=true&vCenter=true&width=520&height=45&lines=CSE+Student+at+IIIT+Manipur;Backend+%26+Full-Stack+Engineer;Applied+RAG;Building+Scalable+%26+Secure+Systems)](https://github.com/DenverCoder1/readme-typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://royals-three.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/royalsachan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:royalsachaniiitm@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/spider-)

<br/>

<img src="https://komarev.com/ghpvc/?username=mars-alien&style=flat-square&color=36BCF7&label=Profile+Views" alt="profile views" />
<img src="https://img.shields.io/badge/Open%20to-AI%20%2F%20ML%20%26%20Backend%20Roles-2F9E6E?style=flat-square" alt="open to work" />

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 🧭 About

> Final-year CSE student at **IIIT Manipur**, building secure, scalable backend systems — and the retrieval/agent layers on top of them.

I work across **Express.js,Node.js,React.js, FastAPI,SpringBoot and PostgreSQL/MongoDB**, with hands-on experience building **RAG pipelines and multi-agent systems** end to end.

<table>
<tr>
<td width="33%" valign="top" align="center">

**🔐 Security & API Design**

<br/>

JWT auth + RBAC across **10+ REST endpoints** and 3 user roles — hardened with rate limiting, CORS and Helmet.js.

</td>
<td width="33%" valign="top" align="center">

**⚡ Performance**

<br/>

Cut response time **~30%** on high-traffic endpoints through PostgreSQL indexing and query optimisation.

</td>
<td width="33%" valign="top" align="center">

**🧠 Retrieval Engineering**

<br/>

Hybrid **BM25 + HNSW** retriever with Reciprocal Rank Fusion (BAAI/bge-m3, 1024-dim) in Weaviate, evaluated with RAGAS.

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📰 PaperTrail
**Multi-Article RAG Research Assistant**<br/>
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
**Event Companion Platform**<br/>
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
**Intelligent Delivery Route Optimizer**<br/>
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
**Multi-Agent Financial Analyst Ecosystem**<br/>
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

[![My Skills](https://skillicons.dev/icons?i=java,python,js,c&theme=dark)](https://skillicons.dev)

**Backend & Databases**

[![My Skills](https://skillicons.dev/icons?i=fastapi,nodejs,express,postgres,mongodb,&theme=dark)](https://skillicons.dev)

**Frontend**

[![My Skills](https://skillicons.dev/icons?i=react,vite,tailwind,html,css&theme=dark)](https://skillicons.dev)

**DevOps & Tooling**

[![My Skills](https://skillicons.dev/icons?i=docker,aws,git,github,githubactions,postman,linux,vscode&theme=dark)](https://skillicons.dev)

**AI / ML & Retrieval**

![RAG](https://img.shields.io/badge/RAG-6D28D9?style=for-the-badge)
![Hybrid Retrieval](https://img.shields.io/badge/Hybrid_Retrieval-BM25_%2B_HNSW_%2B_Reranking-0EA5E9?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LLM APIs](https://img.shields.io/badge/LLM_APIs-Groq-F55036?style=for-the-badge)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 💼 Experience & Education

<table>
<tr>
<td width="55%" valign="top">

**💻 Backend Developer Intern**<br/>
Atal Innovation Centre, Delhi<br/>
`Jun 2024 – Jan 2025`

</td>
<td width="45%" valign="top">

**🎓 B.Tech, Computer Science & Engineering**<br/>
IIIT Manipur<br/>
`Sep 2023 – Aug 2027`

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

## 🏆 Achievements

<table>
<tr>
<td width="50%" valign="top">

🥈 **AIR 2 — Engineer's Ring of Honour 2025**<br/>
Naukri.com, among IIT / IIIT / NIT participants — scholarship awarded and featured in *Times of India*

</td>
<td width="50%" valign="top">

🌍 **Rank 5,204 globally — Meta Hacker Cup 2025**<br/>
Cleared Round 1 among hundreds of thousands of competitors

</td>
</tr>
<tr>
<td width="50%" valign="top">

📡 **Top 3 proposals at IIIT Manipur**<br/>
5G Innovation Hackathon 2025, Dept. of Telecommunications, Govt. of India

</td>
<td width="50%" valign="top">

🎯 **Qualified GATE CS 2026** 

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

<h2 align="center">📊 GitHub Stats</h2>

<div align="center">

<img height="165" src="https://github-readme-stats-seven-tau-38.vercel.app/api?username=mars-alien&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub stats" /> <img height="165" src="https://github-readme-stats-seven-tau-38.vercel.app/api/top-langs/?username=mars-alien&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&exclude_repo=gamebase&hide=jupyter%20notebook,objective-c,c,shell" alt="Top languages" />

<br/><br/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=mars-alien&theme=tokyo-night&bg_color=1A1B27&color=70A5FD&line=BF91F3&point=38BDAE&area=true&hide_border=true&radius=8" alt="Contribution activity graph" />

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" height="4" alt="divider" />

### 💬 Let's build something

Open to **AI/ML, backend and full-stack** roles — and to interesting problems in retrieval, agents and distributed systems.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://royals-three.vercel.app)
[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/royalsachan)
[![Email](https://img.shields.io/badge/Say_Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:royalsachaniiitm@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer" width="100%" alt="footer" />

</div>
