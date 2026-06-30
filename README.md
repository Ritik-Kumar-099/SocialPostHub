# SocialPostHub Project

I am learning MERN Stack. This is my first mern project.
This project is a full-stack social posting web app built with React on the frontend and Node.js/Express on the backend. It allows users to create and view posts, upload images, and interact with a simple modern interface. The app connects to a database to store post data and media information. It is a great example of a complete CRUD-based web application with frontend and backend integration.

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
