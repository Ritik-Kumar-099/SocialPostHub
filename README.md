# 04 Project

This project contains a full-stack web application with a React frontend and an Express/Node.js backend.

## Project Structure

- frontend/: Vite + React application
- backend/: Express server and API

## Features

- Create and view posts
- Upload images through the backend
- React-based UI with routing

## Setup

### 1. Install backend dependencies

```bash
cd backend
npm install
```

### 2. Install frontend dependencies

```bash
cd ../frontend
npm install
```

### 3. Run the app

Start the backend:

```bash
cd backend
node server.js
```

Start the frontend:

```bash
cd frontend
npm run dev
```

## Environment Variables

Create a `.env` file in the backend folder and add your MongoDB connection string and other required values.

## Deployment Notes

- The frontend can be deployed on Vercel or Netlify.
- The backend can be deployed on Render, Railway, or similar hosting platforms.
