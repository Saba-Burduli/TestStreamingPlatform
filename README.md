# TestStreamingPlatform

## Overview

TestStreamingPlatform is an experimental project designed to explore and simulate the core components of a video streaming platform. It focuses on backend architecture, media delivery workflows, and API-based content serving.

The project is intended for learning and prototyping streaming-related systems rather than production deployment.

---

## Project Structure

Typical structure may include:

TestStreamingPlatform/
├── backend/
├── frontend/
├── media/
├── tests/
├── package.json (Node.js projects)
├── requirements.txt (Python projects)
└── entry files (server.js / index.js / main.py / app.py)

---

## How to Run the Project

Because implementations may vary, follow the steps below to identify and start the project correctly.

### 1. Clone the repository

git clone https://github.com/Saba-Burduli/TestStreamingPlatform
cd TestStreamingPlatform

---

### 2. Identify the project type

Check the root directory:

ls

Look for:

- package.json → Node.js project
- requirements.txt → Python project
- both → mixed architecture (frontend + backend)

---

### 3. Install dependencies

If Node.js project (package.json exists)

npm install

Check available scripts:

cat package.json

Common scripts:
- start
- dev
- test

---

If Python project (requirements.txt exists)

Create virtual environment:

python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows

Install dependencies:

pip install -r requirements.txt

---

### 4. Find the entry point

Common Node.js entry files:
- index.js
- server.js
- app.js

Common Python entry files:
- main.py
- app.py
- run.py

---

### 5. Run the application

Node.js

npm start

or:

node index.js

---

Python

python main.py

or:

uvicorn main:app --reload   (FastAPI)
python manage.py runserver (Django)

---

### 6. Development mode (if available)

Node.js

npm run dev

---

### 7. Configure environment variables (if required)

If .env.example exists:

cp .env.example .env

Configure:

- PORT
- DATABASE_URL
- STORAGE_PATH

---

### 8. Verify the server is running

Open:

http://localhost:3000

or run:

curl http://localhost:PORT

---

### 9. Common troubleshooting

Port already in use:

lsof -i :3000
kill -9 <PID>

Missing dependencies:

npm install
pip install -r requirements.txt

Wrong entry file:
Check package.json or project root.

---

## Purpose

- Learn streaming platform architecture
- Build backend APIs for media delivery
- Experiment with video streaming workflows
- Test modular server-side system design

---

## Future Improvements

- Adaptive streaming (HLS/DASH)
- Authentication system
- Real-time analytics
- CDN simulation layer
- Live streaming support

---

## Author

Saba Burduli
