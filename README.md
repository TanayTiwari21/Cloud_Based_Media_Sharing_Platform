📸 Cloud-Based Media Sharing Platform

A Cloud-Based Media Sharing Platform built using Python, FastAPI, and Streamlit, enabling users to securely register, authenticate, and upload images through an interactive frontend with a scalable backend architecture.

The application is containerized using Docker and deployed on AWS, making it production-ready and suitable for real-world use cases.

🌐 Live Demo

🔗 Streamlit Frontend:
http://43.205.137.152:8501/

🔗 API Documentation (Swagger):
http://43.205.137.152:8000/docs

🚀 Features

🔐 User registration and authentication

🖼 Secure image upload and management

🎨 Interactive Streamlit frontend

⚡ High-performance REST APIs using FastAPI

🐳 Dockerized backend for consistent deployment

☁️ Deployed on AWS (EC2)

🗄 Database integration for users and media metadata

✅ Request & response validation using Pydantic

📑 Auto-generated API documentation (Swagger UI)

🔒 Environment variable security using .env and .gitignore

🛠 Tech Stack
Category	Technology
Backend	Python, FastAPI
Frontend	Streamlit
Database	SQL Database (SQLAlchemy)
Containerization	Docker
Cloud	AWS EC2
Validation	Pydantic
API Docs	Swagger UI / OpenAPI
Version Control	Git & GitHub
📂 Project Structure
.
├── main.py        # FastAPI application entry point
├── app.py         # FastAPI app initialization
├── db.py          # Database connection & setup
├── users.py       # User authentication routes
├── images.py      # Image upload & media handling
├── schemas.py     # Pydantic data schemas
├── frontend.py    # Streamlit frontend logic
├── Dockerfile     # Docker configuration
├── .gitignore     # Environment & sensitive file protection

⚙️ Installation & Setup (Local)
1️⃣ Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2️⃣ Create Virtual Environment
python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run Backend
uvicorn main:app --reload

5️⃣ Run Streamlit Frontend
streamlit run frontend.py

🐳 Docker Setup
Build Docker Image
docker build -t media-sharing-app .

Run Docker Container
docker run -d -p 8000:8000 media-sharing-app

☁️ AWS Deployment Flow

Containerized FastAPI application using Docker

Launched AWS EC2 instance

Installed Docker on EC2

Deployed Docker container

Configured security groups for ports 8000 (API) and 8501 (Streamlit)

Accessed application via public IP

🔌 API Endpoints Overview
👤 User APIs

POST /register – Register a new user

POST /login – Authenticate user

🖼 Image APIs

POST /upload-image – Upload image

GET /images – Retrieve uploaded images

🎯 Use Cases

Cloud-based media sharing application

Backend + frontend demo for FastAPI & Streamlit

Learning project for REST APIs & Docker

AWS-deployed full-stack Python project

Portfolio project for Backend / ML / Data roles

🧠 What This Project Demonstrates

End-to-end system deployment (local → Docker → AWS)

Backend API development with FastAPI

Frontend integration using Streamlit

Authentication and database design

Clean, scalable code architecture

Real-world cloud deployment experience

📌 Future Enhancements

JWT-based authentication

Role-based access control

Image compression & optimization

AWS S3 for image storage

Nginx reverse proxy

CI/CD with GitHub Actions

HTTPS with SSL

Monitoring & logging

⭐ Why This Project Stands Out

Combines FastAPI + Streamlit + Docker + AWS

Fully deployed and publicly accessible

Production-ready backend architecture

Strong portfolio project for recruiters
