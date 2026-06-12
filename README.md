# 💬 MERN Chat Application

A full-stack real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js).  
It supports user authentication, one-to-one chat, group chat, and real-time messaging features.

---

## 🚀 Live Demo

- Frontend: https://your-frontend.vercel.app  
- Backend API: https://your-backend.onrender.com  

---

## 🛠️ Tech Stack

### Frontend:
- React.js (Vite)
- Redux Toolkit
- React Router
- Fetch API / Axios
- Tailwind CSS

### Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- bcrypt.js
- CORS

---
project-root/
│
├── backend/
│ ├── controllers/
│ ├── routes/
│ ├── middlewares/
│ ├── models/
│ ├── server.js
│
├── frontend/
│ ├── src/
│ ├── redux/
│ ├── components/
│ ├── pages/
│



---

## ⚙️ Features

- 🔐 User Signup & Login (JWT Authentication)
- 💬 One-to-One Chat
- 👥 Group Chat (Create, Add, Remove, Rename)
- 📩 Real-time message updates
- 🧠 Redux state management
- 📷 Profile image support (Gravatar/default avatar)
- 📱 Responsive UI

---

## 🔐 Environment Variables

### Backend (`.env`)
Create a `.env` file inside backend:


MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=9000



---

### Frontend (`.env`)
Create a `.env` file inside frontend:
VITE_BACKEND_URL=https://your-backend.onrender.com


---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo


Auth Routes:
POST /api/auth/signup
POST /api/auth/signin


Chat Routes:
GET /api/chat
POST /api/chat
POST /api/chat/group
POST /api/chat/rename
POST /api/chat/groupadd
POST /api/chat/groupremove
DELETE /api/chat/deleteGroup/:chatId

Frontend (Vercel):
Deploy frontend folder
Add environment variable VITE_BACKEND_URL
Backend (Render):
Deploy backend folder
Add MongoDB URI + JWT secret
Enable CORS for frontend domain




⭐ Future Improvements
Real-time socket.io messaging
Typing indicators
Online/offline status
Message read receipts
File/image sharing




## 📁 Project Structure
