<div align="center">

# Hi, I'm Jinsoo Kim

<a href="https://git.io/typing-svg">
  <img height="28" alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1000&color=22C55E&center=true&vCenter=true&random=false&width=600&height=28&lines=AI+Engineer+%C2%B7+Forward+Deployed+Engineer;Ontology+Engine+%26+GraphRAG+Search;Agent+Harness+Engineering;LLM+Evals+%26+Guardrails;Enterprise+On-prem+AI+Delivery" />
</a>

I build ontology engines and GraphRAG search, and agent harnesses that own judging, retries and memory.

Then I ship them into banking, capital and retail customers' on-prem environments and measure them there.

<p>
  <img alt="Agentic AI" src="https://img.shields.io/badge/Agentic_AI-0969DA?style=flat" />
  <img alt="Ontology" src="https://img.shields.io/badge/Ontology-1C7C54?style=flat" />
  <img alt="GraphRAG" src="https://img.shields.io/badge/GraphRAG-6F42C1?style=flat" />
  <img alt="Agent Harness" src="https://img.shields.io/badge/Agent_Harness-B7472A?style=flat" />
  <img alt="LLM Evals" src="https://img.shields.io/badge/LLM_Evals-E36209?style=flat" />
  <img alt="MCP" src="https://img.shields.io/badge/MCP-24292F?style=flat" />
  <img alt="FDE" src="https://img.shields.io/badge/FDE-0E8A16?style=flat" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat" />
  <img alt="Claude" src="https://img.shields.io/badge/Claude-191919?style=flat" />
</p>

<p>
  <a href="https://blog.js-96.com"><img alt="Blog" src="https://img.shields.io/badge/Tech_Blog-111827?style=flat"></a>
  <a href="https://blog.js-96.com/cv/"><img alt="CV" src="https://img.shields.io/badge/CV-2B6CF6?style=flat"></a>
  <a href="https://www.linkedin.com/in/jinsoo-kim-942438301/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat"></a>
  <a href="mailto:wlstn010203@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-EA4335?style=flat"></a>
  <a href="mailto:wlstn010203@khu.ac.kr"><img alt="KHU" src="https://img.shields.io/badge/KHU_Mail-8B0000?style=flat"></a>
  <a href="https://github.com/jinsoo96"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat"></a>
</p>

</div>

---

## What I do

- **Ontology engine & search systems**: LLM-free ontology builds from documents, tables and databases, a PostgreSQL-native graph store, and one-shot GraphRAG retrieval with provenance.
- **Agent harness research & development**: a state-machine runtime that owns judging, retries, termination, memory and tool search, compiled into PyPI · npm · MCP packages.
- **XGEN maintenance & enterprise delivery**: porting the platform into air-gapped and on-prem customer environments, fixing what breaks there, and re-measuring under the same conditions.

## Capabilities

| Area | What I can do |
|---|---|
| **Ontology & Retrieval** | Ontology modeling and build pipelines (document / CSV / RDB), incremental sync with PK keyset and row fingerprints, graph storage on PostgreSQL, GraphRAG fusion, hybrid ranking (BM25F · PPR · MMR), evidence and citation tracking |
| **Agent Engineering** | Agent runtime design, judge · retry · termination policy, agent memory, context engineering and progressive tool disclosure, MCP servers, HITL approval and OAuth 2.1 PKCE |
| **LLM Evals** | Fixed gold sets, LLM-as-a-Judge, controlled model and agent comparisons, verdict determinism, RAGAS |
| **Enterprise Delivery** | Air-gapped k3s · Helm deployments, PII masking · guardrails · audit trails, vLLM serving, dependency and SBOM review, Next.js · FastAPI product work |
| **Data Science** | Statistics, time-series forecasting (DLinear · TimeMixer ensembles), ML prediction and feature importance, clustering, text mining |

---

### Featured Projects

| Project | What it does | Proof | Links |
|---------|-------------|-------|-------|
| [**xgen-omnifuse**](https://github.com/jinsoo96/js-omnifuse) | Backend-agnostic one-shot **GraphRAG** search that fuses vector, graph and HippoRAG expansion into a single synthesis | Public financial-regulation benchmark, multi-hop strict answers **19 → 103 / 120** with no LLM in retrieval | [![PyPI](https://img.shields.io/pypi/v/xgen-omnifuse.svg)](https://pypi.org/project/xgen-omnifuse/) |
| [**xgen-ontology-build**](https://github.com/jinsoo96/js-ontology-build) | Documents, tables and DB rows into a provenance-tracked **ontology**, LLM-free by default | Output diff **0** against the product pipeline on a **14,924-chunk** real corpus | [![PyPI](https://img.shields.io/pypi/v/xgen-ontology-build.svg)](https://pypi.org/project/xgen-ontology-build/) |
| [**xgen-harness**](https://github.com/jinsoo96/xgen-harness-executor) | 10-stage state-machine **agent execution engine**; compiles canvas agents into PyPI · npm · MCP packages | Under the same strict-citation judge, scores that split between 0 and full marks settled to **0.70 – 0.98** | [![PyPI](https://img.shields.io/pypi/v/xgen-harness.svg)](https://pypi.org/project/xgen-harness/) |
| [**Jermes**](https://github.com/jinsoo96/jermes) | Self-improving agent that promotes a procedure to a skill only when its gain reproduces on held-out runs | Cumulative accuracy **44.2% → 88.9%** over 190 user questions | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [**XGEN MAKER**](https://github.com/jinsoo96/xgen-maker) | Development-automation harness that lands natural-language requests on exact files and lines through a code ontology of 23 repos | **R@10 0.837** on 2,827 human-merged MRs | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [**Agethos**](https://github.com/jinsoo96/agethos) | Personality, memory and emotion for LLM agents, with a draft · judge · repair persona compiler | Persona compile fidelity **0.930** | [![PyPI](https://img.shields.io/pypi/v/agethos.svg)](https://pypi.org/project/agethos/) |

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
    <td><b>Experience</b></td>
    <td><b>Plateer AI-Lab</b> · AI Engineer / FDE (current)<br/>Ontology engine & search systems · agent harness research & development · XGEN maintenance & enterprise delivery<br/><br/><b>Shaveron</b> · Freelance Developer (FDE), dispatched to LG CNS Singlex Strategy/Operations Team<br/>RAG chatbot prompts, retrieval and evaluation automation</td>
  </tr>
  <tr>
    <td><b>Education</b></td>
    <td>M.S. Big Data Applied Science, Kyung Hee University<br/>B.S. Statistics, Jeonbuk National University</td>
  </tr>
  <tr>
    <td><b>Interests</b></td>
    <td>Agentic AI, Ontology & GraphRAG, LLM Evals, Multi-Agent Systems, Time-Series Forecasting</td>
  </tr>
</table>

### Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**AI & Data**

![Anthropic](https://img.shields.io/badge/Claude_API-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Backend & Frontend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**DevOps & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
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
