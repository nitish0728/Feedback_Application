📝 Feedback App
A full-stack feedback collection application built with React (Vite) for frontend, Express.js for backend, and PostgreSQL for database. The app allows users to submit feedback, which is stored in a database and displayed dynamically.

🚀 Features
Collects feedback with name, email, and message
Instantly displays submitted feedback
Responsive UI with React
Backend API using Express.js
Database management with PostgreSQL
Fully deployed using Vercel
🛠️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/feedback-app.git
cd feedback-app
2️⃣ Backend Setup
Navigate to the backend folder:
cd backend
Install dependencies:
npm install
Create a .env file in the backend directory and add:
DATABASE_URL=your_postgresql_connection_url
Start the backend server:
npm run dev
Backend will run on: http://localhost:5000
3️⃣ Frontend Setup
Navigate to the frontend folder:
cd ../frontend
Install dependencies:
npm install
Update API_URL in src/App.js to use your deployed backend:
const API_URL = "https://your-backend-url.vercel.app/feedback";
Start the frontend:
npm run dev
Frontend will run on: http://localhost:5173
🌍 Deployed Links
Frontend: https://feedback-frontend-ilos491r7-rasheednadaf4-gmailcoms-projects.vercel.app
Backend: https://feedback-app-backend-bczgvcz3d-rasheednadaf4-gmailcoms-projects.vercel.app
