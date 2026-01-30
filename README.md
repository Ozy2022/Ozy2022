# 👋 Hi, I'm Osama Ahmed

<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=36BCF7FF&center=true&vCenter=true&width=600&lines=Full+Stack+Developer;AI+%2F+Machine+Learning+Engineer;Data+Analyst;Bioinformatics+Enthusiast;Building+Epigenetic+AI+Solutions)

</div>

---

## 🧬 Featured Project: EpiNova Lab Portal

<div align="center">

### 🔬 AI-Powered Breast Cancer Detection Platform

*Pioneering epigenetic research through machine learning and DNA methylation analysis*

[![Status](https://img.shields.io/badge/Status-MVP%20Phase-brightgreen?style=for-the-badge&logo=rocket&logoColor=white)](https://github.com)
[![Built With](https://img.shields.io/badge/Built%20With-XGBoost%20AI-blue?style=for-the-badge&logo=python&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge&logo=lock&logoColor=white)](https://github.com)

</div>

---

### 🤖 AI/ML Tasks Completed

| Phase | Task | Status |
|:------|:-----|:------:|
| **Data Preparation** | Loaded & transposed methylation dataset (71 patients, 595K+ CpG sites) | ✅ |
| **Preprocessing** | Implemented median imputation + StandardScaler pipeline | ✅ |
| **Feature Selection** | ANOVA F-test to select top 100,000 discriminative CpG sites | ✅ |
| **Model Training** | Trained XGBoost binary classifier with 5-Fold Stratified CV | ✅ |
| **Hyperparameter Tuning** | Optimized learning rate, max_depth, n_estimators | ✅ |
| **Model Evaluation** | Achieved AUC ≥ 0.88, Accuracy ≥ 80% | ✅ |
| **Biomarker Extraction** | Identified significant CpG biomarkers (feature importance > 0) | ✅ |
| **Model Artifacts** | Saved model, imputer, scaler, selected features as `.pkl` files | ✅ |
| **Backend Integration** | Flask API endpoints for model inference | ✅ |
| **Frontend Integration** | React UI for predictions and report visualization | ✅ |

---

## 🎯 Project Overview

**EpiNova Lab Portal** is a comprehensive web application designed for **breast cancer detection** using advanced machine learning models trained on **DNA methylation data**. The platform enables researchers and clinicians to:

- 📤 Upload patient methylation samples (CSV/Excel)
- 🤖 Run AI-driven predictions using our proprietary **EpiNova AI** models
- 📊 Visualize detailed epigenetic analysis reports
- 📈 Track and manage samples through an intuitive dashboard

---

## 🔄 Prediction Flow Architecture

```mermaid
flowchart LR
    A[📤 Upload CSV] --> B[🔍 Data Validation]
    B --> C[⚙️ Preprocessing]
    C --> D{🧠 Model Selection}
    D --> E[100K Feature Model]
    D --> F[Full Feature Model]
    D --> G[Refined Model]
    E --> H[📊 Feature Alignment]
    F --> H
    G --> H
    H --> I[🧪 Imputation & Scaling]
    I --> J[🎯 XGBoost Prediction]
    J --> K[📈 Risk Assessment]
    K --> L[🔒 Database Storage]
    L --> M[📋 Report Generation]
```

### Pipeline Steps:
1. **Data Upload** → CSV/Excel with CpG methylation Beta values (0-1 scale)
2. **Validation** → Format verification and feature count check
3. **Preprocessing** → Missing value imputation (median) + StandardScaler normalization
4. **Feature Alignment** → Matches input data with model's expected ~597,000 CpG sites
5. **Model Prediction** → XGBoost binary classification
6. **Risk Assessment** → Generates confidence scores and risk levels (Low/Medium/High)
7. **Report Generation** → Interactive visualization with top predictive markers

---

## 🛠️ Technology Stack

<div align="center">

| Category | Technologies |
|:--------:|:-------------|
| **Frontend** | ![React](https://img.shields.io/badge/React%2018-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite%206-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **UI Components** | ![Radix](https://img.shields.io/badge/Radix%20UI-161618?style=flat-square&logo=radixui&logoColor=white) ![Shadcn](https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcnui&logoColor=white) ![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square&logo=chart.js&logoColor=white) ![Lucide](https://img.shields.io/badge/Lucide%20Icons-F56040?style=flat-square&logo=lucide&logoColor=white) |
| **Backend** | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Python](https://img.shields.io/badge/Python%203.11-3776AB?style=flat-square&logo=python&logoColor=white) ![JWT](https://img.shields.io/badge/JWT%20Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| **AI/ML** | ![XGBoost](https://img.shields.io/badge/XGBoost-EC4E20?style=flat-square&logo=xgboost&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **Database** | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

</div>

---

## ✅ What We've Achieved

<div align="center">

### 🏆 Project Milestones Completed

</div>

#### 🧠 Machine Learning & AI
| Achievement | Details |
|:------------|:--------|
| ✅ **Trained 3 XGBoost Models** | 100K features, Full (~590K CpGs), and Refined marker models |
| ✅ **Achieved ~89% AUC Score** | High-performing breast cancer detection from methylation data |
| ✅ **Feature Engineering Pipeline** | ANOVA F-test feature selection on 597,000+ CpG sites |
| ✅ **Cross-Validation** | 5-Fold Stratified CV with hyperparameter tuning |
| ✅ **Complete Preprocessing** | Median imputation + StandardScaler normalization |
| ✅ **Model Serialization** | Saved models, imputers, scalers, and feature lists (`.pkl` files) |

#### 🖥️ Full-Stack Web Application
| Achievement | Details |
|:------------|:--------|
| ✅ **React 18 Frontend** | Modern TypeScript-based UI with Vite 6 |
| ✅ **Flask REST API** | Complete backend with 15+ API endpoints |
| ✅ **JWT Authentication** | Secure login/logout with token-based auth |
| ✅ **SQLite Database** | Users, Samples, and Reports tables with relationships |
| ✅ **Real-time Updates** | DataSyncContext with 15-second polling |
| ✅ **58+ UI Components** | Shadcn/ui + Radix primitives for premium design |

#### 📊 Dashboard & Analytics
| Achievement | Details |
|:------------|:--------|
| ✅ **Dashboard Overview** | Live stats: Total Samples, Completed Today, Processing, Pending |
| ✅ **Sample Management** | Upload, track status, view history |
| ✅ **Interactive Reports** | Detailed epigenetic analysis with top CpG markers |
| ✅ **Analytics Charts** | Recharts visualizations for data insights |
| ✅ **Settings Page** | User profile, team management, API keys, notifications |

#### 🎨 UI/UX Design
| Achievement | Details |
|:------------|:--------|
| ✅ **Premium Dark Theme** | Modern glassmorphism aesthetic |
| ✅ **Micro-Animations** | Smooth transitions and loading states |
| ✅ **Responsive Design** | Works on desktop and tablet |
| ✅ **Drag-and-Drop Upload** | CSV/Excel file upload with validation |
| ✅ **Real-time Processing View** | Live progress tracking during predictions |

#### 🔧 DevOps & Infrastructure
| Achievement | Details |
|:------------|:--------|
| ✅ **Docker Support** | Containerized backend deployment |
| ✅ **Environment Configuration** | Secure `.env` management |
| ✅ **CORS Configuration** | Proper cross-origin request handling |
| ✅ **Firebase Setup** | Initial Firestore structure and security rules |
| ✅ **Git Version Control** | Complete project history |

---

## 🗃️ Database Schema

```mermaid
erDiagram
    USERS ||--o{ SAMPLES : creates
    SAMPLES ||--o| REPORTS : generates
    
    USERS {
        int id PK
        string name
        string email UK
        string password
        string role
    }
    
    SAMPLES {
        string id PK
        int user_id FK
        string patient_id
        string status
        string risk_level
        float confidence
        string model_id
        timestamp created_at
        timestamp completed_at
    }
    
    REPORTS {
        int id PK
        string sample_id FK
        json prediction_result
        timestamp created_at
    }
```

---

## 🖥️ UI Features

<div align="center">

| Feature | Description |
|:-------:|:------------|
| 🏠 **Dashboard** | Real-time stats, pending/processing/completed samples overview |
| 📤 **Sample Upload** | Drag-and-drop CSV/Excel with validation |
| 🔄 **Processing View** | Live progress tracking with micro-animations |
| 📊 **Analytics** | Interactive charts with Recharts visualizations |
| 📋 **Reports** | Detailed epigenetic analysis with top CpG markers |
| 🌙 **Dark Mode** | Premium dark theme UI |
| 🔐 **Authentication** | JWT-based secure login system |
| ⚡ **Real-time Sync** | Auto-refresh every 15 seconds |

</div>

---

## 📊 ML Model Performance

| Model | Features | AUC Score | Target Accuracy |
|:------|:--------:|:---------:|:---------------:|
| **100K Feature Model** | 100,000 CpG sites | ~0.89 | ≥80% |
| **Full Feature Model** | ~590,000 CpGs | ~0.88 | ≥80% |
| **Refined Model** | Optimized markers | ~0.87 | ≥80% |

---

## 💡 Skills Demonstrated

<div align="center">

### Technical Expertise

| Domain | Skills |
|:------:|:-------|
| 🎨 **Frontend** | React Hooks, Context API, TypeScript, Responsive Design, Component Architecture |
| ⚙️ **Backend** | REST API Design, JWT Authentication, Database Design, CORS Configuration |
| 🤖 **AI/ML** | Feature Engineering, Model Training, Cross-Validation, Hyperparameter Tuning |
| 🧬 **Bioinformatics** | DNA Methylation Analysis, CpG Site Processing, Epigenetic Biomarkers |
| 🏗️ **Architecture** | Full-Stack Development, MVC Pattern, Real-time Data Sync |
| 🔧 **DevOps** | Docker, Environment Management, Database Migrations |

</div>

---

## 🚧 Current Enhancements (In Progress)

> **Note:** This project is currently an **MVP (Minimum Viable Product)** designed to demonstrate capabilities to investors. After initial investor feedback, cloud services will be fully integrated.

### 🔥 Firebase Integration
- [ ] Firebase Authentication (replacing JWT)
- [ ] Firestore database migration
- [ ] Firebase Storage for sample files
- [ ] Real-time listeners replacing polling

### 🐘 PostgreSQL Migration
- [ ] Moving from SQLite to PostgreSQL for production scalability
- [ ] Database migration scripts
- [ ] Connection pooling implementation

### ☁️ Future Cloud Services (Post-MVP)
- [ ] AWS/GCP deployment
- [ ] Auto-scaling infrastructure
- [ ] Load balancing
- [ ] CDN for static assets
- [ ] Serverless functions for predictions

---

## 📊 Other Project: Data Analyst Portfolio

<div align="center">

### 📈 COVID-19 Data Analysis Project

*End-to-end data analysis using SQL, Tableau, and Python*

[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=for-the-badge&logo=clockify&logoColor=white)](https://github.com)
[![Current Phase](https://img.shields.io/badge/Current-Part%202-blue?style=for-the-badge&logo=tableau&logoColor=white)](https://github.com)

</div>

| Part | Topic | Technologies | Status |
|:----:|:------|:-------------|:------:|
| **1** | SQL Data Exploration | ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) | ✅ Completed |
| **2** | Tableau Visualization | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) | 🔄 In Progress |
| **3** | Data Cleaning in SQL | ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) | ⏳ Upcoming |
| **4** | Correlation in Python | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | ⏳ Upcoming |

### Skills Being Developed:
- **SQL**: Data extraction, joins, aggregations, CTEs, window functions
- **Tableau**: Interactive dashboards, data storytelling, visual analytics
- **Python**: Pandas, correlation analysis, data visualization with Matplotlib/Seaborn

---

## 🚀 Roadmap

```mermaid
timeline
    title EpiNova Development Roadmap
    
    section MVP Phase (Current)
      Core Features : Dashboard, Sample Upload, Predictions
      ML Models : 100K, Full Feature, Refined models
      Local Database : SQLite implementation
    
    section Enhancement Phase
      Firebase : Auth, Firestore, Storage
      PostgreSQL : Production database
      Performance : Optimization & caching
    
    section Cloud Phase
      Deployment : AWS/GCP infrastructure
      Scaling : Auto-scaling, load balancing
      Enterprise : Multi-tenant architecture
```

---

## 📫 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/osama-albaydhani-04a31b227/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ozy2022)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:business.os.2026@gmail.com)

</div>

---

<div align="center">

### 💼 Open for Opportunities

*Interested in AI, Data Analysis and Software Development*

---

![Profile Views](https://komarev.com/ghpvc/?username=Ozy2022&style=flat-square&color=36BCF7FF)

*⭐ If you find my work interesting, please consider starring my repositories!*

</div>
