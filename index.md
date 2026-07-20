# Skills
---
<b>Languages:</b> Thai (Native), English (Fluent)<br>
<b>Programming:</b> Python, TypeScript, JavaScript, Go, SQL<br>
<b>AI/ML:</b> PyTorch, Scikit-learn, LangChain, NLP, RAG<br>
<b>Frameworks & Libraries:</b> FastAPI, React, Vue.js, Node.js, Next.js, Pandas, NumPy<br>
<b>Databases & Vector Stores:</b> Supabase, Firebase, FAISS, Pinecone<br>
<b>Tools:</b> Docker, Git

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
## Thai Sentiment Analysis: Fine-tuning WangchanBERTa

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](projects/WangchanBERTa_sentiment.html)

<div style="text-align: justify">
In this notebook, I use the Hugging Face Transformers library to fine-tune WangchanBERTa, a Thai RoBERTa model, for three-class sentiment classification. I then compare its performance with a traditional machine learning baseline using TF-IDF features and a Multinomial Naive Bayes classifier. The Hugging Face ecosystem enables efficient fine-tuning of a state-of-the-art Thai language model, resulting in 76% accuracy and 0.72 macro-F1, with 10% higher accuracy and 16% higher macro-F1 than the baseline model.</div>
![Thai Sentiment Analysis Results](/images/sentiment-diagram.png)
<br />

<b>Tools / Technologies</b>
- ML / NLP: [PyTorch](https://pytorch.org/), [HuggingFace Transformers](https://huggingface.co/docs/transformers), [Scikit-learn](https://scikit-learn.org/), [PyThaiNLP](https://pythainlp.github.io/)
- Data / Visualization: [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/)

---
## Rating Prediction from Thai Restaurant Reviews

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](projects/stars_rating_prediction.html)

<div style="text-align: justify">
In this notebook, I develop and compare three regression models to predict continuous star ratings (1–5) from Thai restaurant reviews. The models—Ridge Regression, Random Forest, and XGBoost—are trained using TF-IDF features to evaluate how linear and tree-based approaches perform on sparse, high-dimensional text data. The workflow also includes Thai-specific text preprocessing with custom regex cleaning and PyThaiNLP tokenization, along with N-gram exploratory analysis and WordCloud visualizations. Finally, I evaluate and compare model performance using MAE and MSE.</div>
![Rating Prediction Results](/images/stars_prediction_diagram.png)
<br />

<b>Tools / Technologies</b>
- ML / NLP: [Scikit-learn](https://scikit-learn.org/), [XGBoost](https://xgboost.ai/), [PyThaiNLP](https://pythainlp.github.io/)
- Data / Visualization: [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), [WordCloud](https://www.wordclouds.com/)

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
