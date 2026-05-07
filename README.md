# CareerSaathi

CareerSaathi is an AI-powered career preparation and interview simulation platform designed to help students, freshers, and professionals improve their interview performance through realistic mock interviews, intelligent feedback systems, analytics, and adaptive questioning.

The platform combines modern frontend technologies with AI-driven backend services to create an interactive and scalable interview preparation ecosystem. CareerSaathi aims to bridge the gap between academic learning and real-world interview expectations by providing role-specific, experience-based, and adaptive interview experiences.

Organization Link: https://github.com/CareerSaathi-Project

---

# Vision

CareerSaathi is built with the goal of making high-quality interview preparation accessible, intelligent, and personalized. Traditional mock interview systems are static and repetitive. CareerSaathi introduces adaptive AI-generated questions, detailed performance analysis, and professional feedback mechanisms to simulate realistic interview environments.

The platform focuses on:

- Realistic AI-generated interview experiences
- Technical and role-specific questioning
- Adaptive difficulty progression
- Detailed feedback and scoring
- Interview analytics and performance tracking
- Scalable architecture for future expansion
- Modern responsive user interface
- Secure authentication and backend architecture

---

# Core Features

## AI-Powered Adaptive Interviews
- Dynamic question generation using AI models
- Technical and domain-specific interviews
- Experience-based question difficulty
- Controlled interview length
- Multiple interview roles and domains

## Intelligent Feedback System
- AI-generated detailed answer evaluation
- Harsh, balanced, and encouraging feedback modes
- Verbal analysis and verdict generation
- Overall scoring system

## Analytics Dashboard
- Interview history tracking
- Score breakdowns
- Performance trends
- Role-based analytics
- Question-level feedback analysis

## Authentication System
- Secure JWT-based authentication
- Login and registration support
- Protected interview routes

## Modern Frontend Experience
- Responsive UI
- Smooth animations using Framer Motion
- Dashboard-driven workflow
- Real-time interview interaction

---

# Technology Stack

## Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- ShadCN UI
- React Query
- Framer Motion

## Backend
- FastAPI
- Python
- SQLAlchemy
- JWT Authentication
- Hugging Face Inference API
- PostgreSQL
- Pydantic

## Deployment
- Frontend: Vercel
- Backend: Render

---

# Repositories

## Frontend Repository
https://github.com/CareerSaathi-Project/CareerSathi_frontend

## Backend Repository
https://github.com/CareerSaathi-Project/backendCareerSathi

---

# Frontend Overview

The frontend is responsible for:
- User authentication
- Dashboard and analytics visualization
- AI interview interface
- History management
- API integration with backend services
- Responsive and interactive user experience

---

# Frontend Project Structure

```bash
CareerSathi_frontend/
│
├── client/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── hooks/
│       ├── lib/
│       ├── pages/
│       ├── App.tsx
│       ├── main.tsx
│       └── index.css
│
├── shared/
├── package.json
├── vite.config.ts
├── tailwind.config.ts
├── tsconfig.json
├── postcss.config.js
└── vercel.json

# Backend Project Structure

```bash
backendCareerSathi/
│
├── app/
│   ├── api/
│   │   ├── routes/
│   │   ├── services/
│   │   └── schemas.py
│   │
│   ├── auth/
│   ├── db/
│   ├── utils/
│   └── main.py
│
├── requirements.txt
└── render.yaml

---

# Frontend Setup

## 1. Clone Frontend Repository

```bash
git clone https://github.com/CareerSaathi-Project/CareerSathi_frontend.git
```

---

## 2. Navigate to Frontend Directory

```bash
cd CareerSathi_frontend
```

---

## 3. Install Dependencies

```bash
npm install
```

---

## 4. Configure Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_BASE_URL=https://your-backend-url.onrender.com
```

Replace the backend URL with your deployed backend API URL.

---

## 5. Run Frontend Locally

```bash
npm run dev
```

The frontend development server will start locally.

---

## 6. Build Frontend for Production

```bash
npm run build
```

---

# Frontend Deployment (Vercel)

## Recommended Configuration

### Framework Preset
```text
Vite
```

### Build Command
```bash
npm run build
```

### Output Directory
```text
dist
```

### Install Command
```bash
npm install
```

---

# Backend Setup

## 1. Clone Backend Repository

```bash
git clone https://github.com/CareerSaathi-Project/backendCareerSathi.git
```

---

## 2. Navigate to Backend Directory

```bash
cd backendCareerSathi
```

---

## 3. Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5. Configure Environment Variables

Create a `.env` file:

```env
DATABASE_URL=your_database_url
SECRET_KEY=your_secret_key
HF_API_TOKEN=your_huggingface_token
HF_MODEL=Qwen/Qwen2.5-7B-Instruct
```

---

## 6. Run Backend Locally

```bash
uvicorn app.main:app --reload
```

The backend API server will start locally.

---

# Backend Deployment (Render)

## Recommended Configuration

### Build Command

```bash
pip install -r requirements.txt
```

### Start Command

```bash
uvicorn app.main:app --host 0.0.0.0 --port $PORT
```

### Root Directory

Leave empty if backend files are in repository root.

---

# Contribution Guidelines

We welcome developers, designers, AI engineers, and contributors interested in improving CareerSaathi.

## Steps to Contribute

### 1. Fork the Repository

Fork the required repository from the CareerSaathi organization.

---

### 2. Create a Feature Branch

```bash
git checkout -b feature-name
```

---

### 3. Commit Changes

```bash
git commit -m "Added new feature"
```

---

### 4. Push Changes

```bash
git push origin feature-name
```

---

### 5. Create Pull Request

Open a pull request describing your changes clearly.

---

# Future Scope

CareerSaathi is designed to evolve into a complete AI-driven career preparation ecosystem. Planned future enhancements include:

- Voice-based AI mock interviews
- Video interview simulations
- Resume analysis and ATS scoring
- AI-generated improvement roadmaps
- Company-specific interview preparation
- Real-time coding interview environments
- Behavioral interview intelligence
- AI mentor and career guidance assistant
- Multi-language interview support
- Team and panel interview simulations
- Recruiter-side evaluation dashboards
- Placement preparation modules
- Advanced analytics and progress tracking
- Personalized learning recommendations
- Peer-to-peer mock interview system
- AI-powered resume builder
- Integrated job recommendation system

---

# Open Source Collaboration

CareerSaathi is actively evolving, and community contributions are encouraged. Contributors can help in areas such as:

- Frontend development
- Backend optimization
- AI prompt engineering
- UI/UX improvements
- Security enhancements
- Documentation
- Testing and debugging
- Deployment optimization
- Performance improvements
- Accessibility enhancements
- API scalability
- Database optimization

---

# License

This project is currently intended for educational, research, and development purposes.

A dedicated open-source license may be added in future releases depending on project distribution and collaboration requirements.

---

# Maintainers

CareerSaathi Organization

https://github.com/CareerSaathi-Project
