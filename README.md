# Hi, I'm Yashraj Jadhav 👋

**MS Business Analytics (STEM) @ USC Marshall · Data Scientist · ML Engineer**

![Profile Views](https://komarev.com/ghpvc/?username=yashraj10&color=blue&style=flat)

I build ML systems that ship. Right now I'm an AI Engineering Intern at GrantAide, working on a 3-agent GenAI pipeline. Before that, my production work at Capgemini included a causal inference pipeline that supported roughly $4.2M in pharmaceutical go/no-go decisions. What sticks with me from that project isn't the model. It's a clinical lead who changed her recommendation based on what the analysis actually surfaced. Outside of client work I've trained a Transformer from scratch on 200K behavioral sequences, built a LangGraph multi-agent pipeline for automated code review, and deployed a 3-model ICU census forecaster behind a FastAPI service on GCP.

What I care about usually isn't the model itself. It's what happens after it ships: latency under load, drift, and whether the person on the other end of the dashboard actually trusts the output enough to act on it.

---

## 🧠 What I Work On

**Production ML & Deployment**
3-model ICU census forecasting system (Random Forest, Ridge regression, survival analysis) deployed as a FastAPI microservice on GCP Cloud Run. Dockerized with 6 endpoints, Pydantic v2 validation, 12 integration tests, and p50/p95 latency instrumentation for real-time serving.

**Distributed Data & Scale (PySpark)**
Neural Collaborative Filtering recommender trained on the 32M-row MovieLens dataset. PySpark handled feature engineering and ratings-matrix construction; TensorFlow trained the NCF model; Airflow orchestrated the pipeline; MLflow tracked experiments. A 4-tier AWS S3 data lake sat underneath it, with PSI-gated drift monitoring to decide when a new model replaced the incumbent.

**Causal Inference & Business Decisions**
Causal inference work at Capgemini that informed $4.2M in pharma investment decisions. Treatment and control cohorting, stratified subgroup analysis, effect sizes with confidence intervals. SHAP interpretability on the XGBoost churn models and PSI for drift detection once they were live.

**Deep Learning from Scratch**
Custom PyTorch Transformer encoder (4 layers, 4 attention heads, 128-dim) built from scratch for rage-quit prediction on 200K Dota 2 behavioral sequences. AUC-PR of 0.269, ahead of XGBoost, LSTM, and logistic regression baselines. Attention weights extracted via forward hooks to understand which in-game events the model actually keyed on.

**Agentic AI & LLM Pipelines**
AI Repo Co-Pilot: a 5-node LangGraph pipeline using GPT-4o-mini for automated code review. 33 of 33 adversarial evaluation tests passing, with multi-step orchestration, structured output validation, and self-healing fallback logic for when a node returns malformed output.

**RAG & LLM Evaluation**
Decision Twin: a retention strategy recommender built on the Gemini API and RAG. Benchmarked grounded vs. ungrounded LLM output against accuracy, hallucination rate, and business coherence on a held-out set.

---

## 💼 Professional Experience

**AI Engineering Intern @ GrantAide** *(Current)*
Working on a 3-agent GenAI pipeline in production. Contributing across agent design, prompt and tool specification, and the evaluation harness used to measure pipeline quality before changes ship.

**Data Scientist @ Capgemini Technology Services** *(July 2022 – August 2024)*
Production ML on 500K+ patient records for pharma and provider clients. Hospital readmission classifier deployed as a TensorFlow SavedModel on GCP Cloud Run, running at AUC-ROC 0.84, F1 0.63, and 99.8% request success rate. K-Means diagnostic clustering across 2.5 TB of records. SQL ETL pipelines moving 50K+ records daily into the serving layer.

**Data Science Intern @ Capgemini Technology Services** *(March 2022 – July 2022)*
Profiled 300K+ patient records and ran hypothesis testing across three clinical units, which shaped feature selection for the production models that came later.

---

## 🛠️ Tech Stack

### 🔤 Languages

![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)

### 🔧 Libraries and Frameworks

![pandas](https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PySpark](https://img.shields.io/badge/PYSPARK-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![NumPy](https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PyTorch](https://img.shields.io/badge/PYTORCH-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TENSORFLOW-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/KERAS-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/SCIKIT--LEARN-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBOOST-189AB4?style=for-the-badge&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HUGGINGFACE-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/TRANSFORMERS-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LANGGRAPH-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OPENAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/GEMINI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![FastAPI](https://img.shields.io/badge/FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/STREAMLIT-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/SEABORN-4C72B0?style=for-the-badge&logo=python&logoColor=white)

### ⚙️ Tools & Platforms

![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![SageMaker](https://img.shields.io/badge/SAGEMAKER-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLFLOW-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Airflow](https://img.shields.io/badge/AIRFLOW-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/SPARK-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/KAFKA-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![REST-API](https://img.shields.io/badge/REST--API-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white)
![Tableau](https://img.shields.io/badge/TABLEAU-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/POWER%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

### 💻 Operating Systems

![macOS](https://img.shields.io/badge/MACOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📝 Writing

I write about ML systems, model interpretability, and production engineering on Medium.
→ [Rage Quit Predictor: Building a Transformer from Scratch](https://medium.com/@yashrajjadhav269)

---

## 🔗 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/yashrajjadhav/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=github&logoColor=white)](https://yashraj10.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/yashraj10)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:yashrajjadhav269@gmail.com)

---

*"Production ML isn't about the model. It's about what happens after."*
