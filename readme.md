# Realtime Chat Application (MERN Stack Backend)

### Introduction
This repository contains the Backend for a Realtime Chat Application built using the MERN stack. The app features real-time communication, private and group chats, and other modern messaging functionalities. 

### Feature
- JWT Authentication-Secure user authentication using JSON Web Tokens.
- Private Messaging: Users can engage in **one-on-one** private conversations.
- Group Chat: Create rooms for **group conversations** where users can broadcast messages to multiple people.
- Real-Time Updates: Instant updates for messages, user status (online/offline), read/unread indicators, room join/leave notifications, and more.
- Responsive Design & Theming: Supports responsive web design (RWD) and includes **light/dark** mode themes.

### Technologies
- database - MongoDB
- backend - Express.js & Node.js
- frontend - React.js (with styled-components)
- Real-time messages - Socket.io

### Deploy
- database: MongoDB Atlas
- backend: Render
- frontend: Vercel

### Live Demo


### Testing Account
username: Prachi  
password: Prachi888  

 

### How to use
1. Clone the repo
    ```
    git clone https://github.com/prachi888/ConvoMate-frontend.git
    ```
2. Enter the directory
    ```
    cd realchat-backend
    ```
3. Install dependencies
    ```
    yarn install
    ```
4. Change .env.example file
   - change file name to .env
   - go to [MongoDB Atlas](https://www.mongodb.com/atlas/database) to create a cluster and change the MONGO_URI  
   - Set the CLIENT_URL to your local frontend address (e.g., http://localhost:3000 if the frontend runs on port 3000).
   - Generate random secrets for ACCESS_TOKEN_SECRET, REFRESH_TOKEN_SECRET, and COOKIE_SIGNATURE.

5. Run the app   
    ```
    yarn dev
    ```
    Once you see the message App is listening on port YOUR_PORT, DB connection Success, you can proceed to run the frontend.


