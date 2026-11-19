# Abrar Altaf Lone

Software and data engineer in New York, with an M.S. in Data Science from **Pace University** (2026).
I build data pipelines, ML systems and full-stack products end to end, and I care most about
getting them to work in production.

**Right now:** AI Research Analyst at Workada, contract software engineer on AI training projects
with Mercor, and building [Biblo](https://www.bibloapp.com) and [Kharchi Parchi](https://kharchiparchi.com).

[Portfolio](https://abraraltaflone.com) · [LinkedIn](https://www.linkedin.com/in/abraraltaf92) · [Email](mailto:abraraltaf92@gmail.com)

---

## Featured projects

### [Deepfake Detection System](https://github.com/abraraltaf92/deepfake-detection) · [live demo](https://deepfakedetection.xyz)
A multi-model deepfake detection service, built as a four-person capstone and deployed.
- Five-model ensemble (ResNet-18, EfficientNet-B4, R3D-18, ViT-B/16, R3D-18 + RAFT) with calibrated soft voting; shrinks the cross-dataset generalization gap by 26.9% over the ResNet-18 baseline (FaceForensics++ → Celeb-DF v2, ensemble AUC 0.885)
- FastAPI backend on AWS EC2 (GPU, Docker), Next.js frontend, model weights versioned on Hugging Face Hub
- Includes a documented negative result: a frequency-domain detector that learned codec artifacts rather than forgery signals, and was left out of production

### [Biblo Data Pipeline](https://github.com/abraraltaf92/biblo-data-pipeline)
The data backend for Biblo. It answers "which independent bookstore near me carries this book?"
- Multi-source ingestion (OpenStreetMap, Open Library) into a PostgreSQL warehouse
- Modeled with dbt into a star schema (`dim_bookstore`, `dim_book`, `fact_inventory`) with 16 data-quality tests
- Orchestrated with Airflow and fully containerized with Docker; idempotent and re-runnable

### [Mechanify](https://github.com/abraraltaf92/mechanify)
A macOS menu-bar app, written in Swift, that plays a mechanical-keyboard click for every key press in any app.
- Sounds cut from real switch recordings, placed in stereo by key position and played with minimal delay
- Private by design: it never reads, stores or sends what is typed

### [NYC School Bus Delay Prediction](https://github.com/abraraltaf92/nyc-school-bus-delay-prediction)
- Processed 1.2M+ NYC DOE incident records for delay regression and severity classification
- XGBoost models (R² 0.64; 96% classification accuracy) benchmarked against baselines

### [Kharchi Parchi](https://kharchiparchi.com)
A GST billing platform for small shops in India, built at Aibyte Hub.
- A React Native app and a Next.js web app on one shared TypeScript billing engine, with Supabase
- Prints receipts on Bluetooth thermal printers; each business gets its own workspace and branding

**More:** [Multimodal Sentiment Analysis (MVSA)](https://github.com/abraraltaf92/multimodal-sentiment-analysis-mvsa) ·
[Airbnb Pricing Dynamics in NYC](https://github.com/abraraltaf92/analyzing-airbnb-pricing-dynamics-in-newyork-city) ·
[Whatsdule](https://github.com/abraraltaf92/whatsdule)

---

## Experience

- **AI Research Analyst, Workada** (Nov 2026 – present). Design and run evaluations of AI coding models: build realistic software tasks, grade model output against ground truth, and write up where and why models fail.
- **Software Engineer, AI Training (contract), Mercor** (Sep 2026 – present). Write coding tasks, reference solutions and tests used to train and evaluate AI models, and review other engineers' submissions.
- **Data Engineering Intern, Affordable Charter LLC** (Sep – Dec 2025, Paterson, NJ). Built end-to-end data pipelines in Python and SQL, with automated dashboards and data-validation checks.
- **Founder, [Biblo](https://www.bibloapp.com)** (Oct 2024 – present). A platform connecting readers with independent bookstores. 50+ waitlist sign-ups from an in-person startup showcase at Pace University; now building the mobile app in React Native on Supabase.
- **Founder, Aibyte Hub** (2021 – present). Delivered 20+ web, app and IT projects for clients, mostly pharmacies and healthcare businesses, and built Kharchi Parchi.
- **Software Engineer, Samsung R&D Institute India** (Jan 2022 – Dec 2023). Built network software (4G Layer-3 and RRC call stack, eNodeB, early 6G work), then moved to computer vision and camera systems for Samsung AI features.
- **Author, _The Day I Met a Revolution_** (2023). A book on how artificial intelligence is changing the way people think, build and work.

---

## Tech stack

**Languages:** Python · SQL · TypeScript/JavaScript · C++ · Swift · Dart
**Data engineering:** ETL/ELT · dbt · Airflow · PySpark · Pandas · data modeling · data quality
**ML / AI:** PyTorch · TensorFlow · scikit-learn · XGBoost · CNNs/ViT · model ensembling
**Web and mobile:** Next.js · React Native (Expo) · FastAPI · Flutter · Supabase
**Cloud and infra:** AWS (EC2) · Docker · Git · Linux
**Databases:** PostgreSQL · MySQL · MongoDB · InfluxDB
