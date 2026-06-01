<h1 align="center">Hi there, I'm Yarramaddi Kishor Kumar Reddy 👋</h1>
<h3 align="center">AI / ML Engineer · RAG & LLM Systems · Full-Stack Builder</h3>

---

## 🧠 About Me

I'm an AI/ML developer who likes taking ideas all the way from a Jupyter notebook to something a stranger on the internet can actually use. Most of my recent work sits at the intersection of **LLMs, Retrieval-Augmented Generation, and applied Deep Learning** — but I also enjoy classic ML, computer vision, and full-stack web development when a project calls for it.

- 🔭 Currently working on **agentic LLM tooling** and **RAG systems**
- 🧪 I care about the boring engineering bits — caching, chunking, routing, packaging, deployment
- 📦 Recently shipped **[pr-sentinel](https://github.com/kishor2004reddy/Pull-Request-Sentinel-CLI)** to PyPI
- 🌱 Always exploring: multi-agent orchestration, evaluation, and production-grade MLOps
- 📫 Reach me at: **[kishor04reddy@gmail.com]** · **[LinkedIn](https://www.linkedin.com/in/kishor-kumar-reddy-70b809283/)**

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


**AI / ML / Deep Learning**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**LLM & RAG Stack**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=chromadb&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=for-the-badge&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logoColor=white)

**Backend & Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🚀 Featured Projects

### 🛡️ [PR Sentinel CLI](https://github.com/kishor2004reddy/Pull-Request-Sentinel-CLI) · `Python` · *Published on PyPI*
A local pull-request review tool that runs **four specialized review agents** (Security, Code Quality, Performance, Testing) over a `git diff` via the Claude Code CLI and emits a structured JSON + Markdown report — so you fix issues *before* opening the PR.

- File-type-aware **routing** that skips irrelevant agents per chunk to save tokens
- Bounded-parallel orchestration via `ThreadPoolExecutor`
- SHA256-keyed **disk cache** with 90-day auto-prune
- A **Summary Agent** that deduplicates findings across all reviewers
- Deterministic risk-level verdict (High / Medium / Low / None / Unknown)
- Installable with `pip install pr-sentinel`

### 🎥 [YouTube RAG Chatbot](https://github.com/kishor2004reddy/YoutubeRAGchatbot) · `Python` · `LangChain` · `Streamlit`
Ask natural-language questions about any YouTube video and get **grounded, explainable answers** based strictly on its transcript.

- Pipeline: transcript ingestion → embeddings → ChromaDB → retrieval → LLM
- Uses **LLaMA-3.1** via Groq for low-latency inference
- **HuggingFace `all-MiniLM-L6-v2`** for embeddings
- Persistent per-video vector store — embed once, query forever
- Surfaces the exact transcript chunks used to derive each answer

### 🤟 [Sign Language Translator (ASL)](https://github.com/kishor2004reddy/SignLanguage_Translation) · `Deep Learning` · `Computer Vision`
Real-time American Sign Language recognition system that translates hand gestures to text from a webcam feed.

- **MobileNetV2** with transfer learning (last 30 layers fine-tuned)
- **MediaPipe Hands** for landmark detection and ROI cropping
- Prediction smoothing via a rolling deque buffer for stable output
- 29 ASL classes · 87,000+ training images

### 🎙️ [Podcast Listening Time Prediction](https://github.com/kishor2004reddy/PodcastListeningTimePrediction) · `Flask` · `TensorFlow` · *Deployed*
End-to-end ML web app predicting listener engagement from podcast features (genre, host popularity, sentiment, ad count, etc.).

- Modular pipeline: ingestion → transformation → training → evaluation → prediction
- Reusable preprocessor for consistent feature engineering between train and inference
- Live on Render: [podcastlisteningtimeprediction.onrender.com](https://podcastlisteningtimeprediction.onrender.com/)
---

## 🎯 What I'm Looking For

I'm interested in **AI/ML engineering roles** — especially anything touching LLM applications, RAG systems, agentic tooling, or applied deep learning. I enjoy building things that ship, owning a problem end-to-end, and writing the documentation I'd want to read myself.

---

## 🤝 Let's Connect

<p align="left">
  <a href="https://www.linkedin.com/in/kishor-kumar-reddy-70b809283/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:kishor04reddy@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/kishor2004reddy"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kishor2004reddy&label=Profile%20views&color=58A6FF&style=flat" alt="Profile views" />
</p>

<p align="center"><i>⭐ If you find my work useful, a star goes a long way!</i></p>
