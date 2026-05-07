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

---

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