AimRoute — AI Career Guidance Platform

Helping students discover the right career path based on their interests and marks.
      KIIT University · Final Year Project · 2024–25


What is AimRoute?
AimRoute is an AI-powered career guidance platform for students after 10th, 12th, Graduation, and Post-Graduation. It asks a series of questions and recommends the top 5 careers that best fit the student — along with college suggestions, exam eligibility, and a roadmap.


Tech Stack :
Frontend — React + Vite
Backend — FastAPI (Python)
Database — MySQL
Auth — JWT + bcrypt
ML — scikit-learn (rule-based career matching)
College Data — NIRF 2024 (6,554 colleges)



Key Features:
🎯 AI career matching with fit labels (Excellent / Good / Aspirational)
📝 Branching quiz — 4 levels (10th, 12th, Grad, PG)
🏫 College suggestions from 6,554 NIRF-ranked colleges
📊 Personal dashboard with quiz history + PDF/CSV export
🔐 JWT authentication with forgot password via email
📋 Exam eligibility checker (JEE, NEET, CAT, GATE, UPSC + 15 more)
⚖️ Career comparison tool — compare any two careers side by side
🗺️ 5-step career roadmap for every recommendation


Run Locally

Backend :
bashcd backend
pip install -r requirements.txt
uvicorn app.main:app --reload

Frontend :
bashcd frontend
npm install
npm run dev
