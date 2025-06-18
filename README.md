# 📱 Within – A Full-Stack Social Media App

**Within** is a modern, full-stack social media platform inspired by Instagram. Built with scalability and clean UI in mind, it allows users to sign up, post photos, view feeds, and interact with content in real time.

---

## 🚀 Features

- 🔐 User authentication (register/login/logout)
- 🖼️ Image upload with captions
- 📷 Feed display with most recent posts
- ❤️ Like functionality (future: comments, sharing)
- 🧠 Protected routes with auth middleware
- ☁️ Firebase storage integration for image hosting
- ⚙️ Built with a modular backend and clean UI

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Axios
- React Router

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT for Auth
- Firebase (Storage)

---

## 📂 Project Structure

```bash
within/
│
├── client/         # React frontend
│   ├── src/
│   └── ...
│
├── server/         # Node.js backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── ...
│
├── .env.example    # Sample env file
├── README.md
└── package.json