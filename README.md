# Whispp – Real-Time Chat Application

Whispp is a scalable, secure, and high-performance real-time chat application designed to support fast and seamless messaging between users. Built with the MERN stack and Socket.io, it offers instant message delivery, JWT-based user authentication, and global state management using Zustand. Optimized to handle over 50+ concurrent users with real-time updates and less than 100ms latency.

## Features

### Authentication & Authorization
- JWT-based secure login and session management
- Password hashing using bcrypt for data protection
- Protected routes for authenticated users only

### Real-Time Messaging
- One-on-one and group chat functionality
- Real-time message sending and receiving with Socket.io
- Online/offline user status tracking
- "Message Seen" and "Typing..." indicators

### State Management
- Zustand for lightweight, scalable global state management
- Seamless syncing of user sessions, chat lists, and messages

### Performance & Scalability
- Supports 50+ active concurrent users
- Optimized WebSocket communication ensuring <100ms latency
- Efficient MongoDB queries and data modeling

### Chat System
- Persistent chat history stored in MongoDB
- Group creation and member management
- Message timestamps and auto-scrolling

## Tech Stack

- **Frontend**: React.js, Zustand, CSS Modules
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT, bcrypt
- **Real-Time Engine**: Socket.io
- **Dev Tools**: Postman, Nodemon, VS Code
