<div align="center">

# Hi, I'm Jinsoo Kim

<img alt="AI Engineer · Forward Deployed Engineer" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1000&color=22C55E&center=true&vCenter=true&random=false&width=460&height=30&lines=AI+Engineer+%C2%B7+Forward+Deployed+Engineer;Ontology+Engine+%26+GraphRAG+Search;Agent+Harness+Engineering;LLM+Evals+%26+Guardrails;Enterprise+On-premise+AI+Delivery" />

I build ontology engines and GraphRAG search, and agent harnesses that own judging, retries and memory.<br/>
Then I ship them into banking, capital and retail customers' On-premise environments and measure them there.

<p>
  <a href="https://blog.js-96.com"><img alt="Tech Blog" src="https://img.shields.io/badge/Tech_Blog-2B6CF6?style=flat-square" /></a>
  <a href="https://blog.js-96.com/cv/"><img alt="CV" src="https://img.shields.io/badge/CV-2B6CF6?style=flat-square" /></a>
  <a href="https://www.linkedin.com/in/jinsoo-kim-942438301/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-2B6CF6?style=flat-square" /></a>
  <a href="mailto:wlstn010203@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-2B6CF6?style=flat-square" /></a>
  <a href="mailto:wlstn010203@khu.ac.kr"><img alt="KHU Mail" src="https://img.shields.io/badge/KHU_Mail-2B6CF6?style=flat-square" /></a>
</p>

</div>

## What I do

- **Ontology engine & search systems**: LLM-free ontology builds from documents, tables and databases, a PostgreSQL-native graph store, and one-shot GraphRAG retrieval with provenance.
- **Agent harness research & development**: a state-machine runtime that owns judging, retries, termination, memory and tool search, compiled into PyPI · npm · MCP packages.
- **XGEN maintenance & enterprise delivery**: porting the platform into air-gapped and On-premise customer environments, fixing what breaks there, and re-measuring under the same conditions.

## Capabilities

**Ontology & Retrieval** · [notes](https://blog.js-96.com/series/ontology-engineering/)<br/>
Turning documents, CSV files and relational databases into an ontology, and answering from it with the evidence attached.<br/>
`Ontology modeling` `Build pipelines` `Incremental sync` `PostgreSQL graph store` `GraphRAG fusion` `BM25F · PPR · MMR ranking` `Citation tracking`

**Agent Engineering** · [notes](https://blog.js-96.com/series/agent-harness/)<br/>
Designing the runtime around the model: when to judge, retry and stop, what to remember, and which tools to show.<br/>
`Agent runtime design` `Judge · retry · termination policy` `Agent memory` `Context engineering` `Progressive tool disclosure` `MCP servers` `HITL approval` `OAuth 2.1 PKCE`

**LLM Evals** · [notes](https://blog.js-96.com/series/evaluation/)<br/>
Comparing models and agents under fixed conditions, with gold sets and judges that return the same verdict on reruns.<br/>
`Fixed gold sets` `LLM-as-a-Judge` `Controlled comparisons` `Verdict determinism` `RAGAS`

**Enterprise Delivery** · [notes](https://blog.js-96.com/series/fde/)<br/>
Building, deploying and maintaining XGEN inside customer networks, including responses to security vulnerability assessments for bank customers.<br/>
`Air-gapped k3s · Helm` `PII masking` `Guardrails` `Audit trails` `Vulnerability assessment response` `vLLM serving` `Dependency · SBOM review` `Next.js · FastAPI`

**Data Science**<br/>
Statistics, machine learning and deep learning research from my M.S. work, mainly forecasting and prediction.<br/>
`Time-series forecasting` `DLinear · TimeMixer ensembles` `ML prediction` `Feature importance` `Clustering` `Text mining`

## Featured Projects

- **[xgen-omnifuse](https://github.com/jinsoo96/js-omnifuse)** &nbsp;[![PyPI](https://img.shields.io/pypi/v/xgen-omnifuse?style=flat-square&label=PyPI&color=2B6CF6&labelColor=30363d)](https://pypi.org/project/xgen-omnifuse/)<br/>
  Backend-agnostic one-shot **GraphRAG** search that fuses vector, graph and HippoRAG expansion into a single synthesis.<br/>
  Result: on a public financial-regulation benchmark, multi-hop strict answers went from **19 to 103 of 120** with no LLM in retrieval.

- **[xgen-ontology-build](https://github.com/jinsoo96/js-ontology-build)** &nbsp;[![PyPI](https://img.shields.io/pypi/v/xgen-ontology-build?style=flat-square&label=PyPI&color=2B6CF6&labelColor=30363d)](https://pypi.org/project/xgen-ontology-build/)<br/>
  Documents, tables and DB rows into a provenance-tracked **ontology**, LLM-free by default.<br/>
  Result: output diff **0** against the product pipeline on a **14,924-chunk** real corpus.

- **[xgen-harness](https://github.com/jinsoo96/xgen-harness-executor)** &nbsp;[![PyPI](https://img.shields.io/pypi/v/xgen-harness?style=flat-square&label=PyPI&color=2B6CF6&labelColor=30363d)](https://pypi.org/project/xgen-harness/)<br/>
  10-stage state-machine **agent execution engine** that compiles canvas agents into PyPI · npm · MCP packages.<br/>
  Result: under the same strict-citation judge, scores that split between 0 and full marks settled to **0.70 – 0.98**.

- **[Jermes](https://github.com/jinsoo96/jermes)**<br/>
  Self-improving agent that promotes a procedure to a skill only when its gain reproduces on held-out runs.<br/>
  Result: cumulative accuracy **44.2% → 88.9%** over 190 user questions.

- **[XGEN MAKER](https://github.com/jinsoo96/xgen-maker)**<br/>
  Development-automation harness that lands natural-language requests on exact files and lines through a code ontology of 23 repos.<br/>
  Result: **R@10 0.837** on 2,827 human-merged MRs.

- **[Agethos](https://github.com/jinsoo96/agethos)** &nbsp;[![PyPI](https://img.shields.io/pypi/v/agethos?style=flat-square&label=PyPI&color=2B6CF6&labelColor=30363d)](https://pypi.org/project/agethos/)<br/>
  Personality, memory and emotion for LLM agents, with a draft · judge · repair persona compiler.<br/>
  Result: persona compile fidelity **0.930**.

Also building: [missile-studio](https://github.com/jinsoo96/missile-studio) · [js-image-studio](https://github.com/jinsoo96/js-image-studio) · [ALTERLENS](https://github.com/jinsoo96/alterlens) · [comfy-workflow-mcp](https://github.com/PlateerLab/comfy-workflow-mcp) · [xgen-mcp-harness](https://github.com/PlateerLab/xgen-mcp-harness). The full list with release and commit history is on the [blog](https://blog.js-96.com/projects/).

## Tech Stack

<div align="center">

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-30363d?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-30363d?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-30363d?style=flat-square&logo=javascript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-30363d?style=flat-square&logo=postgresql&logoColor=white)

**AI & Data**<br/>
![Claude API](https://img.shields.io/badge/Claude_API-30363d?style=flat-square&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-30363d?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-30363d?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-30363d?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-30363d?style=flat-square&logo=pandas&logoColor=white)

**Backend & Frontend**<br/>
![FastAPI](https://img.shields.io/badge/FastAPI-30363d?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-30363d?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-30363d?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-30363d?style=flat-square&logo=react&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-30363d?style=flat-square&logo=tailwindcss&logoColor=white)

**DevOps & Infra**<br/>
![Docker](https://img.shields.io/badge/Docker-30363d?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-30363d?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-30363d?style=flat-square&logo=jenkins&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-30363d?style=flat-square&logo=gitlab&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-30363d?style=flat-square&logo=redis&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-30363d?style=flat-square&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-30363d?style=flat-square&logo=linux&logoColor=white)
![Git](https://img.shields.io/badge/Git-30363d?style=flat-square&logo=git&logoColor=white)

</div>

## Background

**Experience**

- **Plateer Inc.** · AI Solution Research Institute, AI R&D Team · AI Engineer / FDE · 2026.01 – present<br/>
  XGEN maintenance and feature development · AI agent research · ontology engine and search systems · On-premise delivery for bank, capital and retail customers (FDE) · security vulnerability assessment response for bank customers
- **Shaveron** · Freelance Developer (FDE) · 2025.01 – 2025.07<br/>
  Dispatched to LG CNS Singlex Strategy/Operations Team · RAG chatbot prompts, retrieval and evaluation automation

**Education**

- M.S. Big Data Applied Science, Kyung Hee University · 2023.03 – 2025.02
- B.S. Statistics, Jeonbuk National University · 2016.03 – 2022.02

**Interests**: Agentic AI, Ontology & GraphRAG, LLM Evals, Multi-Agent Systems, Time-Series Forecasting

## Awards

- **2025** · Excellence Paper Award · Korea Society of Electronic Commerce & Smart Media Society
- **2024** · Excellence Paper Award · Korea Society of IT Services
- **2024** · Best Paper Award · Korea Intelligent Information Systems Society
- **2024** · Excellence Paper Award · Korean Academy of Management
- **2023** · Excellence Paper Award · Korea Society of Information Systems
- **2023** · Best Paper, Honorable Mention · KHU Big Data Graduate Student Conference
- **2023** · Grand Prize · Korea Knowledge Management Society Idea Competition

## Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/stats/stats-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/stats/stats-light.svg" />
  <img width="480" alt="Activity in the last 12 months" src="https://raw.githubusercontent.com/jinsoo96/jinsoo96/stats/stats-dark.svg" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/stats/langs-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/stats/langs-light.svg" />
  <img width="330" alt="Most used languages" src="https://raw.githubusercontent.com/jinsoo96/jinsoo96/stats/langs-dark.svg" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/snake/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jinsoo96/jinsoo96/snake/github-contribution-grid-snake.svg" />
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/jinsoo96/jinsoo96/snake/github-contribution-grid-snake-dark.svg" />
</picture>

</div>
