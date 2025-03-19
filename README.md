# MERN Stack Authentication System

A complete Login/Signup system built using MongoDB, Express.js, React.js, and Node.js with JWT authentication and deployment.

## Features
- User registration and login with secure password hashing using `bcrypt`.
- JSON Web Token (JWT) authentication for user sessions.
- Robust error handling and form validation for improved user experience.
- Responsive UI built with React for seamless interaction.
- RESTful API integration connecting frontend and backend.
- Deployment instructions for hosting the app on Vercel.

## Technologies Used
- **MongoDB** - Database for storing user information.
- **Express.js** - Backend framework for API routes and server logic.
- **React.js** - Frontend library for building the user interface.
- **Node.js** - Runtime environment for server-side logic.
- **JWT (JSON Web Tokens)** - For secure user authentication.
- **bcrypt** - For password hashing.
- **Vercel** - For deploying the final project.

## Installation
1. Clone the repository:
```bash
git clone <repository_link>
cd <project_folder>
```

2. Install dependencies:
```bash
npm install
cd client
npm install
```

3. Setup `.env` file for backend (in the root folder):
```
MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your Secret Key>
PORT=5000
```

4. Setup `.env` file for frontend (inside `/client` folder):
```
REACT_APP_API_URL=http://localhost:5000
```

5. Run the backend:
```bash
npm start
```

6. Run the frontend:
```bash
cd client
npm start
```

## API Endpoints
### Auth Routes
- **POST** `/api/auth/register` - Register a new user
- **POST** `/api/auth/login` - Login an existing user
- **GET** `/api/auth/profile` - Fetch user profile (requires JWT token)

## Deployment Instructions
1. Create a Vercel account and connect your GitHub repository.
2. Set environment variables in Vercel dashboard.
3. Deploy the frontend and backend separately or together based on your setup.


