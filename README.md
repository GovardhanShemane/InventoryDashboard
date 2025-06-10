# MERN Inventory Dashboard

A full-stack Inventory Management System built with the MERN stack (MongoDB, Express.js, React, Node.js) featuring Firebase + JWT authentication and CRUD operations.

![Dashboard Preview](https://via.placeholder.com/800x400?text=Inventory+Dashboard+Preview) *(Replace with actual screenshot)*

## Features

- 🔐 **Dual Authentication**  
  - Firebase Google Login  
  - JWT-based Email/Password Login  
- 📦 **Inventory CRUD Operations**  
  - Add, Edit, Delete products (no page refresh)  
  - Real-time product list with filters (Category, Price)  
- 🎨 **Responsive UI**  
  - Dynamic modals for forms  
  - Toast notifications for actions  
- 🚀 **Deployment Ready**  
  - Backend: Render/Heroku  
  - Frontend: Vercel/Netlify  

## Tech Stack

| Frontend               | Backend           | Database  | Auth               |
|------------------------|-------------------|-----------|--------------------|
| React.js               | Node.js           | MongoDB   | Firebase Auth      |
| Redux/Toolkit (or Context API) | Express.js    | Mongoose  | JWT                |
| Tailwind/MUI           | REST API          |           |                    |

## Setup Instructions

### 1. Prerequisites
- Node.js (v16+)  
- MongoDB Atlas (or local)  
- Firebase Project (for Google Auth)  

### 2. Backend Setup
```bash
cd backend
npm install
# Create a `.env` file with:
# MONGO_URI=your_mongodb_uri
# JWT_SECRET=your_jwt_secret
# FIREBASE_CONFIG=your_firebase_config
npm start
