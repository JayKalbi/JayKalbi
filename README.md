<div align="center">
  <h1>Hi, I'm Jay Kalbi 👋</h1>
  
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&weight=600&size=20&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&height=40&lines=AI+Engineer+%7C+M.Tech+in+AI+%40+NMIMS;Building+Enterprise+LLMs+%26+Financial+AI;Specializing+in+RAG%2C+QLoRA+%26+MLOps" alt="Typing SVG" />
  </a>

  <p>Building production-grade Large Language Model systems, Financial AI, Enterprise RAG, and Edge AI solutions.</p>

  <p>
    <a href="https://linkedin.com/in/jaykalbi"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="https://jaydkalbi2004.wixsite.com/portfolio"><img src="https://img.shields.io/badge/Portfolio-FF6C37?style=for-the-badge&logo=wix&logoColor=white" alt="Portfolio"/></a>
    <a href="mailto:jdkalbi18@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  </p>
</div>

---

### 👨‍💻 About Me

I am an **AI Engineer** specializing in **Large Language Models (LLMs)**, **Explainable AI (XAI)**, and **Predictive Analytics** for high-stakes enterprise applications. 

Currently pursuing my **M.Tech in Artificial Intelligence at NMIMS MPSTME**, I focus on architecting hybrid ML/LLM systems, regulatory-compliant AI risk engines, multi-stage RAG pipelines, and edge-deployed computer vision systems backed by government grants.

- 🎓 **Education**: M.Tech in AI @ NMIMS MPSTME (2026–Present) | B.Tech in Computer Engineering @ BVM (CGPI: 8.84)
- 💼 **Experience**: Ex-Machine Learning Intern @ HPParam IT Solutions | Ex-Backend Intern @ TechnoGuide Infosoft
- 🎯 **Current Focus**: Agentic RAG, Multi-Agent Orchestration, Financial AI Compliance (EU AI Act / Basel III), & Quantized LLM Fine-tuning (QLoRA)

---

### 🚀 Featured Flagship Projects

#### 🏛️ [HybridCredit-LLM: Institutional Risk Engine](https://github.com/JayKalbi/institutional-risk-engine)
> *An enterprise-grade multimodal credit risk assessment platform fusing quantitative tabular ML with Generative AI and strict Basel III regulatory auditability.*
- ⚙️ **Multimodal Architecture**: Fuses **LightGBM** (processing HMDA tabular data for PD & ECL) with a QLoRA fine-tuned **Mistral-7B / Llama-3.3-70B** (via Groq Inference) for qualitative underwriting memorandums, ensembled via a Logistic Regression Meta-Learner.
- 📊 **Performance Metrics**: Achieved **0.985 AUC-ROC** (0.9845 AUC / 0.9693 PR-AUC) outperforming LightGBM baseline (0.6709 AUC), XGBoost (0.6692 AUC), and Logistic Regression (0.6513 AUC).
- ⚖️ **Compliance & XAI**: Basel III compliant, **SHAP TreeExplainer** feature attributions, and **ECOA Fair Lending Demographic Audits** certifying zero disparate impact under CFPB rules.
- 🎨 **Web Interface**: Custom Flask production app featuring a Dark Mode Glassmorphism UI with real-time LLM streaming.
- 🛠️ **Tech Stack**: `Python` `PyTorch` `Hugging Face` `QLoRA` `LightGBM` `XGBoost` `SHAP` `Llama-3.3-70B` `Mistral-7B` `Flask` `Streamlit`
- 🔗 **Repository**: [github.com/JayKalbi/institutional-risk-engine](https://github.com/JayKalbi/institutional-risk-engine)

#### 🔍 [Enterprise Hybrid RAG Intelligence Engine](https://github.com/JayKalbi/hybrid-rag-engine)
> *Production-hardened hybrid retrieval-augmented generation system for SEC 10-K financial document question-answering.*
- ⚙️ **Retrieval Pipeline**: Multi-stage retrieval combining **Dense Vector Search** (`all-MiniLM-L6-v2` in ChromaDB) and **Sparse Search** (BM25 Okapi) merged via **Reciprocal Rank Fusion (RRF)**, followed by a **Cross-Encoder Reranker** (`ms-marco-MiniLM-L-6-v2`).
- 🧠 **Grounded Generation**: Powered by **Llama 3.1 8B Instant** (Groq) with automated inline citation validation to eliminate hallucinations. Automated **LLM-as-Judge** evaluation using **Llama 3.3 70B**.
- 🛠️ **Tech Stack**: `Python` `LangChain` `ChromaDB` `BM25 Okapi` `Cross-Encoder` `Llama 3.1 8B` `Llama 3.3 70B` `Flask` `Waitress` `Docker` `GitHub Actions`
- 🔗 **Repository**: [github.com/JayKalbi/hybrid-rag-engine](https://github.com/JayKalbi/hybrid-rag-engine)

#### 💡 [Intelligent Edge Automation System (SSIP Funded ₹1.2 Lakh)](https://github.com/JayKalbi/JetsonNano-OpenCV-Mediapipe-SetUP)
> *Award-winning real-time computer vision & automation platform deployed on edge hardware.*
- 🏅 **Grant & IP**: Awarded **₹1,20,000 grant** under Student Startup & Innovation Policy (SSIP), Govt. of Gujarat. Pending IPR Patent.
- ⚡ **Optimization**: JetPack 4.6 on **NVIDIA Jetson Nano/Orin** with custom swapfile memory allocation, CUDA pipelines, and RTSP video streaming, achieving **+25% cost efficiency**.
- 🛠️ **Tech Stack**: `NVIDIA Jetson` `CUDA` `OpenCV` `MediaPipe` `TensorFlow` `Python` `RTSP`
- 🔗 **Repository**: [github.com/JayKalbi/JetsonNano-OpenCV-Mediapipe-SetUP](https://github.com/JayKalbi/JetsonNano-OpenCV-Mediapipe-SetUP)

#### ✉️ [Enterprise NLP Engine: Business Email Classifier](https://github.com/JayKalbi/Email-Classification-with-LSTM)
> *Intelligent text classification pipeline built for enterprise email workflow automation.*
- 📩 **Performance**: Trained Bidirectional LSTM neural network on **500K+ records** (Enron Email Dataset) achieving **~90% classification accuracy** across Business, HR, Legal, and Finance categories.
- 🔬 **Analytics**: Preprocessing with KNN clustering for label reduction, PCA & t-SNE embedding visualization, Gmail API integration, and an interactive Streamlit dashboard.
- 🛠️ **Tech Stack**: `TensorFlow/Keras` `BiLSTM` `NLP` `Scikit-Learn` `t-SNE` `PCA` `Gmail API` `Streamlit` `Pandas`
- 🔗 **Repository**: [github.com/JayKalbi/Email-Classification-with-LSTM](https://github.com/JayKalbi/Email-Classification-with-LSTM)

#### ☁️ [Production MLOps & AWS CI/CD Pipeline](https://github.com/JayKalbi/aws-ci-cd-mlproject)
> *Automated continuous integration and continuous deployment pipeline for production machine learning models.*
- 🛠️ **Tech Stack**: `Docker` `GitHub Actions` `AWS EC2` `AWS ECR` `Python` `Flask`
- 🔗 **Repository**: [github.com/JayKalbi/aws-ci-cd-mlproject](https://github.com/JayKalbi/aws-ci-cd-mlproject)

---

### 🛠️ Technical Skills

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Generative AI & LLMs** | Large Language Models, PEFT / QLoRA, Fine-Tuning, Prompt Engineering, RAG, LangChain, Llama 3.3 70B, Llama 3.1 8B, Mistral-7B, Groq API |
| **Machine Learning & NLP** | LightGBM, XGBoost, Scikit-learn, TensorFlow, PyTorch, BiLSTM, SHAP (XAI), PCA, t-SNE, Predictive Analytics |
| **MLOps & Infrastructure** | Docker, GitHub Actions, AWS (EC2/ECR), CI/CD for ML, Flask, Waitress, Streamlit |
| **Programming & DBs** | Python, SQL, C++, REST APIs, PHP PDO |
| **Edge AI & Hardware** | NVIDIA Jetson Orin NX, NVIDIA Jetson Nano, CUDA, RTSP, OpenCV, MediaPipe |

---

### 📊 GitHub Statistics

<div align="center">
  <a href="https://github.com/JayKalbi">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=JayKalbi&theme=dark&hide_border=true" alt="Jay's GitHub Streak" width="49%"/>
  </a>
  <a href="https://github.com/JayKalbi">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=JayKalbi&theme=github-dark&hide_border=true" alt="Jay's Activity Graph" width="49%"/>
  </a>
</div>

<p align="center">
  <img src="https://img.shields.io/github/followers/JayKalbi?label=Followers&style=for-the-badge&logo=github&color=238636" alt="Followers"/>
  <img src="https://img.shields.io/badge/Public_Repos-21+-blue?style=for-the-badge&logo=github" alt="Public Repos"/>
</p>

---

### 🤝 Let's Connect

- 💼 **LinkedIn**: [linkedin.com/in/jaykalbi](https://linkedin.com/in/jaykalbi)
- 🌐 **Portfolio**: [jaydkalbi2004.wixsite.com/portfolio](https://jaydkalbi2004.wixsite.com/portfolio)
- 📧 **Email**: [jdkalbi18@gmail.com](mailto:jdkalbi18@gmail.com)

*"Building intelligent, production-ready AI systems that drive real-world impact."*
