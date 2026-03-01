<div align="center">

<img src="https://raw.githubusercontent.com/KyroTask/KyroTask/main/brand-logo/fox.png" width="100" height="100" alt="KyroTask Logo"/>

# KyroTask

**A premium productivity ecosystem built for Telegram**

---

[![Backend](https://img.shields.io/badge/Backend-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://github.com/KyroTask/internal)
[![Frontend](https://img.shields.io/badge/Frontend-Vue%203-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)](https://github.com/KyroTask/mini-app)
[![Platform](https://img.shields.io/badge/Platform-Telegram%20Mini%20App-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://telegram.org)

</div>

---

## 🦊 About KyroTask

KyroTask is a full-stack productivity platform and habit tracker that lives inside Telegram as a Mini App. It combines task management, goal tracking, habit building, and deep-work focus sessions in one seamless experience — optimized for both mobile and desktop.

---

## 📦 Repositories

| Repo | Description | Stack |
|------|-------------|-------|
| [**KyroTask**](https://github.com/KyroTask/KyroTask) | Main monorepo — root config, scripts, submodules | — |
| [**mini-app**](https://github.com/KyroTask/mini-app) | Telegram Mini App frontend | Vue 3 · Vite · Tailwind CSS · Pinia |
| [**internal**](https://github.com/KyroTask/internal) | REST API backend | Go · Gin · GORM · PostgreSQL |

---

## ✨ Features

- ✅ **Task Management** — Create, organize, and complete tasks with subtasks and comments
- 📁 **Projects & Milestones** — Group tasks with automated progress tracking
- 🎯 **Goal Tracking** — Set goals and measure progress over time
- 🔥 **Habit Tracker** — Build daily streaks and monitor consistency
- ⏱️ **Pomodoro Timer** — Deep focus sessions with automatic cycle tracking and XP leveling
- 📊 **Analytics Dashboard** — Visual insights on focus time, task completion, and habits
- 📅 **Calendar View** — Visualize tasks and deadlines by date
- 🔔 **Telegram Notifications** — Automated reminders and alerts via bot
- 🔐 **Secure Auth** — Telegram WebApp + Google OAuth authentication
- 📱 **Mobile First** — Premium UI optimized for Telegram mobile and desktop web

---

## 🛠 Tech Stack

### Frontend ([mini-app](https://github.com/KyroTask/mini-app))
`Vue 3` `Composition API` `Vite` `Tailwind CSS` `Pinia` `Vue Router` `Axios` `Telegram WebApp SDK`

### Backend ([internal](https://github.com/KyroTask/internal))
`Go` `Gin` `GORM` `PostgreSQL` `SQLite` `JWT` `WebSocket`

---

## 🚀 Getting Started

```bash
# Clone with all submodules
git clone --recurse-submodules https://github.com/KyroTask/KyroTask.git
cd KyroTask

# Install dependencies
npm install
go mod download
cd mini-app && npm install && cd ..

# Configure environment
cp .env.example .env

# Start development (backend + frontend)
npm run dev
```

> Backend runs on `http://localhost:3001` · Frontend on `http://localhost:5173`

---

## 📄 License

MIT © [KyroTask](https://github.com/KyroTask)
