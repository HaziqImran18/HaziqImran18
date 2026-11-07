<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:080808,50:172554,100:00F5D4&text=Haziq%20Imran&fontSize=50&fontColor=FFFFFF&fontAlignY=40&desc=AI%20Engineer%20%E2%80%A2%20LLM%20Agents%20%E2%80%A2%20Evaluated%2C%20Traced%2C%20Shipped&descSize=16&descAlignY=64" alt="Haziq Imran"/>

**I build LLM agents that call real tools, and I measure whether they work.**
BS Artificial Intelligence (2026) · Python / FastAPI / LangGraph · Open to remote roles with US & Canadian teams

<a href="https://www.linkedin.com/in/haziq-imran-778760312"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:hazziq595959@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="YOUR_PORTFOLIO_URL"><img src="https://img.shields.io/badge/Portfolio-Live-00F5D4?style=for-the-badge&labelColor=101820"/></a>
<a href="YOUR_RESUME_PDF_LINK"><img src="https://img.shields.io/badge/Resume-PDF-FFB703?style=for-the-badge&labelColor=101820"/></a>

</div>

---

## 📌 At a glance

| | |
|---|---|
| **Role I'm targeting** | Junior / Early-Career AI Engineer (LLM applications, agents, RAG) |
| **Location & hours** | Rahim Yar Khan, Pakistan (UTC+5). Happy to overlap 4–6 hrs with EST/PST, async-first |
| **Languages** | English (C1), Urdu (native) |
| **Strongest at** | Turning an agent idea into a working API with tools, state, and tests |
| **Currently improving** | Evaluation suites, tracing, guardrails, retrieval quality |
| **Availability** | `[Full-time / contract, start date]` |

---

## 🚀 Featured projects

> Each project: the problem, how it's built, and the **proof it works**. Replace every `[ ]` with your real numbers. If you don't have a number yet, run the eval and get one before you publish.

### 1. 🛒 WhatsApp Shopping Agent
**Problem:** Comparing prices across stores means opening ten tabs. This agent does it inside a WhatsApp chat.

```mermaid
flowchart LR
    U[WhatsApp user] --> W[Webhook · FastAPI]
    W --> A[LangGraph agent]
    A --> T1[Product search tool]
    A --> T2[Price compare tool]
    A --> M[(Conversation state)]
    A --> V{Output validation}
    V -->|valid| R[Reply to user]
    V -->|invalid| F[Retry / fallback]
    A -.-> O[Tracing: cost, latency, errors]
```
<sub>↑ Edit this diagram to match your real architecture. Recruiters read diagrams before code.</sub>

| Engineering proof | Result |
|---|---|
| Test set of real queries | `[N]` queries, `[X]%` returned the correct cheapest option |
| Median / p95 latency | `[ ] s / [ ] s` |
| Cost per conversation | `$[ ]` |
| Failure handling | `[what happens when a store API times out or the model returns bad JSON]` |
| Known limitation | `[one honest sentence]` |

**Stack:** Python · FastAPI · LangGraph · `[LLM provider]` · `[DB]` · Docker
🔗 [Live demo](#) · [Code](#) · [Architecture write-up](#)

---

### 2. 🎓 Scholarship Guidance Assistant
**Problem:** Students miss funding because eligibility rules are scattered and confusing.
**Approach:** `[retrieval over scholarship data? structured eligibility matching? describe in one line]`

| Engineering proof | Result |
|---|---|
| Answer accuracy on `[N]` hand-checked questions | `[X]%` |
| How it handles "not in the data" | `[refuses / cites source / escalates]` |

🔗 [Live demo](#) · [Code](#)

---

### 3. ✉️ Professor Outreach Tool
**Problem:** Cold emails to professors are generic and get ignored.
**Approach:** `[how it researches a professor and personalizes; where a human reviews before sending]`

| Engineering proof | Result |
|---|---|
| Human-in-the-loop step | `[yes/no, where]` |
| Hallucination control | `[how you stop it inventing papers]` |

🔗 [Live demo](#) · [Code](#)

---

## 🧪 How I work

```text
Spec the task → Build the smallest working agent → Write an eval set → Break it on purpose → Fix → Re-run evals
```

What I do on every serious project:

- **Typed everything.** Pydantic models for tool inputs and LLM outputs, so bad JSON fails loudly instead of silently.
- **Eval before polish.** A small golden dataset lives in the repo and runs on every change.
- **Plan for model failure.** Timeouts, retries, and a defined fallback, not a stack trace to the user.
- **Know the bill.** Token cost and latency are logged per request.

> *Does it work? Can we measure it? What happens when the model gets it wrong?*

---

## 🧰 Tech I can defend in an interview

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-0052CC?style=flat-square&logo=pinecone&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

| Daily use | Working knowledge | Learning now |
|---|---|---|
| Python, FastAPI, LangGraph, tool calling | Pinecone, Docker, MCP, Streamlit | Evaluation (Ragas / DeepEval), Langfuse tracing, pgvector, hybrid search + reranking |

<sub>Only list what you could build live in an interview. Move anything shaky to "Learning now".</sub>

---

## 📈 GitHub activity

<div align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Contribution graph"/>

</div>

---

<div align="center">

**Looking for a junior AI engineer who ships, tests, and explains tradeoffs?**
[Email me](mailto:hazziq595959@gmail.com) · [LinkedIn](https://www.linkedin.com/in/haziq-imran-778760312)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5D4,100:080808&height=100&section=footer" alt=""/>

</div>
