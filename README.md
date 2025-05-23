# Chat Application

A real-time chat application built with React (frontend) and Node.js/Express (backend).

## Features

- User authentication (signup, login, logout)
- Real-time messaging
- Modern UI with React
- Secure backend with Express.js

## Tech Stack

### Frontend
- React
- Vite
- Socket.io-client

### Backend
- Node.js
- Express.js
- MongoDB
- Socket.io
- JWT Authentication

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- Git

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file with the following variables:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/chat-app
   JWT_SECRET=your-secret-key
   ```
4. Start the server:
   ```bash
   npm run dev
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Contributing

Feel free to submit issues and pull requests.

## License

MIT 