# 👋 Hi, I'm Abrar Altaf Lone

**Data / ML Engineer** with an M.S. in Data Science from **Pace University, New York**.
I build and ship data and ML systems end to end — from pipelines and models to
deployment — with a strong focus on making things that actually work in production.

---

## 🚀 Featured Projects

### 🎯 [Deepfake Detection System](https://deepfakedetection.xyz) — *deployed, self-hosted*
A live multi-model deepfake-detection service I built and host myself.
- 5-model deep-learning ensemble (ResNet-18, EfficientNet-B4, R3D-18, ViT-B/16, R3D-18+RAFT) with calibrated soft-voting — cut the cross-dataset generalization gap ~27% (FaceForensics++ → Celeb-DF)
- FastAPI backend on **AWS EC2 (GPU, Docker)**, Next.js frontend on Vercel, model weights versioned on Hugging Face Hub
- Includes a documented **negative result** (a frequency-domain detector that learned codec artifacts, not forgery signals — excluded from production)
- 🔗 Live demo: [deepfakedetection.xyz](https://deepfakedetection.xyz)

### 🏗️ [Biblo Data Pipeline](https://github.com/abraraltaf92/biblo-data-pipeline) — *end-to-end data engineering*
The data backend for Biblo — answers "which independent bookstore near me carries this book?"
- Multi-source ingestion (OpenStreetMap + Open Library) into a **PostgreSQL** warehouse
- Modeled with **dbt** into a star schema (`dim_bookstore`, `dim_book`, `fact_inventory`) with **16 data-quality tests**
- Orchestrated with **Airflow**, fully containerized with **Docker**
- Idempotent, re-runnable, production-style pipeline

### 🚌 [NYC School Bus Delay Prediction](https://github.com/abraraltaf92)
- Processed 1.2M+ NYC DOE incident records in Python for delay regression + severity classification
- XGBoost models (R² 0.64; 96% classification accuracy) benchmarked against baselines

---

## 💼 Experience

- **Data Engineering Intern @ Affordable Charter (NYC)** — built end-to-end ETL pipelines (Python, SQL, Pandas) and automated dashboards with data-validation checks.
- **Software Engineer @ Samsung R&D India** — worked on production Samsung Galaxy systems, including AI-driven imaging features (multi-frame low-light processing) for flagship devices, within cross-functional engineering teams.
- **Founder — [Biblo](https://www.bibloapp.com)** — building a two-sided marketplace connecting readers with independent bookstores. 50+ waitlist signups from an in-person startup showcase at Pace University.
- **Founder — AIByte Hub** — independent practice delivering 20+ web and app projects for clients across healthcare, transportation, and logistics.
- **Author — _The Day I Met a Revolution_** — a book on artificial intelligence.

---

## 🔧 Tech Stack

**Languages:** Python · SQL · JavaScript/TypeScript · R
**Data Engineering:** ETL/ELT · dbt · Airflow · PySpark · Pandas · data modeling · data quality
**ML / AI:** PyTorch · TensorFlow · scikit-learn · XGBoost · CNNs/ViT · model ensembling
**Cloud & Infra:** AWS (EC2) · Docker · FastAPI · Git · Linux
**Databases:** PostgreSQL · MySQL · MongoDB · InfluxDB

---

## 📫 Connect

🔗 LinkedIn: [linkedin.com/in/abraraltaf92](https://www.linkedin.com/in/abraraltaf92)
🌐 Portfolio: [abraraltaflone.com](https://abraraltaflone.com)
📧 Email: abraraltaf92@gmail.com

Thanks for stopping by!
