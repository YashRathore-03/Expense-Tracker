# Expense Management System

A comprehensive MERN stack application for tracking personal and business expenses. This full-stack application allows users to create, read, update, and delete expenses, categorize them, and visualize spending patterns.

## Features

- **User Authentication:** Secure signup and login functionality
- **Expense Tracking:** Add, edit, and delete expense records
- **Categorization:** Organize expenses by customizable categories
- **Data Visualization:** View spending patterns with interactive charts
- **Responsive Design:** Works seamlessly on desktop and mobile devices
- **Secure API:** JWT-based authentication for all API endpoints

## Technology Stack

### Frontend
- React.js
- Redux Toolkit for state management
- Chart.js for data visualization
- React Router for navigation
- Axios for API requests
- React Toastify for notifications

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- bcrypt.js for password hashing

## Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB

### Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```

2. Install dependencies for both client and server:

   ```bash
   # Install server dependencies
   cd server
   npm install
   
   # Install client dependencies
   cd ../client
   npm install
   ```

3. Set up environment variables:

   ```bash
   # In the server directory, create a .env file with the following variables
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Run the application:

   ```bash
   # Start the backend server
   cd server
   npm start

   # Start the frontend
   cd ../client
   npm start
   ```

## Deployment

To deploy the application, configure environment variables in the Vercel dashboard for the frontend and use platforms like Heroku, Render, or Railway for the backend.

---

Happy tracking!
