# Doctor Appointment System

This is a full-stack doctor appointment booking system built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## Prerequisites

Before starting, ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

## Getting Started

### Frontend Setup

1. Navigate to the project directory:
   ```sh
   cd client
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```

#### Frontend Dependencies
```json
{
  "name": "client",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "lint": "eslint .",
    "preview": "vite preview"
  },
  "dependencies": {
    "@tailwindcss/vite": "^4.0.5",
    "axios": "^1.7.9",
    "react": "^19.0.0",
    "react-dom": "^19.0.0",
    "react-icons": "^5.4.0",
    "react-router-dom": "^6.29.0"
  },
  "devDependencies": {
    "@eslint/js": "^9.19.0",
    "@types/react": "^19.0.8",
    "@types/react-dom": "^19.0.3",
    "@vitejs/plugin-react": "^4.3.4",
    "autoprefixer": "^10.4.20",
    "eslint": "^9.19.0",
    "eslint-plugin-react": "^7.37.4",
    "eslint-plugin-react-hooks": "^5.0.0",
    "eslint-plugin-react-refresh": "^0.4.18",
    "globals": "^15.14.0",
    "postcss": "^8.5.1",
    "tailwindcss": "^4.0.5",
    "vite": "^6.1.0"
  }
}
```

---

### Backend Setup

1. Navigate to the backend directory:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the backend server:
   ```sh
   npm run dev
   ```

#### Backend Dependencies
```json
{
  "name": "doc-appoinment",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "server.js",
    "dev": "nodemon server.js"
  },
  "dependencies": {
    "bcrypt": "^5.1.1",
    "body-parser": "^1.20.3",
    "cookie-parser": "^1.4.7",
    "cors": "^2.8.5",
    "dotenv": "^16.4.7",
    "express": "^4.21.2",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.10.0",
    "nodemon": "^3.1.9",
    "validator": "^13.12.0"
  }
}
```

## Database Setup

1. Install MongoDB and ensure it is running.
2. Create a `.env` file in the backend directory and configure your MongoDB connection:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

## Running the Project

1. Start the backend:
   ```sh
   cd backend && npm run dev
   ```
2. Start the frontend:
   ```sh
   cd client && npm run dev
   ```
3. Open `http://localhost:5173` in your browser to view the app.

4. Video Demonstration

## Video Demonstration

See how the web application works by watching this video:

[Watch Video](https://drive.google.com/file/d/1sytPVCERXu9SBODMJfPgQVT2URzGz8HF/view?usp=sharing)




