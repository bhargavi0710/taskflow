# ✅ TaskFlow – Smart Cloud To-Do App

A modern cloud-native task management platform built with **Flask, Firebase Firestore, and Render**. TaskFlow enables users to securely manage tasks, track productivity, and monitor progress through a responsive web interface with real-time cloud persistence.

🌐 **Live Application:** https://flask-to-do-app-ac3a.onrender.com

---

## 🚀 Key Features

### 🔐 Secure Authentication
- User registration and login system
- Password hashing using BCrypt
- Session management with Flask-Login
- User-specific task isolation

### 📋 Task Management
- Create, update, and delete tasks
- Track task status:
  - Pending
  - Partially Completed
  - Completed
- Real-time task updates

### 📊 Productivity Dashboard
- Dynamic progress tracking
- Visual task completion statistics
- Task status breakdown

### 🔍 Smart Search & Filtering
- Search tasks instantly
- Filter by task status
- Improved task organization

### 🌙 Enhanced User Experience
- Dark mode support
- Theme preference persistence using localStorage
- Modern glassmorphism-inspired UI
- Responsive design across devices

### ☁️ Cloud-Powered Architecture
- Firebase Firestore for persistent storage
- Hosted on Render
- Automatic deployment pipeline

---

## 🏗️ System Architecture

```text
Browser
   │
   ▼
Frontend (HTML/CSS/JavaScript)
   │
   ▼
Flask Application Server
   │
   ├── Authentication Layer
   │       └── Flask-Login + BCrypt
   │
   └── Task Management Logic
           │
           ▼
Firebase Firestore
```

---

## 🛠️ Technology Stack

| Layer | Technology |
|---------|---------|
| Backend | Flask (Python) |
| Database | Firebase Firestore |
| Authentication | Flask-Login, BCrypt |
| Frontend | HTML5, CSS3, JavaScript |
| Deployment | Render |
| Version Control | Git & GitHub |

---

## 🧠 Engineering Highlights

### Cloud Database Integration
Integrated Firebase Firestore for scalable cloud-based task storage and retrieval.

### Secure Authentication
Implemented BCrypt password hashing and Flask-Login session management for secure user authentication.

### Responsive User Interface
Built a modern glassmorphism-inspired interface with dark mode support and responsive layouts.

### Automated Deployment
Configured Render for continuous deployment directly from GitHub.

---

## 🖥️ Running Locally

### 1. Clone the Repository

```bash
git clone https://github.com/bhargavi0710/taskflow.git
cd taskflow
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Firebase Credentials

Place your Firebase service account key:

```text
firebase_key.json
```

at:

```text
/etc/secrets/firebase_key.json
```

or update the path in:

```python
app.py
```

### 5. Run the Application

```bash
python app.py
```

Open:

```text
http://localhost:5000
```

---

## ☁️ Deployment

TaskFlow is deployed on Render:

https://flask-to-do-app-ac3a.onrender.com

### Deployment Workflow

- Push changes to GitHub
- Render automatically detects updates
- Application redeploys automatically

---

## 🔮 Future Enhancements

- Task deadlines and reminders
- Email notifications
- Calendar integration
- Recurring tasks
- Team collaboration
- Shared workspaces
- Mobile application
- AI-powered productivity assistant

---

## 👩‍💻 Author

**Bhargavi Jagdale**

B.E. Computer Engineering, MMCOE Pune

- GitHub: https://github.com/bhargavi0710
- LinkedIn: https://www.linkedin.com/in/bhargavi-jagdale-a29b69290

---

## 📄 License

MIT License — free to use and modify.
