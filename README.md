# Real-Time Chat Application


## Overview
A simple and efficient real-time chat application that allows users to communicate instantly using WebSockets.

## Features
- **Real-time Messaging**: Instant chat updates using WebSocket technology.
- **User Authentication**: Secure access for users.
- **Responsive Design**: Optimized for both mobile and desktop.
- **Group Chats & Typing Indicators**: Enhanced user interaction.
- **Persistent Message History**: Stores past conversations.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js, Socket.io

## Prerequisites
Ensure you have the following installed:
- **Git**: [Download & Install Git](https://git-scm.com/)
- **Node.js**: [Download & Install Node.js](https://nodejs.org/)
- **npm**: Comes with Node.js installation

## Setup Instructions

### Step 1: Clone the Repository
```sh
git clone <repository-url>
cd <project-folder-name>
```

### Step 2: Initialize the Project
```sh
npm init -y
```
This will generate a `package.json` file with default settings.

### Step 3: Install Dependencies
```sh
npm install
npm install express socket.io nodemon
```
This installs:
- **Express**: Handles server-side logic.
- **Socket.io**: Enables real-time communication.
- **Nodemon**: Automatically restarts the server on changes.

### Step 4: Run the Server
```sh
nodemon server.js
```
This starts the server and watches for changes.

## WebSocket Implementation
- Clients connect via WebSockets for real-time messaging.
- Server broadcasts messages to connected users.



## Contributing
Contributions are welcome! Fork the repository, create a branch, and submit a pull request.



🚀 **Start chatting in real time today!**



---

