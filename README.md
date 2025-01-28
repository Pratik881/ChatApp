# Real-Time Chat Application

A real-time chat application built with React.js and Express.js, enabling users to join different chat rooms and communicate in real-time using Socket.IO.

## Features

- Real-time messaging
- Multiple chat rooms
- Auto-scrolling chat interface
- User join/leave notifications

## Tech Stack

### Frontend
- React.js
- Socket.IO Client
- react-scroll-to-bottom

### Backend
- Express.js
- Socket.IO
- Node.js
- CORS

## Prerequisites

Before running this application, make sure you have the following installed:
- Node.js (v12 or higher)
- npm (Node Package Manager)

## Installation

### Client Setup

1. Navigate to the client directory:
```bash
cd clients
```

2. Install dependencies:
```bash
npm install
```

3. Start the client:
```bash
npm start
```

The client will run on `http://localhost:3000`

### Server Setup

1. Navigate to the server directory:
```bash
cd server
```

2. Install dependencies:
```bash
npm install
```

3. Start the server:
```bash
npm start
```

The server will start using nodemon for development purposes.

## Project Structure

```
├── client/                 # React frontend
│   ├── public/
│   ├── src/
│   └── package.json
│
├── server/                 # Express backend
│   ├── index.js           # Server entry point
│   └── package.json
```

## Scripts

### Client
- `npm start`: Runs the app in development mode
- `npm test`: Launches the test runner
- `npm run build`: Builds the app for production
- `npm run eject`: Ejects from create-react-app

### Server
- `npm start`: Starts the server using nodemon

