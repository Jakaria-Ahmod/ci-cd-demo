# 🚀 MERN CI/CD Demo Project

This is a **simple MERN Stack project** with **CI/CD workflow** using GitHub Actions.  
The goal of this project is to understand how **backend + frontend + CI/CD workflow** works together in a real-world setup.

---

## 🧩 Tech Stack

### 🔹 Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- REST API

### 🔹 Frontend
- React.js
- Vite
- Axios

### 🔹 CI/CD
- GitHub Actions
- Automated install & test on every push

---

## 📁 Project Structure

```text
ci-cd-demo/
├─ .github/
│  └─ workflows/
│     └─ node-ci.yml
├─ backend/
│  ├─ models/
│  │  └─ User.js
│  ├─ routes/
│  │  └─ user.js
│  ├─ index.js
│  ├─ package.json
│  └─ package-lock.json
└─ frontend/
   ├─ src/
   │  ├─ components/
   │  │  └─ Register.jsx
   │  ├─ App.jsx
   │  └─ main.jsx
   ├─ package.json
   └─ package-lock.json
