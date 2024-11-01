A full-stack e-commerce platform developed with the MERN stack (MongoDB, ExpressJS, React, Node.js), designed to provide a robust online shopping experience. This project demonstrates essential e-commerce features such as user authentication, product management, shopping cart, and payment gateway integration, alongside an admin panel for managing users, products, and orders.

Demo Website
Demo on Heroku
Mirror Link
Project Overview
This project is a comprehensive tutorial for building a fully functional e-commerce website, showcasing both frontend and backend development using the MERN stack. It includes key functionalities like user authentication, product management, and payment processing with responsive design.

Tech Stack
Frontend: HTML5, CSS3, React (with Hooks, Router, Axios), Redux (Store, Reducers, Actions)
Backend: Node.js, Express (API, Body Parser, JWT)
Database: MongoDB with Mongoose
Deployment: Heroku, MongoDB Atlas
Key Features
User Authentication: JWT-based secure login and registration.
Product Management: Product details, ratings, reviews, and add-to-cart functionality.
Shopping Cart: Update, remove products, and process checkout with a payment gateway.
Order Management: Track orders, view order history, and manage order status.
Admin Panel: User, product, and order management with role-based access.
Seller Accounts: Separate seller dashboard with product listings.
Search & Filters: Advanced search and filters for categories, price range, and ratings.
Address Selection on Google Maps: Google Maps API integration for selecting an address during checkout.
Live Chat: Real-time chat with Socket.IO.
Responsive Design: Optimized for mobile and desktop.
Snapshots
![WhatsApp Image 2024-11-01 at 4 35 06 PM](https://github.com/user-attachments/assets/afc8a637-ffa8-40ba-842c-d4367726ee1e)


Setup and Run Locally
Prerequisites
Node.js and MongoDB installed
Steps
Clone the Repository

bash
Copy code
git clone git@github.com:basir/amazona.git
cd amazona
Setup MongoDB

Local MongoDB: Set up a local MongoDB database named amazona and configure the .env file with MONGODB_URL=mongodb://localhost/amazona.
MongoDB Atlas: Configure MONGODB_URL with your Atlas connection string.
Run Backend

bash
Copy code
npm install
npm start
Run Frontend

bash
Copy code
cd frontend
npm install
npm start
Seed Database

Seed users and products by visiting:
Seed Users
Seed Products
Admin Login

Sign in at localhost:3000/signin using the seeded admin credentials.
My Contributions
Backend Development: RESTful API development, MongoDB integration, Express.js routes.
Frontend Development: UI components, Redux for state management, backend API integration.
Feature Implementation: Real-time chat (Socket.IO), Google Maps API for address selection, PayPal payment integration.
Deployment: Fully deployed on Heroku, with MongoDB Atlas as the database.
Impact
This project provides a strong foundation for understanding and implementing e-commerce solutions using the MERN stack, user authentication, and payment gateway integrations, offering developers valuable hands-on experience with modern web technologies.

