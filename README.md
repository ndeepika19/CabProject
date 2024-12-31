**Online Cab Booking System**

An online cab booking system built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to book cabs, manage bookings, and view their ride history.

Features

User authentication (signup, login, logout)

Book a cab for immediate or scheduled rides

Real-time cab tracking

Admin panel for managing users and bookings

Integration with a payment gateway

Ride history and receipt generation

**Technology Stack**

**Frontend**:

React.js

Redux (for state management)

Bootstrap/Material-UI (for UI components)

**Backend**:

Node.js

Express.js

MongoDB (for database management)



**Installation**

Prerequisites:

Node.js and npm/yarn installed

MongoDB installed locally or access to a cloud MongoDB database (e.g., MongoDB Atlas)

Steps:

Clone the repository:

git clone https://github.com/your-username/online-cab-booking.git
cd online-cab-booking

Install dependencies for both frontend and backend:

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

Set up environment variables:

Create a .env file in the backend folder with the following keys:

PORT=5000
MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-secret-key>
GOOGLE_MAPS_API_KEY=<your-google-maps-api-key>
PAYMENT_GATEWAY_KEY=<your-payment-gateway-key>

Start the development servers:

# Start backend server
cd backend
npm start

# Start frontend server
cd ../frontend
npm start

Access the application:

Frontend: http://localhost:3000

Backend API: http://localhost:5000

Folder Structure

root
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   └── server.js
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── redux
│   │   └── App.js
└── README.md

API Endpoints

**Authentication**:

POST /api/auth/register - Register a new user

POST /api/auth/login - Login an existing user

**Booking:**

POST /api/bookings - Create a new booking

GET /api/bookings/:id - Get booking details

DELETE /api/bookings/:id - Cancel a booking

**Admin**:

GET /api/admin/users - Manage users

GET /api/admin/bookings - Manage bookings

**Future Enhancements**

Add multi-language support

Implement driver-side app for accepting and managing rides

Add push notifications for real-time updates



**Contact**

For any queries or feedback, feel free to contact:

Name: Deepika

Email: 21wh1a1226@bvrithyderabad.edu.in



Thank you for checking out this project!
