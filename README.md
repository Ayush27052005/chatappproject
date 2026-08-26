# Ayush Connect

Ayush Connect is a real-time chat application built with React, Express, MongoDB, and Socket.IO.

**Project owner:** Ayush Negi  
**Institution:** Graphic Era Hill University  
**Program:** Codec Technology Internship, Project 2

## Features

- User registration and login
- Profile avatar selection
- Online user list
- Real-time one-to-one messaging with Socket.IO
- MongoDB-backed users and messages

## Technologies

- React 17
- Node.js and Express
- MongoDB with Mongoose
- Socket.IO
- Axios

## Requirements

- Node.js and npm
- MongoDB Community Server running locally, or a MongoDB Atlas connection

## Setup

The frontend and backend are separate npm projects. Install each one from its own directory:

```powershell
cd public
npm install

cd ..\server
npm install
```

Create or update `server/.env`:

```env
PORT=5000
MONGO_URL=mongodb://127.0.0.1:27017/chatapp
```

For MongoDB Atlas, replace `MONGO_URL` with your own connection string. Keep `.env` private and never commit database credentials.

## Run Locally

Open two terminals from the project root.

Terminal 1, backend:

```powershell
cd server
npm start
```

Terminal 2, frontend:

```powershell
cd public
npm start
```

Open the URL printed by React, usually `http://localhost:3000`. If that port is busy, React will use another port such as `http://localhost:3001`.

## Project Structure

```text
public/   React frontend
server/   Express and Socket.IO backend
```

## Internship Project

This application was developed by Ayush Negi from Graphic Era Hill University as part of the Codec Technology Internship, Project 2.
