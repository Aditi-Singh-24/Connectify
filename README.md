# Connectify

Connectify is a chat application that allows users to authenticate, chat one-on-one, and create group chats. This README provides a step-by-step guide to running the project, installing dependencies, and using its features.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Application](#running-the-application)


## Features
- **User Authentication(signup/login)**: Secure sign-up and login process.
- **My Chats**: View and manage all your chat conversations.
- **Search User**: Quickly find users by name or other identifiers.
- **Single Chat(One-on-one chat)**: Engage in private one-on-one chat sessions.
- **Group Chat functionality**: Create and participate in group chats with multiple users.

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
- Node.js
- Express.js
- MongoDB
- Socket.io
- React.js
- Chakra UI

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
