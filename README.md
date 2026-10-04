<div align="center">

<!-- Dynamic Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:00D4B1&height=200&section=header&text=Yash%20Chindam&fontSize=52&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=AI%20%7C%20ML%20Engineer%20%7C%20LLM%20Enthusiast&descAlignY=58&descSize=20" alt="header"/>

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=6C63FF&center=true&vCenter=true&multiline=false&width=650&lines=🤖+Building+intelligent+AI+systems;🧠+LLMs+%7C+RAG+%7C+Deep+Learning;🔬+Research+in+Drug-Protein+Interaction;🗂️+NLP+%7C+Computer+Vision+%7C+Generative+AI;🚀+Turning+ideas+into+intelligent+solutions)](https://git.io/typing-svg)

<br/>

<!-- Social Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashchindam/)
[![Hugging Face](https://img.shields.io/badge/🤗%20HuggingFace-FFD43B?style=for-the-badge&logoColor=black)](https://huggingface.co/yashchindam)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yash-Chindam)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yash.chindam@gmail.com)

<br/>

</div>

---

## 👋 About Me

```python
class YashChindam:
    def __init__(self):
        self.name        = "Yash Chindam"
        self.role        = "AI / ML Engineer"
        self.focus       = ["LLMs", "RAG Systems", "Computer Vision", "NLP", "Deep Learning"]
        self.passion     = "Building AI systems that solve real-world problems"
        self.currently   = "Exploring Generative AI & multimodal research"
        self.hf_profile  = "https://huggingface.co/yashchindam"

    def say_hi(self):
        print("Thanks for dropping by! Let's build something intelligent together 🚀")

me = YashChindam()
me.say_hi()
```

---

## 🌍 Open Source

<div align="center">

[![Spec Kit](https://img.shields.io/badge/github%2Fspec--kit-5%20PRs%20merged-6C63FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/github/spec-kit/pulls?q=is%3Apr+author%3AYash-Chindam+is%3Amerged)
[![MLflow](https://img.shields.io/badge/mlflow%2Fmlflow-2%20PRs%20merged-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)](https://github.com/mlflow/mlflow/pulls?q=is%3Apr+author%3AYash-Chindam+is%3Amerged)

**7 PRs merged** · **1 bundled extension shipped inside Spec Kit** · **2 packages in its community catalog**

</div>

### [github/spec-kit](https://github.com/github/spec-kit) — GitHub's Spec-Driven Development toolkit

| Merged | What it was |
|---|---|
| [`#4488`](https://github.com/github/spec-kit/pull/4488) | **Bundled `github` extension** for `taskstoissues` — ships inside Spec Kit's own catalog. Task resolver ported across Bash, PowerShell and Python. 2,455 lines / 13 files / 24 review rounds, 1,422 of them tests. Built another user's feature request ([`#4421`](https://github.com/github/spec-kit/issues/4421)). |
| [`#4250`](https://github.com/github/spec-kit/pull/4250) | **Preset-to-extension dependencies.** Installing a preset without its companion silently did nothing. Added `requires.extensions` with PEP 440 validation and an install-time check naming the exact remediation for five failure states. |
| [`#4424`](https://github.com/github/spec-kit/pull/4424) · [`#4397`](https://github.com/github/spec-kit/pull/4397) · [`#4396`](https://github.com/github/spec-kit/pull/4396) | Three fixes — reference docs that had drifted from the shipped workflow (plus a test that fails on future drift), one JSON key meaning two different paths across three language ports, and template composition looping forever on a literal token. |

**Community catalog** · [`speckit-inventory`](https://github.com/github/spec-kit/issues/4226) (extension) and [`inventory-alignment`](https://github.com/github/spec-kit/issues/4227) (preset) — published and maintained at **v0.1.1**, source at [`spec-kit-inventory-alignment`](https://github.com/Yash-Chindam/spec-kit-inventory-alignment).

### [mlflow/mlflow](https://github.com/mlflow/mlflow) — the open-source AI engineering platform (~22k ★)

| Merged | What it was |
|---|---|
| [`#25556`](https://github.com/mlflow/mlflow/pull/25556) | LLM-as-a-judge scoring failed on **every** Vertex AI Claude model — the gateway's `adapter_class` path bypassed the provider's own `_prepare_payload()`, so Vertex request fields were never applied. Diagnosed it, filed [`#25543`](https://github.com/mlflow/mlflow/issues/25543), fixed it with a regression test. |
| [`#25795`](https://github.com/mlflow/mlflow/pull/25795) | Bedrock Titan and AI21 adapters silently dropped `top_p` — set by the caller, never sent, no error raised. Reported as [`#25571`](https://github.com/mlflow/mlflow/issues/25571), then mapped it onto each adapter's native field name. 22 lines of fix, 104 of test. |

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [Secure MCP Multi-Agent Research Platform](https://github.com/Yash-Chindam/secure-mcp-multi-agent-research-platform)
> A governed research system where five FastMCP servers are driven through a single gateway that **authorizes, meters, circuit-breaks and audits every tool call**. CrewAI planner, researcher, analyst, critic and reporter agents run on a durable Temporal workflow with a reviewer checkpoint. Workflow state transitions reject invalid stage skipping, claims require evidence the platform verifies against recorded tool calls, and reviewer approvals bind to one exact server, capability, resource and argument digest.

**Security model:** Rego policy-as-code that fails closed · Keycloak OIDC with an asymmetric algorithm allowlist · capability registry whose discovery reveals only what the caller may see · PostgreSQL row-level security per tenant
**Stack:** `Python 3.12` `FastMCP` `CrewAI` `Temporal` `FastAPI` `OPA/Rego` `Keycloak` `PostgreSQL` `Redis` `Docker`

</td>
<td width="50%" valign="top">

### 🔀 [Production Local-LLM Inference & Routing Platform](https://github.com/Yash-Chindam/Production-Local-LLM-Inference-Routing-Platform)
> An **OpenAI-compatible control plane** that routes each request across local model tiers on inferred task, privacy class and policy score. Every response records the selected model, its immutable revision, the candidate count and the reason it was chosen — so a routing decision is auditable after the fact.

**Engineering:** three separately reported CI layers (unit/static, integration, Playwright) gate the release image · CD publishes a versioned OCI artifact · production startup refuses the dev key
**Stack:** `Python` `FastAPI` `Ray Serve` `vLLM` `TypeScript` `Playwright` `Docker`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🔍 [Self-Optimizing Production RAG Platform](https://github.com/Yash-Chindam/self-optimizing-production-rag-platform)
> RAG that **cites or abstains** — never guesses. The query path is an explicit state machine (classify → clarify → rewrite → decompose → retrieve → generate → verify → repair), so an ambiguous question gets clarified and an unverified answer is narrowed to its best-supported sentence before falling back.

**Self-optimizing:** an evaluator scores retrieval recall, grounding and forbidden claims *deterministically* rather than by LLM judgment, then a control loop perturbs one pipeline field at a time within reviewer-approved bounds and keeps only Pareto-optimal candidates that never regress authorization, latency or quality · store adapters and the Helm chart are exercised against real services in CI
**Stack:** `Python` `LangGraph` `DSPy` `Qdrant` `OpenSearch` `Neo4j` `Presidio` `RAGAS` `MLflow`

</td>
<td width="50%" valign="top">

### 🔒 [LLM Security & Agent Guardrail Gateway](https://github.com/Yash-Chindam/llm-security-agent-guardrail-gateway)
> A policy-aware gateway that inspects untrusted prompts, retrieved context, model output and proposed tool actions **before they cross a security boundary**. Risky actions return an approval token bound to the exact action digest, tenant, expiry, and one-time use.

**Adversarial evaluation:** a PyRIT-style red-team suite covering direct and indirect injection, multi-turn jailbreak, encoded instructions, cross-tenant access, tool privilege escalation and MCP tool poisoning — scored against a committed baseline so a regression **fails CI** instead of landing silently
**Stack:** `Python` `FastAPI` `PyRIT` `Bandit` `Trivy` `Playwright` `Docker`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧬 [Drug-Protein Interaction Prediction](https://github.com/Yash-Chindam/Drug-Protein-Interaction-Prediction-Using-CLIP-and-Deep-Learning)
> Predicts drug-protein binding strength (*Ki* values) using **OpenAI's CLIP** vision encoders on 2D molecular images and protein sequence logos.

**Results:** RMSE `0.6041` · MSE `0.3649` · 118K drug-protein pairs
**Stack:** `PyTorch` `CLIP` `RDKit` `Transformers` `CUDA`

[![HuggingFace](https://img.shields.io/badge/🤗%20Model-FFD43B?style=flat-square)](https://huggingface.co/yashchindam/Drug-Protein-Interaction-Prediction-Using-CLIP-and-Deep-Learning)
[![Dataset](https://img.shields.io/badge/🤗%20Dataset-FFD43B?style=flat-square)](https://huggingface.co/datasets/yashchindam/Drug-Protein-Interaction-Prediction-Using-CLIP-and-Deep-Learning)

</td>
<td width="50%" valign="top">

### 🏦 [Finlyzer — Bank Statement & Credit Report Analyzer](https://github.com/Yash-Chindam/AI-Powered-Bank-Statement-Credit-Report-Analyzer)
> Financial document analysis that uses **Google Gemini** vision to extract, categorize and summarize transactions from bank statements and credit reports, then surfaces recurring patterns, credit score, open loans and overdue status.

**Throughput:** 9-step automated pipeline · parallel processing across up to 4 API keys via `ThreadPoolExecutor`
**Stack:** `Gemini Pro` `FastAPI` `Streamlit` `GCS` `Docker`

</td>
</tr>
</table>

<details>
<summary><b>🗂️ More Projects (click to expand)</b></summary>

<br/>

| Project | Description | Stack |
|---|---|---|
| [Intelligent Claims Document Processing](https://github.com/Yash-Chindam/Intelligent-Claims-Document-Processing) | **ClaimLens AI** — agentic pipeline for US commercial property insurance across 8+ document types | `LangGraph` `Azure OpenAI` `Pydantic` |
| [AI-Powered Natural Language to SQL Engine](https://github.com/Yash-Chindam/AI-Powered-Natural-Language-to-SQL-Engine) | **NaturalSQL** — plain English to executable PostgreSQL via SQLCoder-7b-2 | `SQLCoder-7b-2` `PyTorch` `Cloud SQL` |
| [AI Voice Onboarding System](https://github.com/Yash-Chindam/AI--Voice-Onboarding-System) | Modular AI onboarding framework with multi-LLM support and guided setup workflows | `LangChain` `LlamaIndex` `FastAPI` |
| [RFP Document Info Extraction via LLMs](https://github.com/Yash-Chindam/RFP-Document-Information-Extraction-Using-LLMs) | Structured extraction from RFP documents, 85–92% accuracy at 30–60s/doc | `GPT-4` `LangChain` `PyPDF2` |
| [Vision-Based Entity Extraction](https://github.com/Yash-Chindam/Vision-Based-Entity-Extraction) | OCR + NER over forms, invoices, ID cards and business cards — entity F1 80–92% | `EasyOCR` `spaCy` `YOLO` |
| [Multi-PDF Chatbot with RAG & FAISS](https://github.com/Yash-Chindam/Multi_Pdf_chatbot_using_RAG_and_Faiss_with_Mistral_Nemo) | Chat across many PDFs at once with RAG over FAISS | `Mistral Nemo` `FAISS` `LangChain` |
| [ECO2 — Environmental ML Platform](https://github.com/Yash-Chindam/ECO2) | Carbon footprint tracking, climate modeling and biodiversity assessment | `GeoPandas` `NetCDF4` `Plotly` |
| [YouTube Video Summarizer](https://github.com/Yash-Chindam/Youtube_Video_Transcribe_Summarizer_using_Gemini_pro) | Transcribes and summarizes YouTube videos with a Streamlit UI | `Gemini Pro` `Streamlit` |
| [RAG w/ LLaMA2 + LangChain + ChromaDB](https://github.com/Yash-Chindam/RAG-using-llama2-langchain-and-chromadb) | End-to-end RAG pipeline using LLaMA 2 | `LLaMA 2` `ChromaDB` |
| [PDF Chatbot with RAG](https://github.com/Yash-Chindam/PDF-Chatbot-with-RAG) | Conversational PDF Q&A with RAG architecture | `RAG` `FAISS` `LLMs` |
| [Image Captioning](https://github.com/Yash-Chindam/Image-Captioning) | Deep learning-based automatic image captioning | `PyTorch` `CNN` `LSTM` |
| [License Plate Recognition](https://github.com/Yash-Chindam/LICENSE-PLATE) | Automatic license plate detection and OCR | `OpenCV` `OCR` |
| [Text Summarization — BART](https://github.com/Yash-Chindam/Text_Summarization_using_BART) | Abstractive text summarization with BART | `BART` `Transformers` |
| [Research Paper Title Generator — BART](https://github.com/Yash-Chindam/Research_paper_title_generator_using_bart_base) | Fine-tuned BART for academic title generation | `BART` `Transformers` |
| [Movie Title Generator — Flan-T5](https://github.com/Yash-Chindam/Movie_title_generator_using_flanT5_base) | Flan-T5 fine-tuned for cinematic title generation | `Flan-T5` `HuggingFace` |
| [Predicting Credit Card Approvals](https://github.com/Yash-Chindam/Predicting-Credit-Card-Approvals) | ML classifier for credit card approval prediction | `scikit-learn` `Pandas` |
| [RAG Implementation & Prompt Optimization](https://github.com/Yash-Chindam/RAG_Implementation_and_Prompt_Optimization) | Benchmarking and optimizing RAG prompt strategies | `RAG` `LLMs` |

</details>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Agents & LLM Orchestration**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![AGNO](https://img.shields.io/badge/AGNO-FF4017?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge)
![Temporal](https://img.shields.io/badge/Temporal-141414?style=for-the-badge)

**Retrieval & Knowledge**

![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-F7931A?style=for-the-badge)
![Graph RAG](https://img.shields.io/badge/Graph_RAG-6C63FF?style=for-the-badge)

**Serving & Infrastructure**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FDB515?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**MLOps & Evaluation**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge)
![RAGAS](https://img.shields.io/badge/RAGAS-6C63FF?style=for-the-badge)

**Cloud & Deep Learning**

![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗%20Transformers-FFD43B?style=for-the-badge)
![CLIP](https://img.shields.io/badge/CLIP-00B2FF?style=for-the-badge)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Yash-Chindam&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6C63FF&icon_color=00D4B1&text_color=C9D1D9&rank_icon=github" height="165" alt="GitHub Stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yash-Chindam&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6C63FF&text_color=C9D1D9" height="165" alt="Top Languages"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Yash-Chindam&theme=tokyonight&hide_border=true&background=0D1117&ring=6C63FF&fire=00D4B1&currStreakLabel=6C63FF" alt="GitHub Streak"/>

<br/><br/>

[![Yash's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Yash-Chindam&theme=tokyo-night&bg_color=0D1117&color=6C63FF&line=00D4B1&point=6C63FF&hide_border=true)](https://github.com/Yash-Chindam)

</div>

---

## 🤗 Hugging Face

<div align="center">

**Published models & datasets on Hugging Face**

[![HuggingFace Profile](https://img.shields.io/badge/🤗%20yashchindam-FFD43B?style=for-the-badge&logoColor=black)](https://huggingface.co/yashchindam)

| Resource | Link |
|:---:|:---:|
| 🧬 Drug-Protein Interaction Model | [yashchindam/Drug-Protein-Interaction-Prediction-Using-CLIP-and-Deep-Learning](https://huggingface.co/yashchindam/Drug-Protein-Interaction-Prediction-Using-CLIP-and-Deep-Learning) |
| 📦 Drug-Protein Dataset | [datasets/yashchindam/Drug-Protein-Interaction-Prediction-Using-CLIP-and-Deep-Learning](https://huggingface.co/datasets/yashchindam/Drug-Protein-Interaction-Prediction-Using-CLIP-and-Deep-Learning) |

</div>

---

## 🏆 Highlights

<div align="center">

![Trophy](https://github-profile-trophy.vercel.app/?username=Yash-Chindam&theme=tokyonight&no-frame=true&margin-w=8&column=7)

</div>

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=Yash-Chindam&color=6C63FF&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views"/>

<br/><br/>

*"The best way to predict the future is to invent it."* — **Alan Kay**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4B1,100:6C63FF&height=120&section=footer" alt="footer"/>

</div>
