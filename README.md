🍔 Project Overview

This is a full-stack Food Delivery Web Application developed using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The application enables users to browse restaurants, explore menus, add food items to the cart, apply coupons, securely place orders, and complete payments.

The project follows a modern client-server architecture with a React frontend and a RESTful Express backend connected to MongoDB Atlas.

🚀 Features
👤 User Features
User Registration & Login
JWT Authentication
Secure Password Hashing
Browse Restaurants
View Restaurant Menus
Search Food Items
Filter Restaurants
Add/Remove Cart Items
Update Cart Quantity
Apply Coupon Codes
Checkout
Online Payment using Stripe
View Orders
AI Chat Assistant Integration
Responsive UI
🍽 Restaurant Features
Restaurant Listing
Restaurant Details
Restaurant Images
Ratings & Reviews
Location Information
Category-wise Menu Display
🍕 Food Item Features
Food Images
Price
Description
Ratings
Reviews
Stock Availability
🛒 Cart Features
Add to Cart
Remove from Cart
Quantity Update
Total Price Calculation
Restaurant Validation
💳 Payment Features
Stripe Payment Gateway
Secure Checkout
Order Confirmation
🤖 AI Assistant
AI-powered food recommendation
Restaurant suggestions
Customer assistance
🛠 Tech Stack
Frontend
React.js
Redux Toolkit
React Router DOM
Axios
Bootstrap
CSS
Backend
Node.js
Express.js
MongoDB
Mongoose
JWT Authentication
bcryptjs
Express Validator
Stripe API
Database

MongoDB Atlas

Collections:

Restaurants
FoodItems
Menus
Users
Orders
Coupons
Cart

⚙ Installation
1. Clone Repository
git clone https://github.com/yourusername/FoodProjectApp.git
2. Move into project
cd FoodProjectApp
3. Install Backend Dependencies
cd backend
npm install
4. Install Frontend Dependencies
cd ../frontend
npm install
Environment Variables

Create a config.env file inside

backend/config/

Add the following variables:

PORT=8080

NODE_ENV=DEVELOPMENT

DB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

JWT_EXPIRE=7d

COOKIE_EXPIRE=7

STRIPE_SECRET_KEY=your_stripe_secret_key

STRIPE_API_KEY=your_stripe_publishable_key

OPENAI_API_KEY=your_openai_api_key
▶ Running the Backend
cd backend
npm start

Backend runs on

http://localhost:8080
▶ Running the Frontend
cd frontend
npm run dev

Frontend runs on

http://localhost:5173
API Endpoints
Authentication
POST   /api/v1/users/register
POST   /api/v1/users/login
GET    /api/v1/users/logout
GET    /api/v1/users/me
Restaurants
GET    /api/v1/eats/stores
GET    /api/v1/eats/stores/:id
GET    /api/v1/eats/stores/:id/menus
Food Items
GET    /api/v1/eats
GET    /api/v1/eats/:id
Cart
GET
POST
PUT
DELETE

/api/v1/eats/cart
Orders
POST /api/v1/eats/orders
GET  /api/v1/eats/orders
Coupons
GET /api/v1/coupon
Payments
POST /api/v1/payment/process
AI Assistant
POST /api/v1/ai/chat
Database Collections
restaurants

fooditems

menus

users

orders

cart

coupons
Screenshots

You can include screenshots here.

Home Page

Restaurant Page

Menu Page

Cart Page

Checkout Page

Login Page
Future Enhancements
Order Tracking
Live Delivery Status
Google Maps Integration
Razorpay Integration
Wishlist
Notifications
Restaurant Dashboard
Admin Dashboard
Recommendation System
Progressive Web App (PWA)
Learning Outcomes
MERN Stack Development
REST API Design
MongoDB Data Modeling
JWT Authentication
Redux State Management
Payment Gateway Integration
Full Stack Deployment
API Testing
Responsive Web Design
