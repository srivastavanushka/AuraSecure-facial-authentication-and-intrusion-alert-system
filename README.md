# 🛡️ AuraSecure

### AI-Powered Facial Authentication & Real-Time Intrusion Alert System

**Secure Access • Intelligent Surveillance • Real-Time Monitoring**

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-React-black?logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-5C3EE8?logo=opencv&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-07405E?logo=sqlite&logoColor=white)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

---

## 🌟 Overview

**AuraSecure** is a full-stack, AI-powered security system that combines **Computer Vision**, **Machine Learning**, and **modern web development** to deliver contactless facial authentication and real-time intrusion detection.

The system continuously analyzes a live camera feed, verifies authorized individuals through facial recognition, flags unknown faces, logs intrusion events, and gives administrators a centralized dashboard to monitor and manage security activity — all without a single password or access card.

Built with a modular architecture, AuraSecure demonstrates how AI models can be integrated with production-style web technologies to solve real-world access control and surveillance problems.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔐 Real-time Facial Authentication | Verifies registered users instantly via live camera feed |
| 🚨 Automatic Intrusion Detection | Flags unrecognized faces and triggers alerts |
| 📷 Intruder Snapshot Capture | Automatically captures and stores images of unauthorized access attempts |
| 👥 Authorized User Management | Add, review, and manage registered users from the dashboard |
| 📊 Admin Dashboard | Centralized interface for monitoring access logs and alerts |
| 📈 Security Event Logging | Full history of authentication attempts and intrusions |
| ⚡ Cooldown Logic | Prevents duplicate/spam alerts for the same intrusion event |
| 🌐 Modern Responsive UI | Built with Next.js, React, and Tailwind CSS |

---

## 🏗️ How It Works

```
Camera Feed
    │
    ▼
Face Detection
    │
    ▼
Face Recognition (Embedding Match)
    │
    ▼
Identity Verification
    │
    ├── Authorized ──▶ Grant Access ──▶ Log Event ──▶ Update Dashboard
    │
    └── Unauthorized ──▶ Capture Image ──▶ Generate Alert ──▶ Admin Dashboard
```

---

## 🛠️ Tech Stack

**Frontend**
`Next.js` · `React` · `Tailwind CSS`

**Backend**
`Python` · `FastAPI` · `REST APIs`

**AI / Computer Vision**
`OpenCV` · `dlib` · `face_recognition` · `NumPy`

**Database**
`SQLite`

**Tools**
`Git` · `GitHub`

---

## 📂 Project Structure

```
AuraSecure/
│
├── app/               # Next.js app routes & pages
├── backend/            # FastAPI backend logic
├── components/          # Reusable React UI components
├── hooks/              # Custom React hooks
├── lib/                # Shared utilities/helpers
├── styles/              # Global styling
├── public/              # Static assets
├── faces/               # Stored facial embeddings/data
│
├── app.py                # FastAPI entry point
├── face.py               # Face detection & recognition logic
├── create_db.py           # Database initialization
├── insert_authorized.py    # Add authorized users
├── insert_alert.py         # Log intrusion alerts
└── package.json            # Frontend dependencies
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- Node.js 18+
- pip and npm/pnpm installed

### 1. Clone the repository
```bash
git clone https://github.com/srivastavanushka/AuraSecure-facial-authentication-and-intrusion-alert-system.git
cd AuraSecure-facial-authentication-and-intrusion-alert-system
```

### 2. Set up the backend
```bash
pip install -r requirements.txt
python create_db.py
uvicorn app:app --reload
```

### 3. Set up the frontend
```bash
npm install
npm run dev
```

### 4. Open the app
Visit `http://localhost:3000` in your browser.

> ⚠️ Note: Update the steps above if your dependency/run commands differ (e.g., if you use `pnpm` instead of `npm`, or a different requirements file).

---

## 🎯 Use Cases

- Smart office & corporate access control
- Educational institution security
- AI-based attendance systems
- Visitor authentication
- Building entry management
- Smart surveillance systems

---

## 📈 Future Enhancements

- [ ] Multi-camera support
- [ ] Liveness detection (anti-spoofing)
- [ ] Face mask detection
- [ ] Email / SMS alert notifications
- [ ] Cloud database integration
- [ ] Docker containerization
- [ ] Mobile application
- [ ] Role-Based Access Control (RBAC)

---

## 📚 Skills Demonstrated

`Artificial Intelligence` · `Computer Vision` · `Face Recognition` · `Full-Stack Development` · `REST API Design` · `Backend Engineering` · `Frontend Development` · `Database Design` · `Authentication Systems` · `Security Monitoring` · `Software Architecture`

---

## 💡 Why AuraSecure?

Unlike traditional authentication systems that rely on passwords or access cards, AuraSecure uses AI-driven facial recognition to deliver a seamless, contactless, and secure authentication experience. By combining real-time intrusion detection with a centralized monitoring dashboard, the project demonstrates how modern computer vision techniques can be applied to solve practical, real-world security challenges — end to end, from camera feed to admin action.

---

## 🤝 Contributing

Contributions, feature requests, and suggestions are welcome. Feel free to fork the repository, open an issue, or submit a pull request.

---

## 👩‍💻 Author

**Anushka Srivastav**
Passionate about Artificial Intelligence, Full-Stack Development, and building intelligent software solutions.

[GitHub](https://github.com/srivastavanushka) · [LinkedIn](https://www.linkedin.com/in/anushka-srivastav-)

---

## ⭐ Support

If you found this project interesting, consider giving it a star — it helps increase visibility and supports future development.

---

## 📄 License

This project is intended for educational and research purposes. Please ensure any use or redistribution complies with the licenses of all third-party libraries used.









