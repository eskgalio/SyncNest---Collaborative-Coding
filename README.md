## 🔄 **SyncNest** — Real-Time Collaborative Coding Platform

> SyncNest is an open-source real-time collaborative coding and communication platform designed for educators, students, and remote teams. It features live code sharing, voice and video conferencing, chat, and shared whiteboard tools—all in a seamless browser-based interface.

---

### 🚀 Features

* ✨ **Real-time Code Collaboration**: Multiple users can code together in real-time.
* 🎙️ **Live Voice & Video Communication**: Embedded conferencing powered by WebRTC.
* 🧑‍🏫 **Whiteboard Integration**: Visual explanations made easy for teaching and brainstorming.
* 🧠 **Multiplayer Terminal & Editor**: Collaborative command-line experience and synced code editor.
* 📋 **Notes & Chat Support**: Rich-text notes, chatroom discussions, and session management.
* 🔐 **Authentication System**: Secure login and room access control.
* 🌐 **Browser-Based**: No setup required—runs directly in your browser.
* 🐳 **Docker Support**: Easily deploy with Docker and Docker Compose.

---

### 📦 Installation & Setup

> **Requirements**

* Node.js (v14+)
* Docker & Docker Compose (for deployment)
* MongoDB
* Git

#### 🔧 Clone and Run Locally

```bash
git clone https://github.com/yourusername/syncnest.git
cd syncnest
npm install
npm run dev
```

#### 🐳 Run via Docker

```bash
docker-compose up --build
```

Make sure to configure your `.env` file using the `.env.example` provided.

---

### 🛠️ Usage

1. Visit the deployed URL or run `localhost:3000` locally.
2. Sign in or create an account.
3. Create or join a coding session.
4. Use the editor, whiteboard, and chat to collaborate with your peers in real time.
5. Invite others using the room link.
6. Use the terminal and whiteboard tools for interactive problem-solving.

---

### 💡 Unique Selling Points (USP)

* Designed specifically for **students and teachers**—a niche focus on the educational ecosystem.
* Integrates **video, audio, chat, and whiteboard** tools into one unified workspace.
* True **zero-installation** collaborative IDE experience.
* Ideal for **remote coding interviews, virtual classrooms**, and **team brainstorming**.
* Fully open-source and **Docker-deployable** for institutions.

---

### 🌐 Deploy on Your Own Server

Use the provided `Dockerfile` and `docker-compose.yml` for easy self-hosting:

```bash
docker-compose -f docker-compose.yml up --build
```

---




