# CollabDoc

A real-time collaborative document editor that enables multiple users to edit the same document simultaneously with instant synchronization.

## 📋 About the Project

CollabDoc is a web-based collaborative text editor built with modern web technologies. It allows multiple users to work on the same document in real-time, seeing each other's changes instantly. The application uses WebSocket technology to maintain persistent connections between clients and the server, ensuring seamless real-time collaboration.

### 🔧 How It Works

- **Frontend**: React-based interface that provides a clean text editing experience  
- **Backend**: Node.js server with Express and WebSocket handling  
- **Real-time Communication**: WebSocket connections maintain live communication between all clients  
- **State Synchronization**: The server acts as a single source of truth, broadcasting changes to all connected clients  

### 🎯 Key Features

- **Live Collaboration**: Multiple users can type simultaneously  
- **Instant Updates**: Changes appear across all clients in real-time  
- **No Setup Required**: Users can join simply by visiting the URL  
- **Simple Interface**: Focused on the core functionality of collaborative editing  

## ✨ Features

- **Real-time Collaboration** - Multiple users can edit simultaneously  
- **Instant Synchronization** - Changes appear across all clients instantly  
- **Simple Interface** - Clean, intuitive text editor  
- **WebSocket Technology** - Efficient real-time communication  

## 🚀 Quick Start

### Prerequisites
- Node.js (version 14 or higher)
- npm

### Installation

1. **Install server dependencies:**
    ```bash
    npm install express ws cors
    ```

2. **Install client dependencies:**
    ```bash
    cd Client
    npm install
    ```

### Running the Application

1. **Start WebSocket server (Terminal 1):**
    ```bash
    node server.js
    ```
    Server runs on: [http://localhost:5000](http://localhost:5000)

2. **Start React client (Terminal 2):**
    ```bash
    cd Client
    npm start
    ```
    Client runs on: [http://localhost:3000](http://localhost:3000)

## 🎮 Usage

1. Open your browser to `http://localhost:3000`  
2. Share the URL with collaborators  
3. Open multiple browser windows/tabs to the same address  
4. Start typing - changes will sync in real-time across all clients  


## ⚙️ Configuration

- **Change server port:** Edit `PORT` variable in `server.js`  
- **Change WebSocket URL:** Update connection URL in `Client/src/App.js`  

## 🐛 Troubleshooting

- **Port conflicts:** Change port number or kill existing process  
- **Module errors:** Run `npm install` in the correct directory  
- **Connection issues:** Ensure both server and client are running simultaneously  



