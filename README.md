# 1CD25MC085


# Campus Notification App (Frontend)

##  Overview
This project is a React-based frontend application built as part of the Campus Evaluation task. It fetches and displays notifications such as Events, Placements, and Results from a backend API with proper authentication and logging middleware.

---

## 🧩 Features

- 🔐 Token-based authentication
- 📡 API integration using reusable API wrapper
- 🪵 Logging middleware for request tracking
- 📊 Dynamic notification rendering
- 🎨 Clean and responsive UI
- ⚡ Loading and error handling states

---

## 🛠️ Tech Stack

- React (Vite)
- JavaScript (ES6+)
- Fetch API
- CSS (Inline styling)

---

## 📁 Project Structure


src/
├── api/
│ └── notifications.js
├── utils/
│ ├── apiWrapper.js
│ └── logger.js
├── App.jsx
├── main.jsx


---

## DEMO 

<img width="1272" height="767" alt="image" src="https://github.com/user-attachments/assets/554b05e5-2bc6-40ba-a9f3-5dd4d8eab9e9" />

<img width="1757" height="588" alt="image" src="https://github.com/user-attachments/assets/f8342c99-e370-4360-a8c0-2be77dc83a00" />

<img width="872" height="663" alt="image" src="https://github.com/user-attachments/assets/b2af50a9-7855-4778-9a30-b22f3a97790e" />


## ⚙️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
2. Install Dependencies
npm install
3. Run Development Server
npm run dev
🔐 Authentication Setup

Before running the project, store your token in browser localStorage:

localStorage.setItem("token", "YOUR_ACCESS_TOKEN");
📡 API Endpoints Used
GET /notifications – Fetch notifications list
POST /auth – Generate access token (evaluation system)

Base URL:

http://4.224.186.213/evaluation-service
🪵 Logging Middleware

A custom logging middleware is implemented to track:

API request start
Request payload
API response
Execution time
Error handling
\



The application displays notifications in a clean card-based UI grouped by:
Event and 
Placement
