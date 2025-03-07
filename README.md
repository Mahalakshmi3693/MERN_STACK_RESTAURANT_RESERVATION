# MERN Stack Restaurant Reservation System

## Description
The **MERN Stack Restaurant Reservation System** is a full-stack web application that allows users to browse restaurant availability, make reservations, and manage bookings. The system provides an intuitive interface for customers and an admin panel for restaurant owners to handle reservations efficiently.

## Features
- User authentication and authorization
- View available time slots and make reservations
- Admin dashboard for managing bookings
- Real-time updates and notifications
- Secure database storage for reservations and user data

## Technologies Used
### **Frontend:**
- **React.js** – Frontend framework for building the user interface
- **React Router** – For navigation between pages
- **Axios** – For handling API requests
- **Tailwind CSS** – For styling and responsiveness

### **Backend:**
- **Node.js & Express.js** – Backend framework for handling API requests
- **MongoDB** – Database for storing reservation data
- **Mongoose** – ODM for interacting with MongoDB
- **JWT Authentication** – For secure login and user authentication

## Installation & Setup
### **1. Clone the Repository**
```sh
   git clone https://github.com/yourusername/mern-restaurant-reservation.git
   cd mern-restaurant-reservation
```

### **2. Set Up the Backend**
```sh
   cd backend
   npm install
   npm start
```

### **3. Set Up the Frontend**
```sh
   cd frontend
   npm install
   npm start
```

### **4. Configure Environment Variables**
- Create a `.env` file in the `backend` directory and add:
```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
```

## Usage
- Open the frontend at `http://localhost:3000`
- Users can sign up, log in, and make reservations
- Admins can manage and update reservations

## Conclusion
This **MERN Stack Restaurant Reservation System** provides a seamless way for customers to book tables while allowing restaurant owners to manage bookings efficiently. It can be extended with additional features like online payments and SMS/email notifications.
