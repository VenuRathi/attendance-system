# RFID Attendance System

A modern, full-stack RFID-based attendance system with real-time analytics dashboard, built for classrooms and events. Features a Python Flask backend, React dashboard frontend, and ESP32/Arduino client integration.

---

## 🚀 Features
- RFID-based attendance marking
- Real-time analytics dashboard
- Lecture/session management
- Duplicate/invalid scan detection
- RESTful API (Flask backend)
- Modern React dashboard (Vite/TypeScript)
- ESP32/Arduino client code
- Data analytics and visualization

---

## 🗂️ Project Structure

```
attendance-system/
│
├── backend/         # Flask backend (API, DB, logic)
├── analytics/       # Data analysis scripts
├── clients/         # Demo sender & ESP32 code
├── replitui/        # React dashboard & UI libraries
├── ui/              # Simple static frontend
├── requirements.txt # Python dependencies
├── test_api.html    # API testing page
└── ...
```

---

## ⚙️ Setup & Usage

### 1. Backend (Flask)
```bash
cd backend
python -m venv ../.venv
source ../.venv/bin/activate  # or .venv\Scripts\activate on Windows
pip install -r ../requirements.txt
python app.py
```
- Runs at: http://localhost:5000

### 2. Frontend (React Dashboard)
```bash
cd replitui/rfid-dashboard
pnpm install  # or npm install
pnpm dev      # or npm run dev
```
- Runs at: http://localhost:5173

### 3. Demo Client
```bash
cd clients
python demo_sender.py
```

---

## 📡 API Endpoints (Sample)
- `POST /attendance` — Mark attendance (RFID scan)
- `GET /attendance` — List attendance records
- `POST /api/lectures/start` — Start a lecture
- `POST /api/lectures/end` — End a lecture
- `POST /api/reset` — Reset system

See backend/app.py for full API details.

---

## 🛠️ Tech Stack
- Python, Flask, SQLite
- React, TypeScript, Vite
- ESP32/Arduino (RFID client)

---

## 👤 Author
- Venu Rathi

---

## 📸 Screenshots
_Add screenshots or demo GIFs here_

---

## ⭐️ Star this repo if you found it useful!
