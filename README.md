MERN E-Commerce Platform
A full-stack e-commerce website developed using the MERN stack (MongoDB, ExpressJS, React, Node.js), modeled after the functionality of major online retailers. This project demonstrates an end-to-end solution for creating, managing, and deploying an e-commerce platform with extensive features like user authentication, product management, shopping cart, payment gateway integration, and more.

Demo Website
Heroku Demo
Heroku Mirror
Project Overview
This project is a comprehensive tutorial that guides you through building a fully functional e-commerce website, covering both frontend and backend development using the MERN stack. It demonstrates core functionalities such as user authentication, product management, order processing, payment integration, and more, all with a responsive design.

Tech Stack
Frontend
HTML5 and CSS3
React (Components, Props, Events, Hooks, Router, Axios)
Redux (Store, Reducers, Actions)
Backend
Node.js & Express (API, Body Parser, File Upload, JWT)
Database
MongoDB (Mongoose, Aggregation)
Development Tools
ESLint, Babel, Git, GitHub
Deployment
Heroku
Key Features
User Authentication: Secure login and registration with JWT-based authentication.
Product Management: View product details, rate and review, add to cart, and more.
Shopping Cart: Add, update, and remove products, checkout, and apply a payment gateway.
Order Management: Track orders, view order history, and update order status.
Admin Panel: Manage users, products, and orders with roles and permissions.
Seller Accounts: Separate seller accounts with their unique dashboard and product listings.
Search and Filters: Advanced search with filters for categories, price range, and ratings.
Address Selection on Google Maps: Integrate Google Maps API for address selection during checkout.
Live Chat: Real-time chat feature with Socket.IO.
Responsive Design: Mobile-friendly and desktop-compatible interface.
Snapshots
Below are some screenshots demonstrating the main sections of the application:

Home Screen

Product Details

Shopping Cart

Admin Dashboard

Seller Dashboard

Order Summary

Setup and Run Locally
Prerequisites
Install Node.js and MongoDB
Steps
Clone the Repository

bash
Copy code
git clone git@github.com:basir/amazona.git
cd amazona
Setup MongoDB

Local MongoDB:
Install MongoDB locally and set up a database named amazona.
Create an .env file in the root folder and set MONGODB_URL=mongodb://localhost/amazona.
Atlas Cloud MongoDB:
Create a database on MongoDB Atlas and set the MONGODB_URL with your connection string.
Run Backend

bash
Copy code
npm install
npm start
Run Frontend

bash
Copy code
# Open a new terminal
cd frontend
npm install
npm start
Seed Database

Seed users and products by navigating to:
Seed Users
Seed Products
Admin credentials will be displayed for login.
Admin Login

Access the admin panel at localhost:3000/signin using the seeded admin credentials.
My Contributions
Throughout this project, I contributed in the following areas:

Backend Development: Built RESTful APIs, integrated MongoDB with Mongoose, and set up Express.js routes for handling user authentication, product management, and order processing.
Frontend Development: Created responsive UI components using React, integrated Redux for state management, and connected the frontend with backend APIs.
Feature Implementation: Added real-time live chat with Socket.IO, Google Maps API for address selection, and PayPal integration for payment processing.
Deployment: Deployed the application on Heroku with MongoDB Atlas as the database, enabling a fully functional live demo.
Impact
This project serves as a strong foundation for understanding and implementing a complete e-commerce solution using modern web technologies. It covers a broad range of essential e-commerce functionalities and is a valuable resource for developers looking to gain hands-on experience with the MERN stack, user authentication, real-time communication, and payment gateway integrations.
