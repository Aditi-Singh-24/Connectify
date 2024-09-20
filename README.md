# Connectify - Messaging Service Prototype
Connectify is a cutting-edge messaging service chat application that allows users to authenticate  designed to showcase secure, real-time communication with modern features like chat one-on-one, and create group chats. This project includes user authentication, one-on-one and group chats, real-time messaging, and optional advanced features like AI-powered chatbots and video/audio calls. It's built with scalability, performance, and user experience in mind.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Application](#running-the-application)


## Features
- **User Authentication(signup/login)**: Secure sign-up and login using JWT for session management.
- **Text Messaging**: Send and receive real-time text messages between users.
- **Group Chat functionality**: Create and participate in group chats with multiple users.
- **Real-Time Updates**:Messages are delivered and updated instantly using Socket.IO.
- **Search User**: Quickly find users by name or other identifiers.
- **Single Chat(One-on-one chat)**: Engage in private one-on-one chat sessions.

## Screenshots

![User Authentication](path/to/user-authentication-screenshot.png)
*User Authentication Screen*

![Login/Signup](path/to/login-signup-screenshot.png)
*Login/Signup Screen*

![My Chats](path/to/my-chats-screenshot.png)
*My Chats Screen*

![Search User](path/to/search-user-screenshot.png)
*Search User Screen*

![Single Chat](path/to/single-chat-screenshot.png)
*Single Chat Screen*

![Group Chat](path/to/group-chat-screenshot.png)
*Group Chat Screen*

## Technologies Used
- **Backend**: Node.js, Express.js, MongoDB, Socket.IO
- **Frontend**: React.js, Chakra UI for a responsive UI
- **Real-Time Updates**: Socket.IO for real-time communication
- **Dev Tools**: Nodemon for server management, JWT for authentication, Mongoose for MongoDB interaction
- **Platforms**: VS Code, Postman, MondoDB.

  
## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/rajendra-17/Connectify.git
   cd Connectify

2. **Install Root Dependencies**:
   ```bash
   npm install --legacy-peer-deps

## List of Root Dependencies:

    bcryptjs: ^2.4.3
    colors: ^1.4.0
    dotenv: ^16.4.5
    express: ^4.21.0
    express-async-handler: ^1.2.0
    jsonwebtoken: ^9.0.2
    mongoose: ^8.6.3
    nodemon: ^3.1.5
    react-scripts: ^4.0.3
    socket.io: ^4.7.5
    socket.io-client: ^4.7.5

3. **Install Frontend Dependencies**:
   ```bash
   cd frontend
   npm install --legacy-peer-deps

 ## List of Frontend Dependencies:

    @chakra-ui/icons: ^2.1.1
    @chakra-ui/react: ^2.8.2
    @emotion/react: ^11.13.3
    @emotion/styled: ^11.13.0
    @testing-library/jest-dom: ^5.17.0
    @testing-library/react: ^13.4.0
    @testing-library/user-event: ^13.5.0
    axios: ^1.7.7
    framer-motion: ^11.5.4
    react: ^18.3.1
    react-dom: ^18.3.1
    react-lottie: ^1.2.4
    react-notification-badge: ^1.5.1
    react-router-dom: ^5.3.4
    react-scripts: 5.0.1
    react-scrollable-feed: ^2.0.2
    react-toastify: ^10.0.5
    socket.io-client: ^4.7.5
    web-vitals: ^2.1.4

    
4. **Set Up Environment Variables**
   Create a .env file in the root directory of the project and add your personal environment variables:
      ```bash
      PORT=5000
      MONGO_URI=*********
      JWT_SECRET=*****
      NODE_ENV=****
      DISABLE_ESLINT_PLUGIN=***

5. **Running the Project**
   To start the server, run the following command in the root directory:
      ```bash
      npm start

   To start the frontend, run:
      ```bash
      cd frontend
      npm start
