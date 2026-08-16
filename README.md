# AMATI: Adaptive Learning Recommender System

AMATI is an adaptive learning recommender system designed for 7th-grade mathematics. It utilizes an AI-based Knowledge Tracing model to analyze student comprehension in real-time and recommends targeted learning materials to optimize their study path.

## Dashboard Preview

<img width="1881" height="911" alt="amati-bg" src="https://github.com/user-attachments/assets/a41001f7-400b-4e93-a4ce-140c70db2393" />

## Key Features

* **Dynamic Curriculum:** Automatically adjusts question difficulty based on individual student performance.
* **Knowledge Tracing Engine:** Tracks and identifies specific knowledge gaps across various sub-chapters.
* **AI-Powered Recommendation:** Serves the most relevant practice questions to improve specific learning outcomes.
* **Admin Dashboard:** Provides comprehensive data visualization for student progress tracking.

## Technology Stack

* **Frontend:** React, Vite, Tailwind CSS
* **Backend:** Node.js, Express, Prisma ORM
* **AI / Data Science:** Python, TensorFlow, FastAPI
* **Database:** PostgreSQL

## Getting Started

### Prerequisites
* Node.js (v16 or higher)
* Python (3.9 or higher)
* PostgreSQL

### Installation

1. Clone the repository.
2. Setup and run the backend:
```bash
cd backend
npm install
npx prisma migrate dev
npm run start
```

3. Setup and run the frontend:
```bash
cd frontend
npm install
npm run dev
```
