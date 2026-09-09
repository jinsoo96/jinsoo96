<div align="center">

# Hi, I'm Jinsoo Kim

<a href="https://git.io/typing-svg">
  <img height="28" alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1000&color=22C55E&center=true&vCenter=true&random=false&width=600&height=28&lines=Ontology+Engineer;GraphRAG+%26+Knowledge-Graph+Architect;Agent+Cognition+Researcher;LLM+Harness+Builder;Open-Source+Maintainer" />
</a>

Building ontology-grounded knowledge graphs and ontology search algorithm.   

Agent env researcher, such as multi-agent harnesses/forge/loop that run on them.

<p>
  <img alt="Ontology" src="https://img.shields.io/badge/Ontology-1C7C54?style=flat" />
  <img alt="Knowledge Graph" src="https://img.shields.io/badge/Knowledge_Graph-2F6F4E?style=flat" />
  <img alt="GraphRAG" src="https://img.shields.io/badge/GraphRAG-6F42C1?style=flat" />
  <img alt="RAG" src="https://img.shields.io/badge/RAG-0E8A16?style=flat" />
  <img alt="Multi-Agent" src="https://img.shields.io/badge/Multi--Agent-0969DA?style=flat" />
  <img alt="Harness Engineering" src="https://img.shields.io/badge/Harness_Engineering-B7472A?style=flat" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat" />
  <img alt="Claude" src="https://img.shields.io/badge/Claude-191919?style=flat" />
</p>

<p>
  <a href="mailto:wlstn010203@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-EA4335?style=flat"></a>
  <a href="mailto:wlstn010203@khu.ac.kr"><img alt="KHU" src="https://img.shields.io/badge/KHU_Mail-8B0000?style=flat"></a>
  <a href="https://github.com/jinsoo96"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat"></a>
</p>

</div>

---

## Focus

**Ontology & knowledge graphs:** building backend-agnostic **ontology / KG toolkits** end to end — document and tabular extraction, entity resolution, predicate governance, dedup, is-a hierarchy induction, quality scoring — then retrieving over them with one-shot **GraphRAG** (vector + graph-label + class-enumeration fusion, MMR diversity, adaptive top-k instead of fixed-k). Zero-infra by default, any SPARQL 1.1 store when you outgrow that.  
**Multi-agent systems:** agent cognition (persona, emotion, memory, theory-of-mind), harness execution engines, and **forge engineering** — agents that rewrite their own harness under benchmark-gated control.  
**Open source and research:** js-ontology-build / js-omnifuse / xgen-harness / Agethos on PyPI, multi-award academic publications.

### Ontology engineering — a few specifics

- **Taxonomy induction, no LLM call**: Korean Hearst-pattern hypernym discovery + head-noun compound decomposition, straight out of raw documents and tables.
- **FK-aware table-to-ontology**: star-schema fact/dimension split; FK direction resolved from the actual primary key, not naive value-overlap.
- **Adaptive retrieval**: dynamic score-cutoff (not fixed top-k) + MMR diversity, so minority/contradicting evidence survives.
- **Backend-agnostic**: zero-dep in-memory graph by default, drop-in to any SPARQL 1.1 store.

### Multi-agent & harness engineering — a few specifics

- **Agent cognition (Agethos)**: OCEAN personality + PAD emotion driving actual behavior, Hebbian memory, vicarious learning.
- **Multi-agent debate (agent-colosseum)**: agents debate/red-team/peer-review each other, benchmarked against single-agent baselines.
- **Harness engineering**: a declared `HarnessConfig` compiles to a 10-stage pipeline, workflows compile to installable MCP wheels.
- **Forge engineering**: agents that rewrite their own harness config under versioned, benchmark-gated control.

---

### Featured Projects

| Project | Description | Links |
|---------|-------------|-------|
| [**js-ontology-build**](https://github.com/jinsoo96/js-ontology-build) | Backend-agnostic **ontology / knowledge-graph toolkit** — parse documents or tables, build a clean KG (entity resolution, predicate governance, dedup, is-a hierarchy induction, quality scoring, community detection), then search it with one-shot **GraphRAG**. Zero infra by default (pure-Python in-memory), loads into any SPARQL 1.1 store. Published on PyPI as `xgen-ontology`. Source-available, all rights reserved | [![PyPI](https://img.shields.io/pypi/v/xgen-ontology.svg)](https://pypi.org/project/xgen-ontology/) [![License](https://img.shields.io/badge/license-source--available-blue)](https://github.com/jinsoo96/js-ontology-build/blob/main/LICENSE) |
| [**js-omnifuse**](https://github.com/jinsoo96/js-omnifuse) | Backend-agnostic one-shot **GraphRAG** — fuses vector + graph (label / class enumeration / relation) seeds with MMR diversity into a single synthesis; zero-infra (in-memory BM25) or any SPARQL/Fuseki. Plus **Vault**, an omnifuse-native memory (fuse / surface). The search half of js-ontology-build, extracted standalone. Published on PyPI as `xgen-omnifuse`. Source-available, all rights reserved | [![PyPI](https://img.shields.io/pypi/v/xgen-omnifuse.svg)](https://pypi.org/project/xgen-omnifuse/) [![License](https://img.shields.io/badge/license-source--available-blue)](https://github.com/jinsoo96/js-omnifuse/blob/main/LICENSE) |
| [**xgen-harness**](https://github.com/jinsoo96/xgen-harness-executor) | Declarative LLM agent **execution engine** (harness engineering) — declare a `HarnessConfig`, get a 10-stage pipeline. Multi-provider, capability-based tool matching, compile workflows to installable MCP wheels | [![PyPI](https://img.shields.io/pypi/v/xgen-harness.svg)](https://pypi.org/project/xgen-harness/) |
| [**JINXUS**](https://github.com/jinsoo96/JINXUS) | Hyper-personalized multi-agent AI assistant — 28 agents, virtual pixel office, 225 tools, autonomous execution | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js) |
| [**Agethos**](https://github.com/jinsoo96/agethos) | A brain for AI agents — OCEAN personality, PAD emotion, memory stream, Hebbian learning, vicarious learning, cross-platform export | [![PyPI](https://img.shields.io/pypi/v/agethos.svg)](https://pypi.org/project/agethos/) || [**forge-engineering**](https://github.com/jinsoo96/forge-engineering) | **Forge Engineering** — a meta-engineering discipline *above* harness engineering: agents that rewrite their own harness under versioned, benchmark-gated control | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

### Awards

| Year | Award | Conference |
|------|-------|------------|
| 2025 | Excellence Paper Award | Korea Society of Electronic Commerce & Smart Media Society |
| 2024 | Excellence Paper Award | Korea Society of IT Services |
| 2024 | Best Paper Award | Korea Intelligent Information Systems Society |
| 2024 | Excellence Paper Award | Korean Academy of Management |
| 2023 | Excellence Paper Award | Korea Society of Information Systems |
| 2023 | Best Paper -- Honorable Mention | KHU Big Data Graduate Student Conference |
| 2023 | Grand Prize | Korea Knowledge Management Society -- Idea Competition |

### Background

<table>
  <tr>
    <td><b>Education</b></td>
    <td>M.S. Big Data Analytics — Kyung Hee University / B.S. Statistics — Jeonbuk National University</td>
  </tr>
  <tr>
    <td><b>Experience</b></td>
    <td>Plateer — AI/LLM Engineer (current); ontology engineering & GraphRAG (knowledge-graph build pipelines, backend-agnostic retrieval) and agent harness execution engines  
        Shaveron — FDE (Forward Deployed Engineer) LG CNS SINGLEX Strategy/Operations Team @ LG Science Park — RAG Development</td>
  </tr>
  <tr>
    <td><b>Interests</b></td>
    <td>Multi-Agent AI Systems, Agent Cognition, RAG, NLP, Time Series Forecasting</td>
  </tr>
</table>

### Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

**AI & Data**

![Anthropic](https://img.shields.io/badge/Claude_API-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**DevOps & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

### GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=jinsoo96&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=jinsoo96&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=jinsoo96&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
</picture>
&nbsp;
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=jinsoo96&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=jinsoo96&layout=compact&theme=default&hide_border=true&langs_count=8" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jinsoo96&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=jinsoo96&theme=github-dark-blue&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=jinsoo96&theme=default&hide_border=true" />
  <img src="https://streak-stats.demolab.com?user=jinsoo96&theme=github-dark-blue&hide_border=true" />
</picture>

</div>


<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/snake/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/snake/github-contribution-grid-snake.svg" />
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/jinsoo96/jinsoo96/snake/github-contribution-grid-snake-dark.svg" />
  </picture>
</div>



