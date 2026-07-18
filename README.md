![header](https://capsule-render.vercel.app/api?type=waving&color=0:3B1F9E,100:8B5CF6&height=220&section=header&text=Nirav%20Sayanja&fontSize=50&fontAlignY=32&desc=ML%20Learner%20%E2%80%A2%20Web%20Developer%20%E2%80%A2%20Builder&descAlignY=52&fontColor=ffffff)

<div align="center">

🌍 **NIT Rourkela, India** · 🎯 **ML → production web apps** · 🔧 **React, Three.js, Supabase**

🛠️ opencode · hermes-agent · cursor · claude · ⚡ learn by shipping, iterate fast

💼 **Open for:** ML / full-stack internship opportunities

</div>

I build things that matter. Right now that means splitting my energy between **machine learning fundamentals** (linear regression → neural nets) and **modern full-stack web development** (React, TypeScript, Three.js, Supabase). My goal is to bridge the gap — ship ML-powered web apps end to end, from trained model to deployed product.

---

## 🚀 Featured Projects

---

### ⛓️ NexusFlow — Blockchain Payment Continuity

Blockchain-backed payment fallback system that monitors bank servers and automatically routes transactions through liquidity pools when banks go down. Three autonomous Python agents coordinate via Kafka for real-time failover.

```
├── 🏦 Real-time bank monitoring with 5-second polling
├── ⚡ Automatic payment routing: bank → blockchain fallback → debt recovery
├── 🧠 LangGraph-powered credit scoring with multi-factor pipeline
├── 📜 Solidity smart contracts (PoolFactory, LiquidityPool, LPERC20)
├── 🔌 React frontend with MetaMask wallet integration
└── 🐳 Docker Compose for full-stack orchestration
```

**Stack:** Python · Solidity · Kafka · Redis · LangGraph · React · TypeScript · Truffle

[![Nexusflow](https://img.shields.io/badge/Nexusflow-3B1F9E?style=for-the-badge&logo=ethereum&logoColor=white)](https://github.com/N-S8990/Nexusflow)

---

### 📡 Sentivo — Market Sentiment & Pulse Engine

Real-time sentiment analysis and signal generation engine. Aggregates Reddit, news, and market data into actionable Fear & Greed scores and trade signals via Apache Kafka.

```
├── 🧠 FinBERT ONNX for sub-100ms sentiment analysis
├── 📡 Kafka pipeline: producers → consumers → signals
├── 📊 Fear & Greed Index (sentiment 50% + momentum 30% + velocity 20%)
├── 🎯 Contrarian & trend-following signal strategies
├── 🐍 Python 3.11+ with Poetry
└── 🐳 Docker Compose for Kafka + Zookeeper
```

**Stack:** Python · Kafka · FinBERT · Docker · Pydantic · YAML Config

[![Sentivo](https://img.shields.io/badge/Sentivo-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/N-S8990/sentivo)

---

### 🛡️ FraudShield — Credit Card Fraud Detection

End-to-end ML system for detecting fraudulent credit card transactions. Three classifiers (Logistic Regression, Random Forest, XGBoost) with SMOTE for class imbalance, a FastAPI backend, and a live React dashboard.

```
├── 🤖 Three ML models with threshold-tuned predictions
├── 📊 SMOTE oversampling for 0.17% fraud class
├── ⚡ FastAPI REST API with /predict, /predict/batch, /models
├── 📈 React 19 + Recharts live dashboard
├── 🔬 MLflow experiment tracking
└── 📓 Jupyter notebooks for EDA & training
```

**Stack:** Python · Scikit-learn · XGBoost · FastAPI · React 19 · TypeScript · MLflow

[![FraudShield](https://img.shields.io/badge/FraudShield-FF4444?style=for-the-badge&logo=github&logoColor=white)](https://github.com/N-S8990/fraudshield)

---

### ✈️ UDAAN Aeromodelling Club — NIT Rourkela

The official website for NIT Rourkela's premier aeromodelling club. A production-grade platform for team induction, event registration, and member management.

```
├── 🎨 3D interactive hero powered by Three.js
├── 📝 Event registration with real-time Supabase backend
├── 🔐 Member authentication & role-based access control
├── ⚙️ Admin toggle panel for induction & registration windows
├── 📊 Excel/CSV export for applicant data management
├── 📱 Fully responsive across all device sizes
└── 🚀 Deployed on Vercel with CI/CD
```

**Stack:** React · TypeScript · Three.js · Supabase · Framer Motion · Vite · Firebase

[![Udaan Website](https://img.shields.io/badge/Udaan_Website-6C47F5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/N-S8990/Udaan-Website)

---

## 📈 Impact & Metrics

| Area | Metric | Value | Details |
|---|---|---|---|
| **Blockchain** | Failover latency | < 5s | Bank down → pool fallback in real time |
| **Blockchain** | Smart contracts | 4 | PoolFactory, LiquidityPool, LPERC20, StakingToken |
| **ML** | Fraud detection | 97.5% ROC-AUC | XGBoost with SMOTE + threshold tuning |
| **ML** | Sentiment latency | <100ms | FinBERT ONNX, batch of 32 |
| **3D** | Render performance | 60 FPS | Three.js hero scene optimized draw calls |
| **Streaming** | Throughput | 1000+ msg/min | Kafka pipeline across all topics |
| **Backend** | Query latency | < 100ms | Supabase real-time queries |
| **UX** | Breakpoints | 5 | Mobile-first responsive design |

---

## 🧠 ML Learning Roadmap

```
▓▓▓▓▓▓▓▓░░░░░░░░░░  Fundamentals    [██████████░░]  65% — supervised, ensembles, SMOTE, evaluation
▓▓▓▓▓░░░░░░░░░░░░░  Deep Learning   [██████░░░░░░]  35% — NLP, transformers, ONNX inference
▓▓▓░░░░░░░░░░░░░░░  Advanced        [███░░░░░░░░░]  15% — real-time pipelines, model optimization
```

**Built:** Classification (LR, RF, XGBoost), SMOTE, NLP sentiment (FinBERT), model serving APIs
**Next:** Training transformers from scratch, CNNs, deployment at scale

---

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit__learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🎵 Now Playing

<img src="https://spotify-github-profile.kittinanx.com/api/view?uid=wvz38vh081z2sa9w09dr3a5kc&cover_image=true&theme=spotify-embed&show_offline=false&background_color=121212&bar_color_cover=true" alt="Spotify" />

---

## 🎯 Current Focus

```
□  Master ML fundamentals — statistics, linear algebra, supervised learning
□  Build an ML-powered web app — model training → API → frontend integration
□  Contribute to open-source projects
□  Ship 2+ portfolio projects this year
□  Land an ML or full-stack internship
```

---

## 🤝 Connect

<p align="center">
  <a href="mailto:niravsayanja@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/N-S8990">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/niravsayanja">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/N-S8990/N-S8990">
    <img src="https://img.shields.io/badge/Portfolio-This_Profile-6C47F5?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>Learning in public. Building in public. Growing in public.</i>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=N-S8990&color=6C47F5&style=flat-square&label=Profile+Views" />
</p>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,100:3B1F9E&height=120&section=footer)
