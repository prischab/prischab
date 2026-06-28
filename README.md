# Prischa Bajeli

CS undergrad (AI & Data Science) @ MIT-WPU · 2× published researcher (IEEE, Springer) · Building end-to-end ML, agentic AI, and full-stack systems

<p align="left">
  <a href="https://linkedin.com/in/prischa-bajeli"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://prischab.github.io/"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:prischabajeli2k5@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About

Third-year Computer Science (AI & Data Science) undergrad at MIT World Peace University, Pune. I build systems end to end — from hardware (Raspberry Pi IoT) to deployed ML pipelines, agentic AI, and full-stack apps. Two peer-reviewed publications to date. Currently looking for an internship.

---

## Publications

**[IoT-Enabled Face Recognition Attendance System Using Raspberry Pi and OpenCV](https://ieeexplore.ieee.org/document/11436752)** — *IEEE ETCOM 2025*
Prischa Bajeli · [[Paper]](https://ieeexplore.ieee.org/document/11436752) · [[Code]](https://github.com/prischab/iot-face-recognition-attendance-system)
- Presents an edge-deployed LBPH facial recognition system running entirely on a Raspberry Pi 4, achieving **95%+** recognition accuracy across **50+** student profiles while removing all manual logging from the attendance workflow.

**[Multivariate Time-Series Prediction of Energy Consumption Using Recursive Feature Elimination (RFE) and LSTM–Keras](https://link.springer.com/chapter/10.1007/978-3-032-20606-0_49)** — *Springer LNNS, ICTCS 2025*
Prischa Bajeli, et al. · [[Paper]](https://link.springer.com/chapter/10.1007/978-3-032-20606-0_49) · [[Code]](https://github.com/prischab/multivariate-energy-consumption-prediction)
- Proposes an RFE-LSTM forecasting pipeline trained on **35K** hourly energy samples, cutting MAE/RMSE by **up to 7%** via recursive feature elimination and an ablation study, identifying short lag features (lag 1–3) as the dominant predictive signals.

---

## Projects

### Agentic AI & Applied ML
| Project | Description | Stack |
|---|---|---|
| [Research-agent-Siora2k5](https://github.com/prischab/Research-agent-Siora2k5) | Agentic AI research assistant that autonomously selects and chains tools (web search, calculator, document RAG, image vision) for multi-step questions. Agent built **both from scratch and with LangGraph**; FastAPI backend, Next.js chat UI, 100% tool-selection eval. | Python, Claude API, LangGraph, FastAPI, Next.js |
| [medguide-rag](https://github.com/prischab/medguide-rag) | Retrieval-augmented Q&A over medical guideline PDFs — semantic chunking, vector search, and grounded answers with source citations. | Python, ChromaDB, sentence-transformers, FastAPI |
| [explainai](https://github.com/prischab/explainai) | Explainable AI for multi-label chest X-ray classification. DenseNet121 on NIH ChestX-Ray14 (112k images, 14 pathologies), patient-stratified splits, **0.83 macro-AUC**; FastAPI REST endpoint + GUI with Grad-CAM visualization. | Python, PyTorch, FastAPI |

### MLOps & Data Science
| Project | Description | Stack |
|---|---|---|
| [heart-disease-mlops](https://github.com/prischab/heart-disease-mlops) | End-to-end MLOps pipeline: trained classifier served via FastAPI, containerized with Docker, and wired to a GitHub Actions CI pipeline with automated tests. | Python, scikit-learn, Docker, FastAPI, GitHub Actions |
| [credit-risk-analysis](https://github.com/prischab/credit-risk-analysis) | Credit default risk modeling on the "Give Me Some Credit" dataset (150K records) — EDA, feature engineering, and Logistic Regression vs. Random Forest (**ROC-AUC 0.84**) with a business-framed conclusion. | Python, Pandas, scikit-learn, Jupyter |
| [Primetrade-ds-assignment](https://github.com/prischab/Primetrade-ds-assignment) | End-to-end analysis of Bitcoin Fear & Greed Index vs. Hyperliquid trader performance — EDA through modeling. | Python, Pandas, Jupyter |

### Published Research Code
| Project | Description | Stack |
|---|---|---|
| [iot-face-recognition-attendance-system](https://github.com/prischab/iot-face-recognition-attendance-system) | Edge-deployed LBPH face recognition attendance on Raspberry Pi 4. Published @ IEEE ETCOM 2025. | Python, OpenCV, SQLite |
| [multivariate-energy-consumption-prediction](https://github.com/prischab/multivariate-energy-consumption-prediction) | RFE-LSTM time-series forecasting on UCI household power data. Published @ Springer ICTCS 2025. | Keras, TensorFlow, Jupyter |

### Full-Stack
| Project | Description | Stack |
|---|---|---|
| [Job-AI](https://github.com/prischab/Job-AI) | AI-powered mobile career copilot — resume optimization, cover letters, application tracking, tailored cold outreach. | React Native, Expo, Express.js, PostgreSQL, Claude API |
| [Archive-2k5](https://github.com/prischab/Archive-2k5) | Full-stack thrift e-commerce store with a dual checkout flow — custom UPI QR verification and Razorpay integration. | Next.js, Prisma, Clerk, Cloudinary |
| [prischab.github.io](https://github.com/prischab/prischab.github.io) | Personal portfolio site, hand-built multi-page HTML/CSS, no frameworks. | HTML, CSS |

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Web & Backend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

**Databases & Tools**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)

---

## GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prischab&layout=compact&theme=default" alt="Top Languages"/>
</p>
