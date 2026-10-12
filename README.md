<div align="center">
<img src="assets/header.svg" alt="Yamin Hossain — Applied AI, Backend Engineering, Data" width="100%">
<br>
<br>
I build AI-enabled applications and data tools — retrieval systems, multi-agent pipelines, and the backend around them. My attention sits where the model meets the system: where context comes from, how a service degrades, and whether someone else can read it and run it.
<br>
<br>
<a href="https://www.yaminhossain.fun/"><img src="assets/badges/portfolio.svg" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/yamin-hossain-38a3b3263"><img src="assets/badges/linkedin.svg" alt="LinkedIn profile"></a>
<a href="https://www.kaggle.com/yaminh"><img src="assets/badges/kaggle.svg" alt="Kaggle profile"></a>
<a href="https://huggingface.co/RobinMillford"><img src="assets/badges/huggingface.svg" alt="Hugging Face profile"></a>
<a href="mailto:issan.yamin@gmail.com"><img src="assets/badges/email.svg" alt="Email Yamin Hossain"></a>
</div>

---

## ◆ Selected Work

### ▸ AI applications and agent systems

#### [Ai-Finance](https://github.com/RobinMillford/Ai-Finance)

<img align="right" src="assets/projects/ai-finance.png" width="380" alt="FinanceAI market analysis dashboard with live stock, forex and crypto data">

Market analysis for stocks, forex, and crypto, run through a parallel agent pipeline. One low-temperature supervisor call returns a plan; LangGraph then fans the chosen specialists out simultaneously, so a three-agent read costs the same three model hops as a single-agent one. *Generated analysis, not investment advice.*

![LangGraph](assets/badges/langgraph.svg) ![Next.js](assets/badges/next-js.svg) ![TypeScript](assets/badges/typescript.svg) ![PostgreSQL](assets/badges/postgresql.svg) ![Groq](assets/badges/groq.svg)

**[Source](https://github.com/RobinMillford/Ai-Finance)** · **[Live app](https://financeai-ai.duckdns.org/)**

<br clear="all">

#### [FrameIQ](https://github.com/RobinMillford/FrameIQ)

<img align="right" src="assets/projects/frameiq.png" width="380" alt="FrameIQ film and television discovery interface with search and trending titles">

A film and television library — watchlist, diary, episode tracking, social feed — built around CineBot, an assistant that routes requests without spending an LLM call, so ordinary questions cost no extra inference. Conversation state is checkpointed to SQLite in WAL mode, which keeps memory intact across restarts and redeploys.

![Flask](assets/badges/flask.svg) ![LangGraph](assets/badges/langgraph.svg) ![OpenAI](assets/badges/openai.svg) ![PostgreSQL](assets/badges/postgresql.svg)

**[Source](https://github.com/RobinMillford/FrameIQ)** · **[Live app](https://frameiq.studio/)**

<br clear="all">

### ▸ Retrieval and applied deep learning

#### [Cortex AI — Multi-Model Insights Hub](https://github.com/RobinMillford/Cortex-AI-Multi-Model-Insights-Hub)

<img align="right" src="assets/projects/cortex-ai.png" width="380" alt="Cortex AI multimodal RAG interface showing retrieved hybrid-search context and a source-cited answer">

Retrieval over documents, figures, and video transcripts, grounded with BM25 keyword scoring running beside sentence-transformer embeddings rather than trusting vectors alone. Figures pass through a vision model first, and it is that description — not the raw image — that gets embedded and searched. Answers carry source references.

![Streamlit](assets/badges/streamlit.svg) ![ChromaDB](assets/badges/chromadb.svg) ![BM25](assets/badges/bm25.svg) ![LangGraph](assets/badges/langgraph.svg)

**[Source](https://github.com/RobinMillford/Cortex-AI-Multi-Model-Insights-Hub)**

<br clear="all">

#### [GopherNotebook](https://github.com/RobinMillford/GopherNotebook)

A local-first document workspace with a Go/Gin backend. Weaviate runs hybrid BM25-and-vector retrieval, a Qwen3 cross-encoder reranks the top candidates, and answers cite a file and page. Ingestion and reranking stay on your own machine; generation can go local or to any cloud provider.

![Go](assets/badges/go.svg) ![Next.js](assets/badges/next-js.svg) ![Weaviate](assets/badges/weaviate.svg) ![LocalAI](assets/badges/localai.svg) ![Docker](assets/badges/docker.svg)

**[Source](https://github.com/RobinMillford/GopherNotebook)**

<br clear="all">

#### [Art Intelligence Hub](https://github.com/RobinMillford/Art-Intelligence-Hub)

<img align="right" src="assets/projects/art-hub.png" width="380" alt="Art style ensemble classifier returning an Art Nouveau verdict with per-model confidence bars for EfficientNetV2 and ConvNeXt">

Two vision problems kept deliberately apart: is this artwork AI-made or human-made, and which style is it? Authenticity runs a fine-tuned MobileNetV2 with Grad-CAM heatmaps marking the regions behind the call, while style is soft-voted across EfficientNetV2-B2 and ConvNeXt-Small, with each model's confidence shown separately rather than hidden behind the ensemble.

![TensorFlow](assets/badges/tensorflow.svg) ![Grad-CAM](assets/badges/grad-cam.svg) ![Streamlit](assets/badges/streamlit.svg) ![OpenCV](assets/badges/opencv.svg)

**[Source](https://github.com/RobinMillford/Art-Intelligence-Hub)** · **[Training notebook](https://www.kaggle.com/code/yaminh/ai-vs-real-project)**

<br clear="all">

### ▸ Data analytics and workflow automation

#### [Analytics for Fashion Supply Management](https://github.com/RobinMillford/Analytics_for_Fashion_Supply_Management)

<img align="right" src="assets/projects/supply-chain.png" width="380" alt="Fashion supply chain dashboard showing total revenue, order quantity, availability, stock and lead-time metrics">

Ten linked views over a single fashion supply-chain file, built to make trade-offs legible rather than to fill a dashboard. The one worth opening first is price against manufacturing cost per product type, which turns a revenue total into an actual margin — the gap between what a garment sells for and what it cost to make.

![Streamlit](assets/badges/streamlit.svg) ![DuckDB](assets/badges/duckdb.svg) ![Plotly](assets/badges/plotly.svg) ![Pandas](assets/badges/pandas.svg)

**[Source](https://github.com/RobinMillford/Analytics_for_Fashion_Supply_Management)**

<br clear="all">

#### [My n8n Workflows](https://github.com/RobinMillford/My_n8n_workflows)

<img align="right" src="assets/projects/n8n.png" width="380" alt="n8n canvas showing the research agent split into query refiner, research manager, dataset agent and compiler branches">

A 42-node research agent that lives inside Telegram. A Switch fans each query into parallel web-research and dataset-hunting branches, three different models handle refinement, long-context extraction, and synthesis respectively, and results are logged to Supabase before coming back out as a file. It imports as JSON; the credentials are yours to supply.

![n8n](assets/badges/n8n.svg) ![Supabase](assets/badges/supabase.svg) ![Tavily](assets/badges/tavily.svg) ![LangChain](assets/badges/langchain.svg)

**[Source](https://github.com/RobinMillford/My_n8n_workflows)**

<br clear="all">

---

## ◆ GitHub Activity

<div align="center">
<b>Public GitHub Activity</b>
<br>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=RobinMillford&amp;include_all_commits=true&amp;show=reviews,prs_merged&amp;hide_rank=true&amp;theme=transparent&amp;disable_animations=true&amp;hide=issues,contributed_to,prs" alt="Public GitHub Activity: total stars earned, all-time public commits, pull requests merged, and pull requests reviewed" width="460">
<br>
<br>
<b>Recent Commits</b>
<br>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=RobinMillford&amp;hide_rank=true&amp;theme=transparent&amp;disable_animations=true&amp;hide=stars,issues,contributed_to,prs,prs_merged,reviews" alt="Total public commits in the last year" width="460">
<br>
<sub>Public GitHub activity; counts reflect GitHub's available statistics and may be cached.</sub>
</div>

---

## ◆ Toolkit

Drawn from what the projects above actually run on.

**AI & retrieval**
![LangGraph](assets/badges/langgraph.svg) ![LangChain](assets/badges/langchain.svg) ![OpenAI](assets/badges/openai.svg) ![Groq](assets/badges/groq.svg) ![HuggingFace](assets/badges/huggingface.svg) ![TensorFlow](assets/badges/tensorflow.svg)

**Languages & backend**
![Python](assets/badges/python.svg) ![Go](assets/badges/go.svg) ![TypeScript](assets/badges/typescript.svg) ![Flask](assets/badges/flask.svg) ![PostgreSQL](assets/badges/postgresql.svg)

**Data & visualization**
![Pandas](assets/badges/pandas.svg) ![DuckDB](assets/badges/duckdb.svg) ![Plotly](assets/badges/plotly.svg) ![Streamlit](assets/badges/streamlit.svg)

**Automation & infrastructure**
![n8n](assets/badges/n8n.svg) ![Docker](assets/badges/docker.svg) ![GitHub Actions](assets/badges/github-actions.svg)

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