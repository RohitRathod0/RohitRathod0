<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=shark&color=0A0E14&fontColor=00D9FF&text=Rohit%20Rathod&fontSize=38&desc=AI%2FML%20Engineer%20%7C%20Full-Stack%20%7C%20Agentic%20Systems&descColor=7CFFCB&animation=fadeIn&fontAlignY=32&descAlignY=52" />
</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00D9FF&center=true&vCenter=true&width=820&lines=%24+whoami+%E2%86%92+Final-Year+CE+Student+%40+SPIT+Mumbai;%24+focus+%E2%86%92+AI%2FML+Engineering+%7C+Agentic+Systems;%24+ls+%2Fprojects+%E2%86%92+INVEX+%7C+OS-Tutor+%7C+MCP-Orchestrator;%24+cat+open-to.txt+%E2%86%92+AI%2FML+%26+Full-Stack+AI+Roles" />

</div>

<div align="center">

[![Portfolio](https://img.shields.io/badge/GitHub-RohitRathod0-00D9FF?style=for-the-badge&logo=github&logoColor=white&labelColor=0A0E14)](https://github.com/RohitRathod0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-00D9FF?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A0E14)](https://linkedin.com/in/rohit-rathod-2a867228a)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-00D9FF?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A0E14)](mailto:rohitrathod4084@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-200%2B%20Solved-00D9FF?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0A0E14)](https://leetcode.com/Rohit_Rathod09)

</div>

## `> whoami`

Final-year Computer Engineering student (SPIT, Mumbai, graduating 2027) building production-grade AI systems — agentic architectures, RAG pipelines, and MLOps — alongside a full-stack engineering foundation. ~1.5+ years of self-directed project work outside the classroom.

```bash
$ cat .profile

ROLE     =  AI/ML Engineer (in progress) | Full-Stack Developer
EXP      =  1.5+ yrs self-directed AI/ML project work
DOMAIN   =  Agentic AI  |  Fintech  |  MLOps  |  RAG Systems
STACK    =  React/TSX  |  Node.js  |  Python/FastAPI  |  LangGraph
OPEN_TO  =  AI/ML Engineering & Full-Stack AI roles (Indian fintech / AI companies)
```

## `> ls /skills`

<div align="center">

**Languages & Frontend**
<br>
<img src="https://skillicons.dev/icons?i=py,js,ts,react,html,css&theme=dark" />

**Backend & Data**
<br>
<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,postgres,redis&theme=dark" />

**AI / ML / Infra**
<br>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,docker,aws,git,github&theme=dark" />

</div>

*(Also working daily with LangChain, LangGraph, CrewAI, ChromaDB, Qdrant, MLflow, and the Claude/GPT-4/Mistral/Gemini APIs — not pictured, skillicons.dev doesn't have icons for these yet.)*

## `> cat expertise.md`

| Domain | Level | Details |
| :-- | :-- | :-- |
| Agentic AI Systems | Advanced | LangGraph, LangChain, CrewAI, multi-agent orchestration, RAG (ChromaDB, Qdrant) |
| Full-Stack Development | Advanced | React/TSX, Node.js/Express, FastAPI, MongoDB, PostgreSQL |
| MLOps & Classical ML | Intermediate–Advanced | LightGBM, Isolation Forest, MLflow, Evidently AI, SHAP, Docker/AWS deployment |
| Deep Learning from First Principles | Intermediate | 355M-param GPT-2 pretrained from scratch in PyTorch, LoRA/PEFT fine-tuning |
| Fintech Domain | Focus area | Investment platforms, fraud detection, credit risk modeling |

## `> ls /projects --featured`

<details open>
<summary><b>&#9654; INVEX &mdash; Full-Stack Production Investment Platform</b></summary>

Primary project — a production-targeting investment platform with a 12-agent LangGraph layer spanning 3 LLM providers.

| Aspect | Detail |
| :-- | :-- |
| **Stack** | React/TSX &middot; Node.js/Express &middot; MongoDB &middot; Python/LangGraph |
| **Scale** | 12 agents across 3 LLM providers, deploying to AWS EC2 |
| **Impact** | Redis caching cut market-data/risk-profile lookups from ~2s to ~18ms (99% latency reduction, Docker-verified) &middot; fixed IDOR vulnerabilities across 16 endpoints &middot; built append-only AuditLog for price-alert notifications |

Every metric here is grep- and Docker-verified before being written down — including walking back an earlier "30% LLM inference cost reduction" claim to accurately reflect that only market-data/risk-profile caching was in scope, not LLM response caching.

</details>

<details>
<summary><b>&#9654; MCP Marketplace Simulator &mdash; Multi-Agent MCP Orchestration</b></summary>

| Aspect | Detail |
| :-- | :-- |
| **Stack** | Specialized agents behind individual MCP servers &middot; orchestrator agent &middot; RAG (ChromaDB) &middot; prompt engineering |
| **Scale** | 3 agents + orchestrator, built in a feature-branch-per-phase workflow |
| **Impact** | Built a full eval harness; prompt iteration (v1→v2) took in-distribution routing/tool-selection/grounding accuracy from 80–89% to 100% (n=35) &middot; held-out testing on 14 novel queries showed ~75–80% generalization, confirming genuine (not keyword-coincidence) grounding |

</details>

<details>
<summary><b>&#9654; OS-Tutor &mdash; Multimodal RAG Educational Dialogue System</b></summary>

Final-year major project, guided by faculty, built with a 2-person team.

| Aspect | Detail |
| :-- | :-- |
| **Stack** | Qdrant &middot; BGE embeddings &middot; LangChain &middot; LoRA fine-tuning &middot; Streamlit |
| **Scale** | Fine-tuned TinyLlama-1.1B (initially prototyped on Qwen2.5-VL-7B) |
| **Impact** | Fine-tuned model published on HuggingFace as `rohit21789/OS-tutor`; full LaTeX report and SVG diagrams delivered |

</details>

<details>
<summary><b>&#9654; UPI Fraud Detection &mdash; Deployed ML Fraud Pipeline</b></summary>

| Aspect | Detail |
| :-- | :-- |
| **Stack** | LightGBM &middot; Isolation Forest &middot; FastAPI &middot; MLflow &middot; Evidently AI &middot; Docker &middot; AWS EC2 |
| **Scale** | Deployed on AWS EC2 (t3.small, Ubuntu 24.04, Docker Compose) |
| **Impact** | PR-AUC 0.9598 &middot; resolved Evidently version pinning, MLflow artifact-path issues, Streamlit rendering bugs, and SSH/tmux session management for long-running builds |

</details>

<details>
<summary><b>&#9654; ArthSaathi &mdash; Multi-Agent Financial Literacy Companion</b></summary>

Built for Nomura KakushIN 2026.

| Aspect | Detail |
| :-- | :-- |
| **Stack** | Mistral Large &middot; Gemini 2.5 Flash &middot; LiveKit &middot; Whisper &middot; gTTS |
| **Scale** | Multi-agent voice-first financial literacy assistant |
| **Impact** | Real-time voice interaction pipeline combining two LLM providers with live speech-to-text/text-to-speech |

</details>

*Also shipping: a standalone **Credit Risk Scorecard** (optbinning, Logistic Regression, LightGBM, SHAP, FastAPI — AUC ~0.86, Gini ~0.72) and a **355M-param GPT-2** pretrained from first principles in PyTorch.*

## `> cat experience.log`

```
IETE Committee, SPIT ................ Head of Operations
Military Boys Hostel ................ General Secretary
ET AI Hackathon 2026 ................ Semifinalist (25,000+ registrants)
```

## `> cat certifications.txt`

<div align="center">

![MCP Advanced Topics](https://img.shields.io/badge/Anthropic-MCP%20Advanced%20Topics-00D9FF?style=flat-square&labelColor=0A0E14)
![AI Fluency](https://img.shields.io/badge/Anthropic-AI%20Fluency-00D9FF?style=flat-square&labelColor=0A0E14)
![AI Capabilities & Limitations](https://img.shields.io/badge/Anthropic-AI%20Capabilities%20%26%20Limitations-00D9FF?style=flat-square&labelColor=0A0E14)
![Agentic Track](https://img.shields.io/badge/Udemy-AI%20Engineer%20Agentic%20Track-00D9FF?style=flat-square&labelColor=0A0E14)

</div>

## `> ./analytics.sh`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=RohitRathod0&show_icons=true&hide_border=true&title_color=00D9FF&icon_color=7CFFCB&text_color=E6EDF3&bg_color=0A0E14" />

<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=RohitRathod0&hide_border=true&background=0A0E14&stroke=00D9FF&ring=7CFFCB&fire=00D9FF&currStreakLabel=00D9FF" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RohitRathod0&layout=compact&hide_border=true&title_color=00D9FF&text_color=E6EDF3&bg_color=0A0E14" />

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=RohitRathod0&theme=algolia&no-frame=true&column=7&margin-w=8" />

</div>

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=RohitRathod0&bg_color=0A0E14&color=00D9FF&line=00D9FF&point=7CFFCB&area=true&hide_border=true" />

</div>

## `> cat current-focus.yaml`

```yaml
building:
  - INVEX             # deploying the 12-agent investment platform to AWS EC2
  - MCP-Marketplace    # multi-agent MCP orchestration, iterating on eval-driven prompt design

open_to:
  - AI/ML Engineering roles
  - Full-Stack AI Product roles
  - Indian fintech & AI engineering companies
```

## `> ./connect.sh`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-RohitRathod0-00D9FF?style=for-the-badge&logo=github&logoColor=white&labelColor=0A0E14)](https://github.com/RohitRathod0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-00D9FF?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A0E14)](https://linkedin.com/in/rohit-rathod-2a867228a)
[![Email](https://img.shields.io/badge/Email-rohitrathod4084%40gmail.com-00D9FF?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A0E14)](mailto:rohitrathod4084@gmail.com)

</div>

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=shark&color=0A0E14&fontColor=00D9FF&height=100&section=footer" />
</div>
