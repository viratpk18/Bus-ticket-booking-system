# Bus Ticket Booking System

This project is a **Bus Ticket Booking System** built using the MERN stack (MongoDB, Express.js, React, Node.js). The system provides a platform for users to book bus tickets, view schedules, and manage bookings efficiently. The frontend uses **React** with **Tailwind CSS**, and the backend is powered by **Node.js** and **Express.js** with **MongoDB** as the database.

## Features
- User authentication (login/register)
- Bus schedule viewing
- Booking management
- Responsive user interface
- Secure API endpoints

## Project Structure

```
Bus-booking/
├── backend/               # Backend server code (Node.js, Express)
├── src/                   # Frontend source code (React)
├── .env                   # Environment variables (not included in repo)
├── package.json           # Dependencies and project scripts
├── tailwind.config.js     # Tailwind CSS configuration
├── vite.config.ts         # Vite bundler configuration
├── tsconfig.json          # TypeScript configuration
└── .gitignore             # Git ignore rules
```

## Prerequisites
Ensure you have the following installed:

- **Node.js** (v14 or higher)
- **npm** (v6 or higher) or **yarn**
- **MongoDB**

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/viratpk18/bus-ticket-booking-system.git
   ```

2. **Install dependencies:**
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the root and backend directories.
   - Add the following variables:
     ```env
     # Backend .env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

## Running the Project

1. **Start the backend server:**
   ```bash
   cd backend
   npm start
   ```

2. **Start the frontend development server:**
   ```bash
   cd ../
   npm run dev
   ```

3. **Access the application:**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000`

## Scripts

- **`npm run dev`**: Starts the development server.
- **`npm start`**: Runs the production build.
- **`npm run build`**: Builds the application for production.

## Technologies Used

### Frontend:
- React
- TypeScript
- Tailwind CSS
- Vite

### Backend:
- Node.js
- Express.js
- MongoDB

## Deployment

1. Build the frontend:
   ```bash
   npm run build
   ```

2. Deploy the backend to your preferred platform (Heroku, Vercel, AWS, etc.).

3. Serve the frontend build using a static file server or integrate it with your backend.

## Contribution
Feel free to fork this repository and submit pull requests to improve the project.

## Contact
For any questions or issues, please contact [praveenkumar2k4.t@gmail.com].

