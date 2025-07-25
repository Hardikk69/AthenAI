# 🧠 AthenAI – Intelligent Academic Monitoring & Prediction System

AthenAI is a full-stack AI-powered platform that predicts and visualizes student academic performance. It features an automated ML pipeline, real-time insight dashboards, and role-based access for teachers, students, and admins.

## 🚀 Features

- 📊 Predict student performance and risk levels using ML
- 🔄 Auto-retrain pipeline with clean, transform, label, train steps
- 🖥️ Interactive React-based dashboard (student/teacher views)
- 🧠 FastAPI backend with PostgreSQL integration
- 🐳 Containerized architecture (Docker-ready)
- 🔐 JWT-based role authentication
- ⚙️ GitHub Actions CI/CD pipeline

## 🧱 Tech Stack

- **Frontend**: React + Vite + TailwindCSS
- **Backend**: FastAPI + Python (ML models)
- **Database**: PostgreSQL (hosted or local)
- **DevOps**: GitHub Actions, Docker, Render/Netlify

## 📂 Project Structure

```
athenai/
├── backend/        # FastAPI backend + ML pipeline
├── frontend/       # React + Tailwind dashboard
├── db/             # SQL seed/init scripts
├── .github/        # CI/CD workflows
└── docker-compose.yml
```

## 🛠️ Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/athenai.git
cd athenai
```

### 2. Run locally (dev)

#### Backend:
```bash
cd backend
uvicorn main:app --reload
```

#### Frontend:
```bash
cd frontend
npm install
npm run dev
```

### 3. Run with Docker
```bash
docker-compose up --build
```

## 🤖 ML Pipeline (Overview)

1. Load & clean academic data
2. Label students (pass/fail/risk)
3. Train classifier model (e.g., XGBoost)
4. Serve prediction via API
5. Auto-retrain on new data upload

## ✍️ Author

**Hardik Kansara**  
🔗 [knhardik.tech](https://knhardik.tech) | [GitHub](https://github.com/HardikKansara)

---