# ✅ TaskFlow – Smart Cloud To-Do App

A fast, elegant, cloud-powered To-Do application built with Flask and Firebase. Users can register, log in, and manage tasks with real-time status tracking — all deployed and live on Render.

🌐 **Live App:** [https://flask-to-do-app-ac3a.onrender.com](https://flask-to-do-app-ac3a.onrender.com)

---

## 🚀 Features

- 🔐 User authentication (register & login with hashed passwords)
- ✅ Add, update (Pending / Partially Completed / Completed), and delete tasks
- 📊 Visual progress bar with task breakdown
- 🔍 Search/filter tasks
- 🌙 Dark mode toggle (persisted via localStorage)
- 🎨 Modern glassmorphism UI with animated backgrounds
- ☁️ Cloud-backed with Firebase Firestore

---

## 🛠️ Tech Stack

| Layer      | Technology              |
|------------|-------------------------|
| Backend    | Python (Flask)          |
| Database   | Firebase Firestore      |
| Auth       | Flask-Login + Bcrypt    |
| Frontend   | HTML, Vanilla CSS, JS   |
| Deployment | [Render](https://render.com) |

---

## 🖥️ Running Locally

1. **Clone the repository:**
   ```bash
   git clone git@github.com:bhargavi0710/taskflow.git
   cd taskflow
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   venv\Scripts\activate   # Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add your Firebase credentials:**
   Place your `firebase_key.json` at `/etc/secrets/firebase_key.json` (or update the path in `app.py`).

5. **Run the app:**
   ```bash
   python app.py
   ```

6. Open your browser at `http://localhost:5000`

---

## ☁️ Deployment on Render

This app is already deployed at [https://flask-to-do-app-ac3a.onrender.com](https://flask-to-do-app-ac3a.onrender.com).

To trigger a redeployment: simply **push to the `main` branch** — Render auto-deploys on every push.
