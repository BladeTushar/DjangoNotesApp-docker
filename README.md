A simple Notes Management Web Application built with Django, using MySQL as the database and Nginx as the reverse proxy. The project is fully containerized using Docker Compose for easy setup and deployment.

🚀 Tech Stack

Backend: Django (Python)

Database: MySQL

Web Server: Nginx

Containerization: Docker & Docker Compose
-----------------------------------------------------------
Structure

django-notes-app/
├── django-notes-app/          # Django project source code
├── nginx/                     # Nginx configuration folder
│   └── default.conf
├── Dockerfile                 # Django app Docker build file
├── docker-compose.yml         # Multi-container configuration
├── requirements.txt           # Python dependencies
└── .env                       # Environment variables


⚙️ Prerequisites

Make sure you have the following installed:

Docker

Docker Compose
-------------------------------------------------------------
🐳 How to Run the Project

Build and start all containers

docker compose up --build


Stop containers

docker compose down


Rebuild (if configs change)

docker compose up --build -d