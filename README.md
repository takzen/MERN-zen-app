# Fullstack Workout Tracker

## Overview
This project is a fullstack application for tracking workouts. It includes a **backend** built with **Node.js**, **Express**, and **MongoDB**, as well as a **frontend** developed with **React**. The app allows users to create, view, update, and delete workout entries, offering a seamless and efficient way to manage workout routines.

---

## Features
### Backend:
- **RESTful API**: Endpoints for managing workout entries (CRUD operations).
- **Database Integration**: Uses MongoDB for data persistence.
- **Environment Configuration**: Leverages `dotenv` for managing environment variables.

### Frontend:
- **React Context API**: Manages global state for workouts across the application.
- **Responsive Design**: Optimized for both desktop and mobile usage.
- **Clean UI**: Built with React components for modularity and reusability.

---

## Technologies Used
### Backend:
- **Node.js**: Runtime for building server-side applications.
- **Express.js**: Lightweight framework for building RESTful APIs.
- **MongoDB**: NoSQL database for storing workout data.
- **Mongoose**: ODM library for MongoDB.

### Frontend:
- **React**: Frontend library for building user interfaces.
- **React Context API**: Simplifies state management.

---

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- MongoDB instance (local or cloud-based)

### Backend Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `backend` directory and add the following:
   ```env
   MONGO_URI=<your-mongodb-connection-string>
   PORT=4000
   ```
4. Start the server:
   ```bash
   npm run dev
   ```
   The server will run on `http://localhost:4000`.

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React development server:
   ```bash
   npm start
   ```
   The frontend will run on `http://localhost:3000`.

---

## Project Structure
### Backend:
- `server.js`: Main entry point for the server.
- `routes/`: Contains the API routes.
- `models/`: Defines the MongoDB schemas.

### Frontend:
- `App.js`: Main React component.
- `context/WorkoutsContext.js`: Provides global state for workouts.
- `components/`: Reusable React components.

---

## Scripts
### Backend:
- `npm run start`: Starts the production server.
- `npm run dev`: Starts the development server using Nodemon.

### Frontend:
- `npm start`: Starts the React development server.

---

## License
This project is licensed under the [MIT License](LICENSE).
