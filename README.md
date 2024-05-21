# DevVani-ChatApp
# ChatApp

# ChatApp

---

## Overview

DevVani ChatApp is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) to facilitate real-time messaging between users. This repository contains both the frontend and backend code for the application.

## 🚀 Features

- **User Authentication:** Users can sign up, log in, and log out securely.
- **Real-time Messaging:** Users can send and receive messages instantly in real-time.
- **User Status:** Online/offline status indicators for users.
- **User Profiles:** View and edit user profiles.
- **Responsive Design:** The frontend is designed to be responsive and accessible on various devices.

## 💻 Technologies Used

- **Frontend:**
  - React.js
  - Redux (for state management)
  - Axios (for HTTP requests)
  - Socket.IO (for real-time communication)
  - Material-UI (for UI components)

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB (with Mongoose ORM)
  - Socket.IO (for real-time communication)
  - JWT (JSON Web Tokens) for authentication

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VasudevJaiswal/DevVani-ChatApp
   # Setting Up ChatApp


2. **Navigate to the backend directory:**
    ```bash
    cd chatapp/backend
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Create a `.env` file in the backend directory and add the following environment variables:**
    ```makefile
    PORT=5000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5. **Start the server:**
    ```bash
    npm start
    ```

## Setting Up the Frontend

1. **Navigate to the frontend directory:**
    ```bash
    cd chatapp/frontend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Create a `.env` file in the frontend directory and add the following environment variables:**
    ```arduino
    REACT_APP_BACKEND_URL=http://localhost:5000
    ```

4. **Start the development server:**
    ```bash
    npm start
    ```

Now you can access the ChatApp frontend by opening your browser and going to [http://localhost:3000](http://localhost:3000).

Make sure the backend server is running as well to enable communication between the frontend and backend.

---
