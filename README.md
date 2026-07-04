# 💬 NexChat

**NexChat** is a modern full-stack messaging platform inspired by WhatsApp, built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. It provides fast, secure, and real-time communication with support for private chats, group conversations, media sharing, and a responsive user experience.

---

# ✨ Features

## 👤 User Features

* Secure User Authentication
* One-to-One Messaging
* Group Chats
* Real-Time Messaging
* Media & File Sharing
* Emoji Support
* Online/Offline Status
* Typing Indicators
* Read Receipts
* Search Conversations
* User Profiles
* Responsive Mobile-Friendly Interface

---

# ⚙️ Core Features

* JWT Authentication
* Socket.IO Real-Time Communication
* Protected Routes
* RESTful APIs
* Cloud File Upload Support
* Responsive Design
* Optimized Database Queries
* Error Handling
* Environment Variable Configuration
* Clean & Scalable Architecture

---

# 🛠 Tech Stack

## Frontend

* React.js
* JavaScript
* HTML5
* CSS3 / Tailwind CSS
* Axios
* Socket.IO Client

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* Socket.IO
* JWT Authentication
* bcrypt
* Cloudinary (or equivalent cloud storage)

---

# 📂 Project Structure

```text
NexChat
│
├── Frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── Backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── services/
│   └── package.json
│
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/NexChat.git

cd NexChat
```

---

## Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Run the backend:

```bash
npm start
```

---

## Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

# 🔐 Environment Variables

Configure the following:

* MongoDB Connection URI
* JWT Secret
* Cloud Storage Credentials
* Client URL
* Socket Server URL

---

# 📸 Screenshots

Add screenshots after deployment.

* Login Page
* Registration Page
* Chat List
* Private Chat
* Group Chat
* User Profile
* Media Sharing
* Mobile View

---

# 📡 API Overview

Example endpoints:

```text
POST   /api/auth/register
POST   /api/auth/login

GET    /api/chats
POST   /api/chats

GET    /api/messages/:chatId
POST   /api/messages

GET    /api/users
GET    /api/users/:id
PUT    /api/users/profile

POST   /api/groups
PUT    /api/groups/:id
DELETE /api/groups/:id
```

---

# 📱 Responsive Design

* Desktop
* Tablet
* Mobile

---

# 🔒 Security

* JWT Authentication
* Password Hashing with bcrypt
* Protected API Routes
* Input Validation
* Secure Environment Variables
* Robust Error Handling

---

# 🚀 Future Improvements

* Voice & Video Calling
* End-to-End Encryption
* Voice Messages
* Message Reactions
* Status Updates
* Message Scheduling
* AI Chat Assistant
* Dark Mode
* Multi-Device Support
* Push Notifications

---

# 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome. Feel free to fork the repository and submit a pull request.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 🙏 Acknowledgment

This project is based on the **MERN-Stack-Projects** repository by **Kunal Tyagi** and has been significantly modified with UI redesigns, architectural improvements, performance optimizations, additional functionality, and overall codebase enhancements.

**Original Repository:**

https://github.com/kunaltyagi9/MERN-Stack-Projects
