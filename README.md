🚀 Smart Analytics SaaS Dashboard

A production-style full stack analytics dashboard built with secure authentication, role-based access control, and scalable backend architecture.

Designed to simulate a real-world SaaS application with complete frontend-backend integration.

📌 Overview

This project demonstrates how a secure SaaS dashboard works in a production environment:

🔐 JWT-based Authentication

👤 Role-Based Access (Admin / User)

🛡 Protected Routes & Middleware

🔑 Change Password & Delete Account

📊 Dynamic Dashboard Rendering

🌐 RESTful API Architecture

🗄 MongoDB Database Integration

🏗 Architecture

Client (React + Tailwind)
->
Express REST API
->
Middleware (Auth + Role Protection)
->
Controllers
->
MongoDB Database

Backend is structured using:

routes/

middleware/

controllers/

models/

✨ Features
🔐 Authentication & Security

JWT token-based authentication

Secure password hashing using bcrypt

Protected routes using custom auth middleware

Role-based access control (Admin/User)

Change password functionality

Delete account feature

📊 Dashboard

Dynamic rendering based on user role

Real-time profile updates

Secure data fetching from backend

Structured and scalable API integration

🏗 Backend Engineering

Clean MVC-style architecture

RESTful API design

Middleware-based authorization

Proper error handling & response structure

🛠 Tech Stack
Frontend

React.js

Tailwind CSS

Backend

Node.js

Express.js

MongoDB

JWT (jsonwebtoken)

bcrypt
