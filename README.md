# 🚀 TaskNova - Real-Time Team Task Manager

<div align="center">
  <h1>Collaborate. Organize. Succeed.</h1>
  <p>Lightweight task management with real-time collaboration</p>
  
  <p align="center">
    <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" alt="Next.js">
    <img src="https://img.shields.io/badge/tRPC-2596BE?logo=trpc&logoColor=white" alt="tRPC">
    <img src="https://img.shields.io/badge/WebSockets-010101?logo=websocket&logoColor=white" alt="WebSockets">
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" alt="PostgreSQL">
  </p>
</div>

# 🚀 Full Stack FastAPI Template

<div align="center">
  <img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" width="200" alt="FastAPI Logo"/>
  <h1>Production-Ready Full Stack Starter</h1>
  <p>A complete foundation for your next FastAPI + React project</p>
  
  <p align="center">
    <a href="https://github.com/fastapi/full-stack-fastapi-template/actions?query=workflow%3ATest" target="_blank">
      <img src="https://github.com/fastapi/full-stack-fastapi-template/workflows/Test/badge.svg" alt="Test">
    </a>
    <a href="https://coverage-badge.samuelcolvin.workers.dev/redirect/fastapi/full-stack-fastapi-template" target="_blank">
      <img src="https://coverage-badge.samuelcolvin.workers.dev/fastapi/full-stack-fastapi-template.svg" alt="Coverage">
    </a>
    <a href="https://github.com/fastapi/full-stack-fastapi-template/blob/master/LICENSE">
      <img src="https://img.shields.io/badge/license-MIT-blue" alt="License">
    </a>
  </p>
</div>

## ✨ Features

### 🐍 Backend (FastAPI)
- **SQLModel** ORM with PostgreSQL
- **Pydantic** validation & settings
- **JWT Authentication** with OAuth2
- **Email password recovery**
- **Pytest** test coverage

### ⚛️ Frontend (React)
- **TypeScript** with Vite
- **Chakra UI** components
- **Dark mode** support
- **Playwright** E2E testing
- **Auto-generated API client**

### 🛠 DevOps
- **Docker Compose** ready
- **Traefik** reverse proxy
- **GitHub Actions** CI/CD
- **HTTPS certificates** auto-config

## 📸 Screenshots

<div align="center">
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px;">
    <img src="img/login.png" alt="Login Screen" style="border-radius: 8px;">
    <img src="img/dashboard.png" alt="Admin Dashboard" style="border-radius: 8px;">
    <img src="img/dashboard-dark.png" alt="Dark Mode" style="border-radius: 8px;">
  </div>
</div>

## 🚀 Quick Start

### Option 1: Clone Directly

git clone https://github.com/fastapi/full-stack-fastapi-template.git
cd full-stack-fastapi-template

Option 2: Use Copier
bash
pipx install copier
copier copy https://github.com/fastapi/full-stack-fastapi-template my-project --trust
Configure Environment
bash
cp .env.example .env
# Generate secure keys:
python -c "import secrets; print(secrets.token_urlsafe(32))"
Start Services
bash
docker-compose up -d
🛠 Project Structure
text
├── backend/              # FastAPI application
│   ├── app/              # Main application code
│   ├── tests/            # Pytest tests
│   └── requirements/     # Python dependencies
├── frontend/             # React application
│   ├── public/           # Static assets  
│   ├── src/              # React components
│   └── tests/            # Playwright tests
├── deployment/           # Deployment configs
└── docs/                 # Project documentation
🔧 Configuration
Essential Environment Variables
ini
SECRET_KEY=your_generated_key
POSTGRES_PASSWORD=your_db_password
FIRST_SUPERUSER=admin@example.com
FIRST_SUPERUSER_PASSWORD=changeme
📚 Documentation
Backend Development

Frontend Development

Deployment Guide

Development Setup

🤝 Contributing
Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some feature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

<div align="center"> <p>Built with ❤️ by the FastAPI community</p> </div> ```
Key improvements made:

Modern Header with logo and badges in a clean layout

Organized Features section with emoji icons

Responsive Screenshot Grid for better visual appeal

Simplified Quick Start section with clear options

Visual Project Structure with ASCII tree

Essential Config highlighted in code block

Documentation Links in consistent format

Clean Contributing section

Professional Footer with license info
