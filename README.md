<div align="center">

<img src="assets/header.svg" alt="Yamin Hossain — Applied AI, Backend Engineering, Data" width="100%">

<br>

I build AI-enabled applications and data tools — retrieval systems, multi-agent pipelines, and the backend around them. My attention sits where the model meets the system: where context comes from, how a service degrades, and whether someone else can read it and run it.

<br>

<a href="https://www.yaminhossain.fun/"><img src="https://img.shields.io/badge/Portfolio-0ea5e9?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/yamin-hossain-38a3b3263"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn profile"></a>
<a href="https://www.kaggle.com/yaminh"><img src="https://img.shields.io/badge/Kaggle-20beff?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle profile"></a>
<a href="https://huggingface.co/RobinMillford"><img src="https://img.shields.io/badge/HuggingFace-ffd21e?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face profile"></a>
<a href="mailto:issan.yamin@gmail.com"><img src="https://img.shields.io/badge/Email-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email Yamin Hossain"></a>

</div>

---

## ◆ Selected Work

### ▸ AI applications and agent systems

#### [Ai-Finance](https://github.com/RobinMillford/Ai-Finance)

<img align="right" src="assets/projects/ai-finance.png" width="380" alt="FinanceAI market analysis dashboard with live stock, forex and crypto data">

Market analysis for stocks, forex, and crypto, run through a parallel agent pipeline. One low-temperature supervisor call returns a plan; LangGraph then fans the chosen specialists out simultaneously, so a three-agent read costs the same three model hops as a single-agent one. *Generated analysis, not investment advice.*

![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-f55036?style=flat-square)

**[Source](https://github.com/RobinMillford/Ai-Finance)** · **[Live app](https://financeai-ai.duckdns.org/)**

<br clear="all">

#### [FrameIQ](https://github.com/RobinMillford/FrameIQ)

<img align="right" src="assets/projects/frameiq.png" width="380" alt="FrameIQ film and television discovery interface with search and trending titles">

A film and television library — watchlist, diary, episode tracking, social feed — built around CineBot, an assistant that routes requests without spending an LLM call, so ordinary questions cost no extra inference. Conversation state is checkpointed to SQLite in WAL mode, which keeps memory intact across restarts and redeploys.

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white)

**[Source](https://github.com/RobinMillford/FrameIQ)** · **[Live app](https://frameiq.studio/)**

<br clear="all">

### ▸ Retrieval and applied deep learning

#### [Cortex AI — Multi-Model Insights Hub](https://github.com/RobinMillford/Cortex-AI-Multi-Model-Insights-Hub)

<img align="right" src="assets/projects/cortex-ai.png" width="380" alt="Cortex AI multimodal RAG interface showing retrieved hybrid-search context and a source-cited answer">

Retrieval over documents, figures, and video transcripts, grounded with BM25 keyword scoring running beside sentence-transformer embeddings rather than trusting vectors alone. Figures pass through a vision model first, and it is that description — not the raw image — that gets embedded and searched. Answers carry source references.

![Streamlit](https://img.shields.io/badge/Streamlit-ff4b4b?style=flat-square&logo=streamlit&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-8a2be2?style=flat-square) ![BM25](https://img.shields.io/badge/BM25-5a6472?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white)

**[Source](https://github.com/RobinMillford/Cortex-AI-Multi-Model-Insights-Hub)**

<br clear="all">

#### [GopherNotebook](https://github.com/RobinMillford/GopherNotebook)

A local-first document workspace with a Go/Gin backend. Weaviate runs hybrid BM25-and-vector retrieval, a Qwen3 cross-encoder reranks the top candidates, and answers cite a file and page. Ingestion and reranking stay on your own machine; generation can go local or to any cloud provider.

![Go](https://img.shields.io/badge/Go-00add8?style=flat-square&logo=go&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Weaviate](https://img.shields.io/badge/Weaviate-00ab6c?style=flat-square) ![LocalAI](https://img.shields.io/badge/LocalAI-f59e0b?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white)

**[Source](https://github.com/RobinMillford/GopherNotebook)**

<br clear="all">

#### [Art Intelligence Hub](https://github.com/RobinMillford/Art-Intelligence-Hub)

<img align="right" src="assets/projects/art-hub.png" width="380" alt="Art style ensemble classifier returning an Art Nouveau verdict with per-model confidence bars for EfficientNetV2 and ConvNeXt">

Two vision problems kept deliberately apart: is this artwork AI-made or human-made, and which style is it? Authenticity runs a fine-tuned MobileNetV2 with Grad-CAM heatmaps marking the regions behind the call, while style is soft-voted across EfficientNetV2-B2 and ConvNeXt-Small, with each model's confidence shown separately rather than hidden behind the ensemble.

![TensorFlow](https://img.shields.io/badge/TensorFlow-ff6f00?style=flat-square&logo=tensorflow&logoColor=white) ![Grad-CAM](https://img.shields.io/badge/Grad-CAM-e2574c?style=flat-square) ![Streamlit](https://img.shields.io/badge/Streamlit-ff4b4b?style=flat-square&logo=streamlit&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5c3ee8?style=flat-square&logo=opencv&logoColor=white)

**[Source](https://github.com/RobinMillford/Art-Intelligence-Hub)** · **[Training notebook](https://www.kaggle.com/code/yaminh/ai-vs-real-project)**

<br clear="all">

### ▸ Data analytics and workflow automation

#### [Analytics for Fashion Supply Management](https://github.com/RobinMillford/Analytics_for_Fashion_Supply_Management)

<img align="right" src="assets/projects/supply-chain.png" width="380" alt="Fashion supply chain dashboard showing total revenue, order quantity, availability, stock and lead-time metrics">

Ten linked views over a single fashion supply-chain file, built to make trade-offs legible rather than to fill a dashboard. The one worth opening first is price against manufacturing cost per product type, which turns a revenue total into an actual margin — the gap between what a garment sells for and what it cost to make.

![Streamlit](https://img.shields.io/badge/Streamlit-ff4b4b?style=flat-square&logo=streamlit&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-f00000?style=flat-square&logo=duckdb&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3f4f75?style=flat-square&logo=plotly&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**[Source](https://github.com/RobinMillford/Analytics_for_Fashion_Supply_Management)**

<br clear="all">

#### [My n8n Workflows](https://github.com/RobinMillford/My_n8n_workflows)

<img align="right" src="assets/projects/n8n.png" width="380" alt="n8n canvas showing the research agent split into query refiner, research manager, dataset agent and compiler branches">

A 42-node research agent that lives inside Telegram. A Switch fans each query into parallel web-research and dataset-hunting branches, three different models handle refinement, long-context extraction, and synthesis respectively, and results are logged to Supabase before coming back out as a file. It imports as JSON; the credentials are yours to supply.

![n8n](https://img.shields.io/badge/n8n-ea4b71?style=flat-square&logo=n8n&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ecf8e?style=flat-square&logo=supabase&logoColor=white) ![Tavily](https://img.shields.io/badge/Tavily-ff4d00?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square)

**[Source](https://github.com/RobinMillford/My_n8n_workflows)**

<br clear="all">

---

## ◆ Toolkit

Drawn from what the projects above actually run on.

**AI & retrieval**
![LangGraph](https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-f55036?style=flat-square&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-ffd21e?style=flat-square&logo=huggingface&logoColor=black) ![TensorFlow](https://img.shields.io/badge/TensorFlow-ff6f00?style=flat-square&logo=tensorflow&logoColor=white)

**Languages & backend**
![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00add8?style=flat-square&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat-square&logo=postgresql&logoColor=white)

**Data & visualization**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-f00000?style=flat-square&logo=duckdb&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3f4f75?style=flat-square&logo=plotly&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-ff4b4b?style=flat-square&logo=streamlit&logoColor=white)

**Automation & infrastructure**
![n8n](https://img.shields.io/badge/n8n-ea4b71?style=flat-square&logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088ff?style=flat-square&logo=githubactions&logoColor=white)

---

## ◆ Research & Publications

Peer-reviewed work, mostly on computer vision.

- **ICDMIS 2024** — [Machine Learning for Computer Vision: A Comprehensive Overview](https://link.springer.com/chapter/10.1007/978-981-96-6053-7_7)
- **ICMIB 2024** — [Improving Sports Categorization in WiFi-Blocked Areas: Modifying YOLO Network for All-Inclusive Sports Image Identification](https://link.springer.com/chapter/10.1007/978-981-96-3797-3_19)
- **ICICCT 2024** — [YOLOv8 Image Processing for Evaluation of Stability Algorithms Based on Neural Networks: A Sports Use Case](https://link.springer.com/chapter/10.1007/978-981-97-7710-5_46)

---

<div align="center">
  <img src="https://raw.githubusercontent.com/RobinMillford/RobinMillford/output/snake.svg" alt="Contribution graph" width="62%">
</div>

---

The longer write-up of this work, plus background and the rest of the repository archive, is at **[yaminhossain.fun](https://www.yaminhossain.fun/)**. For implementation detail the source is the better reference — [issan.yamin@gmail.com](mailto:issan.yamin@gmail.com) if either is not enough.