# Research Workflow Manager | Full-Stack Analytics Platform

## 🚀 Project Summary

Research Workflow Manager is a **full-stack research paper tracking and analytics platform** that helps users manage, track, and analyze their academic readings. It includes a dashboard with library management, progress stages, funnel charts, and timeline analytics — providing insights into reading habits and workflow progress.

---

## 📌 Features

- 📚 **Library Management**
  - Store and view research papers with metadata
  - Track reading progress across defined stages

- 📈 **Analytics Dashboard**
  - Reading funnel visualization
  - Papers over time trend chart
  - Insight into stages such as Abstract Read, Notes Completed, etc.

- 📝 **Add Paper Module**
  - Add new research entries via form input
  - Assign domain, status, citations, and impact levels

- ✨ **User Experience**
  - Responsive UI with sidebar navigation
  - Clear and intuitive workflow insights

---

## 🧠 Architecture Overview

[ User / Browser ]
↓
[ React Frontend ]
(Library, Add Paper, Analytics)
↓
[ Backend API (Node/Express) ]
(CRUD + Analytics computation)
↓
[ Data Store (In-memory / DB) ]

---

## 📊 Data Model (Example)

Paper {
id
title
author
domain
status
citationCount
impactLevel
createdAt
}

---

## 💻 Tech Stack

- **Frontend:** React (JavaScript, JSX)
- **Backend:** Express (Node.js)
- **Charts:** Chart.js or similar for visualization
- **Deployment:** Vercel / Railway / etc.

---

## 🛠️ Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/hustler0109/Research-Workflow-Manager.git
cd Research-Workflow-Manager
```
2. Install backend dependencies
```bash
cd backend
npm install
npm start
```
3. Install frontend dependencies
```bash
cd ../frontend
npm install
npm run dev
Open the frontend at http://localhost:5173 or the port shown in your terminal.
```

## 📦 Folder Structure

Research-Workflow-Manager/
├── backend/
│   ├── index.js
│   └── ...API logic
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   └── App.jsx
│   ├── package.json
│   └── vite.config.js
├── .gitignore
├── README.md
└── ...

## 📈 Analytics and Visualizations
Reading Funnel Chart: Shows breakdown of papers across progress stages

Papers Over Time: Line chart tracking additions or progress over time

These charts help visualize research priorities and identify bottlenecks.

## 🧠 Design Principles
Explicit state tracking of paper progress

Analytics-first views for awareness

Clear separation between frontend UI and backend logic


👤 Author
Shristy Joshi Thakur

Focused on building data-driven productivity tools, analytical dashboards, and user-friendly workflows.
