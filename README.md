# Real-Time Chat Application

### Live Demo
[Check out the Live Demo here!](https://appusingsocketmaaz.netlify.app/)

---

## Overview
This project is a real-time chat application built with **Node.js**, **Express**, and **Socket.IO**. It allows users to join a chat room and communicate instantly. Messages are broadcasted to all users, enabling live interaction. The interface is styled for simplicity and responsiveness.

## Features
- Real-time messaging with Socket.IO.
- Interactive user interface with custom styling.
- Separate color schemes for outgoing and incoming messages.
- Automatic scrolling for new messages.
- Name prompt for each user.

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/realtime-chat-app.git
    ```
2. Navigate to the project folder:
    ```bash
    cd realtime-chat-app
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

### Running the Application
1. Start the server:
    ```bash
    npm run dev
    ```
2. Open your browser and navigate to `http://localhost:3000`.

## Project Structure
```
realtime-chat-app/
│
├── public/               # Contains client-side files
│   ├── style.css         # Styles for the chat interface
│   ├── client.js         # Client-side JavaScript for chat functionality
│   └── wassup.png        # Logo image for branding
│
├── server.js             # Main server file with Express and Socket.IO setup
├── index.html            # Main HTML file for the chat interface
└── package.json          # Project configuration and dependencies
```

## Usage
- Upon opening the app, users are prompted to enter their name.
- Users can type messages into the text area and press "Enter" to send.
- Each message will appear in the chat interface, with outgoing messages styled differently from incoming messages.

## Technologies Used
- **Node.js**: JavaScript runtime for server-side programming.
- **Express**: Web framework for building the server.
- **Socket.IO**: Enables real-time, bidirectional communication between clients and the server.

## License
This project is licensed under the MIT License.
