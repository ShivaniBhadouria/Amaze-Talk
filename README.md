<h1 align="center">🚀 AmazeTalk – MERN Chat App</h1>

<p align="center">
  <a href="https://realtime-chat-app-one-topaz.vercel.app/auth">
    🔗 <strong>Live Demo</strong>
  </a>
  |
  <a href="https://github.com/ShivaniBhadouria/Amaze-Talk">
    📦 <strong>Source Code</strong>
  </a>
</p>

---

## 📚 Project Overview

**AmazeTalk** is a real-time chat application built with the powerful **MERN Stack** and **Socket.IO** to enable seamless real-time messaging. Users can chat one-on-one, create groups, send/accept friend requests, and stay connected with online statuses and live typing indicators.

---

## 🖼️ Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/f6ffb3b6-9674-409a-9f84-305955ebbfdb" width="500" />
  <img src="https://github.com/user-attachments/assets/e1f411c6-3297-4530-b66c-768e1744cf66" width="500" />
  <img src="https://github.com/user-attachments/assets/f71e8d69-9927-4683-9206-ad4db734d6f3" width="500" />
  <img src="https://github.com/user-attachments/assets/b0d16a5d-eb8a-49da-83c0-a81f2a97cf27" width="500" />
  <img src="https://github.com/user-attachments/assets/474b566c-555d-4e0a-9a87-b2b2a04041eb" width="500" />
  <img src="https://github.com/user-attachments/assets/9d8271d6-45d3-4eb9-a243-bee90092ecb3" width="500" />
</p>

---


## ⚙️ How It Works

### 🔁 Architecture

1. **Frontend (React.js):** Handles UI and API requests to backend. Uses Socket.IO for real-time events.
2. **Backend (Node.js + Express):** REST API to manage users, authentication, messages, groups, and notifications.
3. **Database (MongoDB):** Stores user data, chats, groups, and messages.
4. **Socket.IO:** Enables real-time features like live chat, typing indicators, online presence, etc.
5. **JWT (JSON Web Tokens):** Used for secure authentication across sessions.

---

## 🔍 Features

### ✅ Basic Features

- 🔐 **JWT Authentication:** Secure login and registration.
- 🧑‍🎨 **Profile Picture Support:** Upload and manage avatars.
- 🔎 **Search Users:** Search by username or email.
- ✉️ **Send & Accept Chat Requests:** Like friend requests—must accept before chatting.
- 💬 **Private Chat:** One-on-one messaging.
- 👥 **Group Chat:** Real-time group messaging with multiple users.
- 🔔 **Real-Time Notifications:** Get instantly notified for new messages.
- 📱 **Responsive UI:** Works perfectly on mobile, tablet, and desktop.
- 🎞️ **Framer Motion UI Effects:** Smooth transitions and user feedback animations.

---

## 🌟 Unique Features

- 🔄 **Two-Way Friend Request System:** Only mutually accepted users can chat.
- 🏷️ **Group Creation with Member Search:** Create and name groups with selected users instantly.
- 🚦 **User Presence & Real-Time Sync:** Status indicators and real-time message syncing.


---

## 💻 Tech Stack

| Layer       | Technology                        |
|------------|------------------------------------|
| Frontend    | React.js, Framer Motion           |
| Backend     | Node.js, Express.js                |
| Database    | MongoDB                            |
| Real-Time   | Socket.IO                          |
| Auth        | JWT (JSON Web Tokens)              |
| Styling     | Tailwind CSS                       |
| Deployment  | Vercel (Frontend), Render (Backend) |

---

🔧 Backend Setup
bash
Copy
Edit
cd backend
npm install
📄 Create a .env file in the /backend folder and add:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
▶️ Start Backend Server

bash
Copy
Edit
npm start
📍 Server runs at: http://localhost:5000

🎨 Frontend Setup
bash
Copy
Edit
cd ../frontend
npm install
📝 (Optional) Update API base URL in axios.js or .env if needed.

▶️ Start Frontend App

bash
Copy
Edit
npm start
📍 Frontend runs at: http://localhost:3000

🔗 Live Demo
Try it live here:
🌐 https://realtime-chat-app-one-topaz.vercel.app/auth

🧑‍💻 Contributing
We welcome all contributions! Follow the steps below to contribute:

🚀 How to Contribute
🍴 Fork the repository

📁 Create a new branch:

bash
Copy
Edit
git checkout -b my-feature
💡 Make your changes

✅ Commit and push:

bash
Copy
Edit
git commit -m "Add new feature"
git push origin my-feature
📥 Submit a Pull Request

📄 License
This project is licensed under the MIT License.
You're free to use, modify, and distribute it.

🙌 Acknowledgments
Made with ❤️ by @shivanibhadouria
