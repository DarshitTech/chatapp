

#  Real-Time Chat Application  
A minimal yet powerful chat web app that enables users to **communicate instantly** using **WebSockets** via `Socket.IO`. Designed with simplicity and real-time efficiency in mind. 🚀  

---

## 🌟 Features

- 💬 **Instant Messaging** – Real-time chat updates with zero delay.  
- 🔐 **User Authentication** – Secure access and login support.  
- 📱 **Responsive UI** – Works beautifully across devices.  
- 👥 **Group Chats** – Supports multiple users in the same room.  
- ✍️ **Typing Indicators** – See when someone is typing.  
- 💾 **Message History** – Persistent chat history across sessions.

---

## 🔧 Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)  
- [Node.js & npm](https://nodejs.org/)

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone <repository-url>
cd <project-folder-name>
```

### 2️⃣ Initialize the Project
```bash
npm init -y
```

### 3️⃣ Install Required Dependencies
```bash
npm install express socket.io nodemon
```

### 4️⃣ Run the Server
```bash
nodemon server.js
```

> 💡 `nodemon` will restart the server automatically on file changes.

---

## 🔌 WebSocket Overview

- Clients connect using `socket.io-client`.  
- Server listens for and **broadcasts** messages in real-time.  
- Supports custom events like user joins, message sends, and typing status.

```js
// Example Server Logic
io.on('connection', (socket) => {
  socket.on('message', (data) => {
    io.emit('message', data); // Broadcasts to all users
  });

  socket.on('typing', (user) => {
    socket.broadcast.emit('typing', user); // Notify others
  });
});
```

---

## 🎥 Demo & Preview

- 🎬 **Video Walkthrough**: [Watch on YouTube](https://youtu.be/DJ3zk0Vr28I)  

---

## 🤝 Contributing

We ❤️ contributions!  
Feel free to:
- Fork the repository  
- Submit pull requests  
- Suggest new features or improvements in [Issues](https://github.com/DarshiT2009/chatapp/issues)

---

## 📌 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express.js  
- **Real-Time**: Socket.IO  
- **Dev Tools**: Nodemon

---

## 🙌 Acknowledgements

- [Socket.IO](https://socket.io/)  
- [Express.js](https://expressjs.com/)  
- [MDN Web Docs](https://developer.mozilla.org/)





