# 🎥 NEXMEET

A real-time video conferencing and chat application built with React, Node.js, Socket.IO, WebRTC, and MongoDB.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Express-green?logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb)
![Socket.IO](https://img.shields.io/badge/Socket.IO-RealTime-black?logo=socket.io)

---

## 📖 Overview

NEXMEET is a full-stack video conferencing platform that enables users to communicate through real-time video and audio calls, exchange instant messages, and collaborate seamlessly. Built using WebRTC and Socket.IO, the application provides low-latency communication and a smooth meeting experience.

Whether for online classes, team meetings, interviews, or virtual collaboration, NEXMEET offers a secure and user-friendly environment for communication.

---

live link :https://nexmeet-the-video-conferencing-app-1.onrender.com/
<img width="1341" height="615" alt="image" src="https://github.com/user-attachments/assets/3091881e-8b3a-4baf-956d-66d253a4f777" />


## ✨ Features

- 🎥 Real-time video conferencing
- 🎙️ High-quality audio communication
- 💬 Instant chat messaging
- 👥 Create and join meeting rooms
- 🔐 User authentication and authorization
- 📹 Camera on/off controls
- 🎤 Microphone mute/unmute functionality
- 🖥️ Screen sharing support
- ⚡ Low-latency communication using WebRTC
- 🌐 Share meeting links instantly
- 📱 Responsive design for desktop and mobile devices

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Material UI (MUI)
- React Router DOM
- Axios
- Socket.IO Client

### Backend
- Node.js
- Express.js
- Socket.IO
- JWT Authentication
- MongoDB
- Mongoose

### Real-Time Communication
- WebRTC
- Socket.IO

### Deployment
- Vercel / Netlify (Frontend)
- Render / Railway (Backend)
- MongoDB Atlas (Database)

---

## 📂 Project Structure

```bash
NEXMEET
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   ├── hooks
│   │   └── App.jsx
│   └── package.json
│
├── backend
│   ├── models
│   ├── routes
│   ├── middleware
│   ├── controllers
│   ├── socket
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/PaulamiS/NEXMEET-The-video-conferencing-app.git
```

### Install Frontend Dependencies

```bash
cd frontend
npm install
```

### Install Backend Dependencies

```bash
cd ../backend
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the backend directory.

```env
PORT=8000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLIENT_URL=http://localhost:5173
```

---

## ▶️ Running the Application

### Start Backend Server

```bash
cd backend
npm run dev
```

### Start Frontend Server

```bash
cd frontend
npm run dev
```

The application will be available at:

```text
Frontend: http://localhost:5173
Backend:  http://localhost:8000
```

---

## 🚀 Usage

1. Register or log in to your account.
2. Create a new meeting room.
3. Share the room link with participants.
4. Join the room and start communicating.
5. Use video, audio, chat, and screen-sharing features.
6. End or leave the meeting securely.

---

## 📸 Key Functionalities

### Video Conferencing
- Real-time peer-to-peer video calls using WebRTC.

### Chat Messaging
- Instant communication powered by Socket.IO.

### Authentication
- Secure login and registration using JWT.

### Room Management
- Create, join, and manage meeting rooms.

### Screen Sharing
- Share your screen for presentations and collaboration.

---

## 🔒 Security Features

- JWT-based authentication
- Protected API routes
- Secure WebSocket communication
- MongoDB data persistence
- Room-based participant access

---

## 🎯 Future Enhancements

- Meeting recording
- AI-generated meeting summaries
- Virtual backgrounds
- Breakout rooms
- Live captions
- File sharing
- Calendar integration

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👩‍💻 Author

**Paulami Sahu**

- GitHub: https://github.com/PaulamiS





