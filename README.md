# Talkalot Realtime Chat Application 💬🚀

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Key Features](#features)
  - [File Structure](#file-structure)
  - [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Future Improvements](#future-improvements)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
**Talkalot** is a **real-time chat application** built using the **MERN stack** (MongoDB, Express.js, React, and Node.js). It allows users to engage in private and group chat conversations, send messages, and receive real-time notifications. The app also supports user authentication, providing a secure environment for messaging. The app is fully responsive, meaning users can chat seamlessly on both desktop and mobile devices.

### The challenge
The goal of this project was to build a fully functional and secure chat application with the following objectives:
- **User authentication**: Secure login and registration with JWT tokens.
- **Real-time messaging**: Instant chat experience using **Socket.io**.
- **Private and group chat rooms**: Enable users to have private conversations and create public or private group chats.
- **Message notifications**: Real-time notifications for incoming messages.
- **Responsive UI**: A responsive frontend to ensure a smooth experience across devices.

### Features
- **Real-time Messaging**: Send and receive messages instantly without refreshing the page, powered by **Socket.io**.
- **User Authentication**: Sign up, login, and manage user sessions with JWT-based authentication.
- **Private & Group Chats**: Create or join chat rooms for one-on-one private chats or group discussions.
- **Message Notifications**: Get real-time notifications for new messages.
- **User Profile**: Customize the user profile with a username and profile picture.
- **Responsive Design**: The chat application works well on mobile and desktop devices.

### File Structure
```
/root-directory
|-- backend/                     # Backend server (Node.js, Express, MongoDB)
|   |-- controllers/              # Handles API logic (user authentication, chat room management)
|   |-- models/                   # MongoDB models (User, Message, Room)
|   |-- routes/                   # API routes (auth, messages, rooms)
|   |-- socket/                   # Socket.io setup and real-time messaging logic
|   |-- server.js                 # Main backend entry point
|
|-- frontend/                     # Frontend client (React)
|   |-- components/               # React components (ChatWindow, Message, Navbar, etc.)
|   |-- pages/                    # React pages (Home, Login, Register, Chat Room)
|   |-- services/                 # API call functions (auth, chat)
|   |-- App.js                    # Main React component with routing
|   |-- index.js                  # React app entry point
|
|-- .env                          # Environment variables (MongoDB URI, JWT secret)
|-- package.json                  # Project dependencies and scripts
|-- README.md                     # Project description and instructions
```

### Technologies Used
- **MongoDB** for database management (storing user data, messages, and chat rooms).
- **Express.js** for the backend server and API development.
- **React** for building a dynamic and interactive frontend.
- **Node.js** as the backend runtime environment.
- **Socket.io** for real-time, bidirectional communication between the server and clients.
- **JWT** for secure authentication (JSON Web Tokens).
- **Mongoose** for interacting with MongoDB.
- **Axios** for making HTTP requests from the React frontend.

## Setup Instructions

### Prerequisites
- Node.js and npm installed (for both backend and frontend development).
- MongoDB instance (either locally or through a service like MongoDB Atlas).
- Basic knowledge of JavaScript, React, and Node.js.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/talkalot-realtime-chat-application.git
   ```

2. Navigate to the project directory:
   ```bash
   cd talkalot-realtime-chat-application
   ```

3. Set up the **backend**:
   - Navigate to the `backend/` directory:
     ```bash
     cd backend
     ```
   - Install backend dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file in the `backend/` directory with the following content:
     ```
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

4. Set up the **frontend**:
   - Navigate to the `frontend/` directory:
     ```bash
     cd frontend
     ```
   - Install frontend dependencies:
     ```bash
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

5. The app should now be running locally at `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend API.

### Usage
1. **User Authentication:** Sign up and log in to the app to start chatting. The app uses JWT for session management.
2. **Create Chat Rooms:** Once logged in, you can create or join private or group chat rooms.
3. **Send Messages:** Type and send messages in real-time to other users in the room.
4. **Real-time Notifications:** Receive instant notifications when someone sends a message.
5. **Responsive Chat Interface:** Use the app on both mobile and desktop for an optimal experience.

### Future Improvements
- **File Uploads:** Add support for file sharing (images, documents) in chat rooms.
- **Voice & Video Calls:** Integrate WebRTC or a similar solution to enable voice and video calls.
- **Message Reactions:** Allow users to react to messages with emojis.
- **Chatbot Integration:** Add AI-powered chatbots for fun and informative conversations.
- **User Blocking:** Enable users to block other users to prevent unwanted communication.
- **End-to-End Encryption:** Implement end-to-end encryption for secure messaging.

### Useful resources

- [React Documentation](https://reactjs.org/docs/getting-started.html) - The official React documentation.
- [Node.js Documentation](https://nodejs.org/en/docs/) - Learn more about Node.js and how it works.
- [MongoDB Documentation](https://www.mongodb.com/docs/) - Learn how to interact with MongoDB.
- [Socket.io Documentation](https://socket.io/docs/) - Real-time communication in your app.
- [JWT.io Introduction](https://jwt.io/introduction/) - Learn how JSON Web Tokens work for authentication.
- [Express.js Documentation](https://expressjs.com/) - Learn about Express.js for backend development.

## Author

<b><strong>Sarthak Sachdev</strong></b>
- Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)
- LinkedIn - [Sarthak Sachdev](https://www.linkedin.com/in/sarthak2004/)
- Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)

## Acknowledgments

Special thanks to the open-source community and the authors of **MongoDB**, **Express.js**, **React**, **Node.js**, and **Socket.io** for providing the powerful tools that made building this app possible.

## Got feedback for me?

Feel free to reach out via email at saarsaach30[at]gmail[dot]com with any feedback or suggestions!

## Contributing
Contributions are welcome! Fork the repository, make changes, and submit a pull request.

## License📃
This project is licensed under the MIT License.

Copyright (c) 2024, Sarthak Sachdev

**Happy coding!** 😊🚀
