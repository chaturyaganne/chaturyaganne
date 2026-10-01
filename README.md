# Hi, I'm Chaturya Ganne

**ML/AI Engineer** | **MS Applied Machine Learning @ University of Maryland (May 2027)** | **5x Published Researcher**

I build RAG systems, agentic pipelines, and computer vision models, and ship them as real systems. Looking for **full-time New Grad 2027 roles** in ML engineering, AI engineering, data science, and software engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chaturya-ganne-6b85a7178/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=SAiN8-oAAAAJ)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://chaturyaganne.github.io/portfolio/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cganne@umd.edu)

---

## Recent Highlights

- **Cut document review from 2 weeks to 4 hours (95%+)** with a production RAG pipeline (OpenSearch, reranking, LangChain, LangGraph) that processed 2,000 documents in 4 hours at Daiichi Sankyo
- **Sped up cross-department information routing by 70%** by automating a manual workflow, deployed in 5 days
- **2x production inference speed** on Groq workloads and **+25% image-processing throughput** from fine-tuned transformer and diffusion models at AwoneDataSciences
- **2 papers at IWSHM 2025 (Stanford University)** on railway safety with vision transformers, 5 publications in total
- **92% AUC-ROC** chest X-ray diagnosis tool across 15 thoracic diseases: [Live Demo](https://chaturyaganne.github.io/medical_diaganois_tool/)
- **4.0 GPA** in the MS Applied Machine Learning program at UMD

---

## Experience

- **Daiichi Sankyo US** (Global Development Information Management Intern, Jun 2026 to present): enterprise RAG systems and knowledge-discovery apps with FastAPI, SQL, and React/Angular
- Adaptive computer vision: RL policies that trade off accuracy against energy in real-time video
- LLM agents that learn to operate legacy enterprise software with no API
- Coursework in optimization of ML algorithms and computing systems for ML

---

## Featured Projects

### [AI Medical Diagnosis Tool](https://github.com/chaturyaganne/medical_diaganois_tool)
**ResNet50 + Grad-CAM + LLaMA 3.2** | **92% AUC-ROC on 15 thoracic diseases**

Chest X-ray diagnostic system with Grad-CAM heatmaps for clinician interpretability. LLaMA 3.2 (via Hugging Face) drafts radiology reports and cut draft time by 60%.

`PyTorch` `Computer Vision` `Generative AI` `Grad-CAM` `Healthcare AI`

[Live Demo](https://chaturyaganne.github.io/medical_diaganois_tool/)

---

### [Smart Railway Safety System](https://www.dpi-proceedings.com/index.php/shm2025/article/view/37360)
**RT-DETR + YOLOv8 + Mask R-CNN + ViLT** | **F1 0.89** | **Published at IWSHM 2025, Stanford**

Multi-model computer vision sensor suite for obstacle detection and track health monitoring. It improved obstacle-detection precision by 15, and a Vision-Language Transformer (ViLT) fusion model reached an F1 score of 0.89 in track risk scoring.

`Vision Transformers` `Object Detection` `Segmentation` `Deep Learning` `Published Research`

[Read Paper](https://www.dpi-proceedings.com/index.php/shm2025/article/view/37360)

---

### AdaptAlloc: Adaptive Object Detection with Contextual Bandits
**REINFORCE + YOLOv8 + RT-DETR + Streamlit + Docker**

A policy network routes each video frame to YOLOv8 (fast, low energy) or RT-DETR (accurate, high energy) using a 9-dimensional scene-complexity state (Shannon entropy, detection uncertainty). A live Streamlit dashboard benchmarks it against Always-YOLO and Always-RT-DETR baselines, and the full stack runs in Docker.

`Reinforcement Learning` `Computer Vision` `PyTorch` `Docker` `Streamlit`

---

### IMRT Radiation Treatment Planner
**CVXPY + Convex Optimization on PortPy**

Formulates IMRT beamlet optimization as a convex program that meets clinical dose limits (PTV at least 60 Gy, esophagus at most 45 Gy, spinal cord at most 30 Gy). A spectral regularizer serves as a memory-efficient stand-in for nuclear-norm minimization, reducing fluence-matrix rank while keeping D95 at least 60 Gy.

`Convex Optimization` `CVXPY` `Python` `Healthcare AI`

---

### Computer-Use Automation System for Legacy Enterprise Apps
**LLM agent + Playwright**

An agent learns to operate API-less legacy UIs, then turns each successful run into a versioned, replayable capability that runs deterministically with zero LLM calls. A 5-state error taxonomy and same-session human handoff separate real failures from legitimate application outcomes.

`LLM Agents` `Playwright` `Automation` `Reliability`

---

### [AwoneDataSciences Internship Work](https://github.com/chaturyaganne/awone_internship)
**+25% throughput** | **150ms lower latency** | **2x inference speed**

Fine-tuned transformer and diffusion models in PyTorch, built a virtual call assistant (STT/TTS + NLP) for e-commerce support, and optimized Groq workloads with operations research techniques.

`Transformers` `Diffusion Models` `NLP` `Model Optimization` `Production ML`

---

## Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**ML / Deep Learning**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Agentic AI and RAG**  
![LangChain](https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=chainlink&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)
![LLaMA](https://img.shields.io/badge/LLaMA-0467DF?style=flat-square&logo=meta&logoColor=white)

**Computer Vision and Model Serving**  
YOLO, RT-DETR, Mask R-CNN, ViLT, Grad-CAM, Triton Inference Server, ONNX, TensorRT, CUDA

**MLOps, Cloud, and Backend**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Data Engineering and Analytics**  
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

## Publications

1. **[Smart Railway Safety: Integrating Deep Learning with Vision Transformers for Obstacle Detection and Track Health Monitoring](https://doi.org/10.12783/shm2025/37360)**  
   *IWSHM 2025, Stanford University* | DEStech Transactions on Structural Health Monitoring

2. **[AI-Driven Railway Maintenance for Fault Identification Through Object Detection and Segmentation](https://doi.org/10.12783/shm2025/37361)**  
   *IWSHM 2025, Stanford University* | DEStech Transactions on Structural Health Monitoring

3. **Predicting Duration of Vertical Ground Motions for the Himalayan Region Using Machine Learning Techniques**  
   *ICOAI 2024* | 11th International Conference on Artificial Intelligence

4. **Time-Frequency Analysis of Strong Ground Motions from the 1989 Loma Prieta Earthquake**

5. **Time-Frequency Analysis of Strong Ground Motions from the 1994 Northridge Earthquake**

Full list on [Google Scholar](https://scholar.google.com/citations?hl=en&user=SAiN8-oAAAAJ).

---

## Achievements

- **Merit Scholarship** for all four years at Mahindra University (2021 to 2025)
- **Conference presenter:** ICRESH 2024 (BARC, Mumbai) and IWSHM 2025 (Stanford)
- **5 peer-reviewed publications** in AI and structural health monitoring
- **IET Member** since April 2023

---

## About Me

I'm a graduate student in **Applied Machine Learning** at the University of Maryland, College Park, graduating May 2027. My work bridges research and production: transformer and diffusion models in PyTorch, RAG and agentic pipelines with LangChain and LangGraph, and deployment with FastAPI, Docker, and MLflow.

**Research interests:** Vision Transformers, Reinforcement Learning, Multimodal AI, Healthcare AI, Infrastructure Monitoring

**Currently seeking:** Full-time New Grad 2027 roles in ML engineering, AI engineering, data science, and software engineering. I'm especially interested in RAG, agentic systems, and applied computer vision.

---

## Get In Touch

I'm happy to talk about ML projects, research, or open roles.

- **Email:** [cganne@umd.edu](mailto:cganne@umd.edu)
- **LinkedIn:** [Chaturya Ganne](https://www.linkedin.com/in/chaturya-ganne-6b85a7178/)
- **Portfolio:** [chaturyaganne.github.io/portfolio](https://chaturyaganne.github.io/portfolio/)
- **Google Scholar:** [Publications](https://scholar.google.com/citations?hl=en&user=SAiN8-oAAAAJ)
