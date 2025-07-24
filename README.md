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

## 🌟 Key Features

### 🏗️ Task Management
- **Real-time task updates** with WebSocket connections
- **Drag-and-drop** task organization
- **Multiple views** (Kanban, List, Calendar)
- **Task assignments** with team members

### 👥 Collaboration
- **Live presence indicators** showing who's online
- **Instant notifications** for task updates
- **Comment threads** on tasks
- **Mention teammates** with @ notifications

### 📊 Productivity
- **Due date reminders**
- **Progress tracking** with completion percentages
- **Custom labels & filters**
- **Activity history** for all changes

### ⚙️ Administration
- **Team management** with roles
- **Project templates**
- **Export/import** capabilities
- **API access** for integrations

## 🖥 Screenshots

<div align="center">
  <img src="screenshots/kanban-view.png" width="32%" alt="Kanban View"/>
  <img src="screenshots/task-detail.png" width="32%" alt="Task Detail"/> 
  <img src="screenshots/team-settings.png" width="32%" alt="Team Settings"/>
</div>

## 🛠 Tech Stack

### Frontend
- **Next.js 14** (App Router)
- **tRPC** for type-safe API calls
- **Tailwind CSS** with ShadCN components
- **React DnD** for drag-and-drop
- **Zod** for form validation

### Backend
- **Node.js** with Express
- **WebSockets** for real-time updates
- **Prisma** ORM
- **PostgreSQL** database
- **Redis** for pub/sub and caching

### Infrastructure
- **Docker** for containerization
- **GitHub Actions** CI/CD
- **Vercel** for frontend hosting
- **Railway** for backend services

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- PostgreSQL database
- Redis instance (for real-time features)

### Installation

# Clone repository
git clone https://github.com/yourusername/tasknova.git
cd tasknova

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env

Database Setup
bash
# Run database migrations
npx prisma migrate dev --name init

# Generate Prisma client
npx prisma generate
Running Locally
bash
# Start development server
npm run dev
📚 Documentation
API Reference

Real-Time Architecture

Deployment Guide

🤝 Contributing
We welcome contributions! Please see our Contribution Guidelines for details.

📜 License
TaskNova is MIT licensed.


<div align="center"> <p>Simplify teamwork with TaskNova</p> </div> ```
Key features of this README:

Modern Header with badges showing the core technologies

Organized Feature Sections with clear categorization

Visual Screenshots in a responsive grid layout

Detailed Tech Stack breakdown by frontend/backend/infra

Comprehensive Setup Instructions including prerequisites

Documentation Links for extended information

Professional Footer with license and contact info
