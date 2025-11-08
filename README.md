🛒 Mini MERN E-commerce Project

A simple full-stack E-commerce web application built using the MERN stack (MongoDB, Express.js, React, Node.js).
This project demonstrates authentication, product management, cart functionality, and order checkout — ideal for learning and practicing MERN fundamentals.

🚀 Features

✅ User registration & login (JWT Authentication)

✅ Add, edit, delete products (Admin only)

✅ Product listing & details page

✅ Shopping cart (add/remove items)

✅ Checkout & order summary

✅ RESTful API with Express.js

✅ MongoDB database with Mongoose

✅ React frontend with Context API / Redux (choose one)

✅ Protected routes (Frontend + Backend)

🏗️ Tech Stack
Layer	Technology
Frontend	React.js, Axios, React Router
Backend	Node.js, Express.js
Database	MongoDB with Mongoose
Authentication	JWT (JSON Web Token)
Styling	Tailwind CSS / Bootstrap (your choice)
Dev Tools	Nodemon, dotenv, concurrently
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/<your-username>/mini-mern-ecommerce-project.git
cd mini-mern-ecommerce-project

2. Install dependencies
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install

3. Set up environment variables

Create a .env file inside the backend folder and add the following:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NODE_ENV=development

4. Run the app
# Run backend (in one terminal)
cd backend
npm run dev

# Run frontend (in another terminal)
cd frontend
npm start


Or use concurrently (if configured in root package.json):

npm run dev

📁 Folder Structure
mini-mern-ecommerce-project/
│
├── backend/
│   ├── server.js
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── middleware/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/ or redux/
│   │   └── App.js
│   └── public/
│
└── README.md
