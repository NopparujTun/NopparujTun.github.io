# Skills
---
<b>Programming</b>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white" alt="SQL"/>
</p>
<b>AI/ML</b>

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/NLP-5A67D8" alt="NLP"/>
  <img src="https://img.shields.io/badge/RAG-6B46C1" alt="RAG"/>
</p>
<b>Frameworks & Libraries</b>

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white" alt="NumPy"/>
</p>
<b>Databases & Vector Stores</b>

<p>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white" alt="Supabase"/>
  <img src="https://img.shields.io/badge/Firebase-DD2C00?logo=firebase&logoColor=white" alt="Firebase"/>
  <img src="https://img.shields.io/badge/FAISS-0467DF?logo=meta&logoColor=white" alt="FAISS"/>
  <img src="https://img.shields.io/badge/Pinecone-000000?logo=pinecone&logoColor=white" alt="Pinecone"/>
</p>
<b>Tools</b>

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" alt="Git"/>
</p>

---
# Experience
---
## Front-End Developer Intern at [Botnoi](https://www.botnoigroup.com/)
<b>Apr 2024 - Jun 2024</b> — Bangkok, Thailand<br />
<br />
<b>Accomplishments</b>
- Built and maintained reusable [Vue.js](https://vuejs.org/) components from [Figma](https://www.figma.com/) designs, delivering responsive user interfaces for both desktop and mobile platforms.
- Collaborated closely with designers and developers to translate UI/UX requirements into functional frontend features using Vue.js, [Tailwind CSS](https://tailwindcss.com/), and [Vite](https://vitejs.dev/).
- Assisted in reviewing frontend performance and code quality by identifying large assets, oversized bundles, and responsive layout issues affecting usability and load performance.

---
# Projects
---
## Thai Sentiment Analysis: WangchanBERTa vs Baseline

[![Static Badge](https://img.shields.io/badge/Open_in_Colab-blue?style=flat&logo=googlecolab&labelColor=grey)](https://colab.research.google.com/drive/1RQvTdfjL0yJ0PGoU9kGntPhkpbhpOvt9?usp=sharing)

<div style="text-align: justify">
A comparative study fine-tuning a Thai RoBERTa model (WangchanBERTa) against a classical machine learning baseline for 3-class sentiment classification, evaluated on the real-world Wisesight Sentiment dataset.
</div>
![Thai Sentiment Analysis Results](/images/sentiment.png)
<br />
<b>Key Features</b>
- <b>Transformer Fine-Tuning</b>: Fine-tuned [WangchanBERTa](https://huggingface.co/airesearch/wangchanberta-base-att-spm-uncased) (Thai RoBERTa) for 3-class sentiment classification (positive / neutral / negative) on the 21K-sample [Wisesight Sentiment](https://huggingface.co/datasets/pythainlp/wisesight_sentiment) dataset using the HuggingFace [Trainer](https://huggingface.co/docs/transformers/main_classes/trainer) API, reaching <b>76% accuracy</b> and <b>0.72 macro-F1</b>.
- <b>Baseline Benchmarking</b>: Built a TF-IDF + Naive Bayes baseline and compared both models under shared metrics, demonstrating a <b>+10-point accuracy</b> and <b>+16-point macro-F1</b> gain from contextual pre-training — most notably tripling recall on the minority positive class (0.19 → 0.51).
- <b>Thai NLP Pipeline</b>: Handled Thai's spaceless script with [PyThaiNLP](https://pythainlp.github.io/) word tokenization, and visualized per-class errors with confusion matrices.



<b>Tools / Technologies</b>
- ML / NLP: [PyTorch](https://pytorch.org/), [HuggingFace Transformers](https://huggingface.co/docs/transformers), [Scikit-learn](https://scikit-learn.org/), [PyThaiNLP](https://pythainlp.github.io/)
- Data / Visualization: [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/)

---
## Agentic RAG Chatbot

[![Static Badge](https://img.shields.io/badge/View_on_GitHub-blue?style=flat&logo=github&labelColor=grey)](https://github.com/NopparujTun/agentic-rag-chatbot)
![GitHub Repo stars](https://img.shields.io/github/stars/NopparujTun/agentic-rag-chatbot?style=flat&logo=github)

<div style="text-align: justify">
A production-grade retrieval-augmented generation system for institutional domain knowledge, orchestrating LLM tool-use via LangChain and LangGraph with a FastAPI backend.
</div>
<br />
<b>Key Features</b>
- <b>Agentic Orchestration</b>: Architected a production-grade RAG system for institutional domain knowledge, orchestrating LLM tool-use via [LangChain](https://www.langchain.com/) and [LangGraph](https://www.langchain.com/langgraph) with a [FastAPI](https://fastapi.tiangolo.com/) backend.
- <b>Hybrid Search + Reranking</b>: Improved retrieval performance from an <b>86.8%</b> dense-search baseline to <b>92.3% MRR@10</b> and <b>90.0% Recall@1</b> by implementing a Hybrid Search engine ([Pinecone](https://www.pinecone.io/) + BM25) with Cross-Encoder Reranking.
- <b>Dual-Language NLP Pipeline</b>: Built a Thai/English NLP ingestion pipeline using [PyThaiNLP](https://pythainlp.github.io/) for accurate text segmentation across dual-language institutional documents.

<b>Tools / Technologies</b>
- Backend: [Python](https://www.python.org/), [FastAPI](https://fastapi.tiangolo.com/)
- LLM orchestration: [LangChain](https://www.langchain.com/), [LangGraph](https://www.langchain.com/langgraph)
- Vector store: [Pinecone](https://www.pinecone.io/)
- Frontend: [React](https://react.dev/)
- NLP: [PyThaiNLP](https://pythainlp.github.io/)

---
## EduGenie - AI Teaching Assistant

[![Static Badge](https://img.shields.io/badge/View_on_Devpost-blue?style=flat&logo=devpost&labelColor=grey)](https://devpost.com/software/edugenie-r2iq7l)
[![Static Badge](https://img.shields.io/badge/Bolt_Hackathon_Certificate-green?style=flat&logo=googledrive&labelColor=grey)](https://drive.google.com/file/d/1aR8QRpu4lKgjXSpsotQIE0S71kVwqjqe/view)

<div style="text-align: justify">
A full-stack AI assistant enabling educators to generate lesson plans and quizzes using LLMs, built during the <b>Bolt Hackathon 2025</b> organized by Botnoi Group.
</div>
<br />
<b>Key Features</b>
- <b>AI-Powered Content Generation</b>: Built a full-stack AI assistant enabling educators to generate lesson plans and quizzes using LLMs.
- <b>LLM Integration</b>: Integrated [OpenRouter](https://openrouter.ai/) APIs with the frontend to handle prompt requests and display structured AI-generated content.
- <b>Rapid Prototyping</b>: Rapidly prototyped and iterated using AI-assisted development tools and GitHub in a fast-paced hackathon environment.

<b>Tools / Technologies</b>
- Frontend: [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/)
- Backend / Database: [Supabase](https://supabase.com/)
- LLM API: [OpenRouter](https://openrouter.ai/)

---
# Education
---
## [Chiang Mai University](https://www.cmu.ac.th/)
<b>M.Sc. in Computer Science</b> — Chiang Mai, Thailand  
<b>2026 - Present</b>  
Relevant Coursework: Machine Learning, Artificial Intelligence, Natural Language Processing

## [Chiang Mai University](https://www.cmu.ac.th/)
<b>B.Sc. in Computer Science</b> — Chiang Mai, Thailand  
<b>2022 - 2026</b>

---
<center>© 2026 Nopparuj Tunnukij. Powered by Jekyll and the Minimal Theme.</center>
