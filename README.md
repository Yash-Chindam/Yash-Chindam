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
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yashchindam@gmail.com)

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

[![MLflow](https://img.shields.io/badge/mlflow%2Fmlflow-PR%20merged-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)](https://github.com/mlflow/mlflow/pulls?q=is%3Apr+author%3AYash-Chindam)
[![Spec Kit](https://img.shields.io/badge/github%2Fspec--kit-4%20PRs%20merged-6C63FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/github/spec-kit/pulls?q=is%3Apr+author%3AYash-Chindam+is%3Amerged)
[![Superpowers](https://img.shields.io/badge/obra%2Fsuperpowers-2%20PRs%20open-00D4B1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/obra/superpowers/pulls?q=is%3Apr+author%3AYash-Chindam)

**6 upstream projects** · **5 PRs merged** · **7 PRs in review** · **2 packages published to a public catalog**

</div>

### [mlflow/mlflow](https://github.com/mlflow/mlflow) — the open-source AI engineering platform (~22k ★)

**Merged** · [`PR #25556`](https://github.com/mlflow/mlflow/pull/25556) merged into `master`

> LLM-as-a-judge scoring was unusable on Vertex AI's Claude models: every call failed with `anthropic_version: Field required`. The gateway's `adapter_class` path bypassed the provider's own `_prepare_payload()`, so the Vertex-specific request fields were never applied. I diagnosed it, filed [`#25543`](https://github.com/mlflow/mlflow/issues/25543), and fixed it at the adapter layer with a regression test covering the judge path.

**In review** · a 4-PR series implementing [`FR #25585`](https://github.com/mlflow/mlflow/issues/25585) — ~3,400 lines across 95 files

| PR | Scope |
|---|---|
| [`#25741`](https://github.com/mlflow/mlflow/pull/25741) | Run artifact requests in the UI use the stored artifact-proxy URI |
| [`#25742`](https://github.com/mlflow/mlflow/pull/25742) | Logged-model artifact requests |
| [`#25743`](https://github.com/mlflow/mlflow/pull/25743) | Model-version artifact requests |
| [`#25748`](https://github.com/mlflow/mlflow/pull/25748) | Trace attachment requests |

Also reported [`#25571`](https://github.com/mlflow/mlflow/issues/25571) — the Bedrock Titan and AI21 completions adapters silently drop `top_p` and `top_k`.

`Python` · `TypeScript` · `React` · `MLOps` · `LLM gateways`

---

### [github/spec-kit](https://github.com/github/spec-kit) — GitHub's Spec-Driven Development toolkit

**Core contribution** · [`PR #4250`](https://github.com/github/spec-kit/pull/4250) merged into `main`

> Presets could not declare that they depend on an extension, so installing one without its companion left users with a workflow that silently did nothing. I added `requires.extensions` to the preset manifest with strict PEP 440 validation, plus an install-time check that warns — and names the exact remediation — for missing, stale, disabled, corrupted, and version-mismatched dependencies.

**Merged fixes** · 3 additional PRs into `main`

| PR | What it fixed |
|---|---|
| [`#4424`](https://github.com/github/spec-kit/pull/4424) | The workflows reference guide had drifted from the shipped workflow on four points — version, minimum Spec Kit version, supported integrations, and the default integration. The guide told readers the default was `copilot` when it was actually `auto`. Reconciled the documented definition with the real one and added a test that fails if they diverge again. |
| [`#4397`](https://github.com/github/spec-kit/pull/4397) | `setup-plan` emitted a JSON key named `SPECS_DIR` that held the per-feature directory, while every sibling script used `SPECS_DIR` for the specs root — the same name meaning two different paths. Renamed it to `FEATURE_DIR` across the Bash, PowerShell, and Python ports with a parity test. |
| [`#4396`](https://github.com/github/spec-kit/pull/4396) | Template composition in `common.sh` looped forever when the resolved core content contained a literal `{CORE_TEMPLATE}`, because the loop re-tested the string it had just rewritten. Matched the already-correct PowerShell and Python semantics instead of inventing new ones. |

**Community catalog** · published, listed, and maintained at **v0.1.1**

| Package | What it does |
|---|---|
| [`speckit-inventory`](https://github.com/github/spec-kit/issues/4226) | Read-only extension that derives every live `FR-`/`NFR-`/`SC-`/`T-` ID from existing specs and returns focused per-task context packs instead of whole-file dumps |
| [`inventory-alignment`](https://github.com/github/spec-kit/issues/4227) | Preset that makes the agent classify each requirement against the live set before writing, so a reworded requirement is updated rather than duplicated |

Both shipped at v0.1.0, then updated to [v0.1.1](https://github.com/github/spec-kit/issues/4486) when I found the published entries pointed at a `download_url` that 404s — source at [`spec-kit-inventory-alignment`](https://github.com/Yash-Chindam/spec-kit-inventory-alignment).

**In review** · [`PR #4488`](https://github.com/github/spec-kit/pull/4488) — a bundled `github` extension for `taskstoissues`, implementing someone else's feature request ([`#4421`](https://github.com/github/spec-kit/issues/4421)). 1,541 lines across 13 files.

`Python` · `CLI tooling` · `agent workflows` · zero runtime dependencies

---

### Also contributed to

| Project | Contribution |
|---|---|
| [obra/superpowers](https://github.com/obra/superpowers) | [`#2263`](https://github.com/obra/superpowers/pull/2263) — brainstorming keeps the open question open when the user asks for context, instead of treating the request as an answer · [`#2259`](https://github.com/obra/superpowers/pull/2259) — re-resolve and verify relative links when skill content moves |
| [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) | Reported [`#8673`](https://github.com/langchain-ai/langgraph/issues/8673) — checkpoint serialization rejects any int outside the 64-bit range, though `Decimal` of the same value round-trips fine |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [`#7042`](https://github.com/crewAIInc/crewAI/pull/7042) — tools returning coroutines inside an already-running event loop |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [`#89498`](https://github.com/NousResearch/hermes-agent/pull/89498) — the curator dropped configured fallback chains instead of forwarding them |

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗%20Transformers-FFD43B?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**LLMs & Models**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral_AI-FF6B35?style=for-the-badge)
![LLaMA](https://img.shields.io/badge/LLaMA_2-1877F2?style=for-the-badge&logo=meta&logoColor=white)
![CLIP](https://img.shields.io/badge/CLIP-00B2FF?style=for-the-badge)
![BART](https://img.shields.io/badge/BART-F26207?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini_Pro-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Vector Databases & RAG**

![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-F7931A?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)
![BM25](https://img.shields.io/badge/BM25-6C63FF?style=for-the-badge)

**Data & Tools**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ [Secure MCP Multi-Agent Research Platform](https://github.com/Yash-Chindam/secure-mcp-multi-agent-research-platform)
> A governed research system where five FastMCP servers are driven through a single gateway that **authorizes, meters, circuit-breaks and audits every tool call**. Workflow state transitions reject invalid stage skipping, claims require supporting evidence, and reviewer approvals bind to one exact server, capability, resource and argument digest.

**Security model:** Rego policy-as-code that fails closed · Keycloak OIDC with an asymmetric algorithm allowlist · capability registry whose discovery reveals only what the caller may see · tenant-isolated jobs and evidence
**Stack:** `Python 3.12` `FastMCP` `FastAPI` `OPA/Rego` `Keycloak` `PostgreSQL` `Docker`

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

**Self-optimizing:** an evaluator scores retrieval recall, grounding and forbidden claims *deterministically* rather than by LLM judgment, then a control loop perturbs one pipeline field at a time within reviewer-approved bounds and keeps only Pareto-optimal candidates that never regress authorization, latency or quality
**Stack:** `Python` `LangGraph` `DSPy` `Qdrant` `OpenSearch` `Neo4j` `Presidio`

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

**Results:** RMSE `0.6041` · MSE `0.3649`
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
