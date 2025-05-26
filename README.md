Book World
A full-featured book review and management application built with the MERN stack (MongoDB, Express, React, Node.js). Users can browse books, leave reviews with star ratings, and manage their favorites. Admins have extended capabilities for adding, editing, and deleting books, as well as managing user data and access.

🚀 Features
✅ User Authentication
Secure user registration and login system

JWT for authorization

Bcrypt for password hashing

📚 Book Listing with Reviews & Ratings
Browse and search for books

Leave comprehensive reviews with star ratings

Read and gain insights from community reviews

👤 User Profile Pages
Personalized profiles to track activity

Manage and curate a list of favorite books

🔄 Advanced Feature
Unique nested commenting system using Depth-First Search (DFS) for efficient comment deletion within the review tree structure

🔐 User Roles & Permissions
Differentiation between user and admin roles

Admin capabilities to add, update, and delete book listings

Manage user data and user roles (excluding a master admin)

🛠️ Technologies Used
🌐 Frontend
React.js

Recoil for State Management

Tailwind CSS

Shadcn UI library

React Hook Form

Tanstack Tables

Lucide-React for icons

🔧 Backend
Node.js

Express.js

MongoDB

Mongoose for MongoDB object modeling

Multer for handling multipart/form-data

CORS for Cross-Origin Resource Sharing

JWT for token-based authentication

Bcrypt for secure password storage

📦 Other Dependencies
Axios

Zod for schema validation

React Router DOM for routing

Cloudinary for image uploads (optional)

📥 Installation Guide
✅ Requirements
Node.js

MongoDB

You can use MongoDB Atlas URL instead of local MongoDB.

⚙️ Configure Environment Variables
Rename .env.example to .env in both backend and frontend directories.

Add the following to the backend .env file:


MONGO_URL=your_mongodb_url

JWT_SECRET=your_jwt_secret

CLOUD_NAME=your_cloudinary_name

CLOUD_API_KEY=your_cloudinary_api_key

CLOUD_API_SECRET=your_cloudinary_api_secret

PORT=5000

Installation

Clone the Repository

git clone https://github.com/CODING-ENJOY154/BOOK.git

cd book-world

Install packages

cd backend

npm install

cd ..

cd frontend

npm install

Start Frontend

Make sure you are in frontend directory:
npm run dev

Start Backend
Make sure you are in backend directory:

node index.js

 localhost:5173 
