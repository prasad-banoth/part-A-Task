# 🧩 Full-Stack Docker Assignment – PART-A

## 👤 Submitted by:
**Name:** Prasad Banoth 
**Branch:** `solutions-prasad
`  

---

## 📌 Objective

This assignment demonstrates the ability to containerize a full-stack web application and orchestrate services using **Docker Compose**. The application includes:

- 🌐 React Frontend
- ⚙️ FastAPI Backend
- 🛢️ PostgreSQL Database

All components are Dockerized and connected seamlessly, showcasing real-time communication between services and proper user authentication flow.

---

## 📁 Project Structure


assignment/
├── backend/ # FastAPI backend
│ └── Dockerfile
├── frontend/ # React frontend
│ └── Dockerfile
├── docker-compose.yml # Service orchestration
├── .env # Environment variables
└── README.md # Project documentation

🐳 Docker Setup
🚀 Run All Services
docker-compose up -d --build
✅ Expected Services

##########Service	Description	URL

Frontend	React App	http://localhost:3000
Backend	FastAPI App + Swagger	http://localhost:8000/docs
PostgreSQL	Database	Accessible via port 5432


🔐 Authentication Flow
Access the frontend in your browser: http://localhost:3000

Use the UI to Sign Up with email and password.

Then, Login with the same credentials.

On successful login, a success message is shown.

The backend handles logic and communicates with PostgreSQL to store user data.

You can verify API functionality via FastAPI Swagger docs: http://localhost:8000/docs.


