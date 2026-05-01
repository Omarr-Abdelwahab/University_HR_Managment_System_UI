HR Management System

A full-stack HR management platform for handling employees, attendance, and core HR operations in a centralized system.

🚀 Overview

The HR Management System is a web application designed to digitize and streamline HR workflows such as employee management, authentication, and attendance tracking. It provides structured, role-based access to HR data through REST APIs.

🛠 Tech Stack

Frontend: React

Backend: Node.js, Express

Database: SQL Server

API: RESTful architecture

✨ Features
Employee management (create, update, delete, and view employee records)
Secure authentication system
Role-based access control (admin / user separation)
Attendance tracking and HR workflow handling
REST APIs for frontend-backend communication
Structured relational database design using SQL Server
⚙️ System Design

Frontend handles user interface and interactions

Backend manages business logic, authentication, and API routes

SQL Server stores structured HR data (employees, roles, attendance)

REST APIs connect frontend and backend for dynamic data flow

🚀 Setup Instructions
Clone Repository
git clone <repository-url>
cd hr-system
Frontend Setup
cd frontend
npm install
npm run dev
Backend Setup
cd backend
npm install
npm run dev
📌 Notes
Ensure SQL Server is running locally or remotely before starting backend
Configure database connection in environment variables
Backend must be running for full system functionality
👀 Preview
Employee dashboard for HR management
Secure login system with role-based access
Admin controls for managing HR operations
Responsive UI for daily workflow usage
