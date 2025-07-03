# MERN To-Do App

A full-stack task management application designed to enhance productivity through simplicity. Built with the **MERN stack**, this app empowers users to efficiently create, update, filter, and manage their daily tasks with a seamless user experience.

---

## 🚀 Deployment Links

- **Frontend (Vercel)**: [`https://to-do-frontend-chi.vercel.app/login`](https://to-do-frontend-chi.vercel.app/login)  
  _Access the full-featured client interface. Sign up, log in, and manage your tasks effortlessly._

- **Backend (Render)**: [`https://todobackend-y0yl.onrender.com`](https://todobackend-y0yl.onrender.com)  
  _Handles all authentication and task-related API operations._


---

## ✨ Features

- Add tasks with default status and priority  
- View all tasks with a clean and responsive UI  
- Update task status (Pending or Completed)  
- Change task priority (Low, Medium, High)  
- Delete tasks with a single click  
- Filter tasks by status and priority  
- Secure login and registration using JWT authentication  
- Logout with redirection to login screen  

---

## 💡 Why This App?

Over **80% of people** struggle to complete their daily tasks — not because they lack motivation, but because the tools they use are either **overwhelming or underwhelming**.  
This app offers a distraction-free, easy-to-use alternative built for:

- Students juggling assignments and classes  
- Professionals balancing meetings and deliverables  
- Anyone wanting structure in a busy life  

---

## 🛠️ Tech Stack

| Layer      | Technology                            |
|------------|---------------------------------------|
| Frontend   | React, Tailwind CSS, React Router DOM |
| Backend    | Node.js, Express.js                   |
| Database   | MongoDB with Mongoose                 |
| Auth       | JWT, bcrypt                           |
| Deployment | Vercel (Frontend), Render (Backend)   |

---

## 📁 Project Structure

```bash
mern-todo-app/
├── frontend/   # React client with routing and task UI
├── backend/    # Express server with auth and task logic
└── README.md   # Project overview and instructions
```
GitHub Repositories
- Frontend Repository: [https://github.com/Dhrubarati/ToDoFrontend](https://github.com/Dhrubarati/ToDoFrontend)

- Backend Repository: [https://github.com/Dhrubarati/ToDoBackend](https://github.com/Dhrubarati/ToDoBackend)

---
## 💻 Local Development Setup 
Prerequisites
- Node.js and npm

- A MongoDB connection string (e.g., from MongoDB Atlas)

## Backend Setup
```bash
cd backend
npm install
touch .env
```
nside .env:
```bash
MONGOURL=your_mongodb_connection_string
PORT=8080
```
Start the backend server:
```bash
npm start
```
## Frontend Setup
```bash
cd frontend
npm install
npm start
```
The app will now be running locally at: http://localhost:3000

---
## 🔐 Authentication Overview

- Passwords are hashed using `bcrypt`
- JWT tokens are issued during login
- Tokens are securely stored in `localStorage`
- All task-related API routes are protected with middleware

---

## 🧠 Code Highlights

### Frontend

- `useState`, `useEffect` for task state management
- React Router for navigation between login, signup, and protected home routes
- Real-time updates using Fetch API calls

### Backend

- RESTful APIs with Express
- Mongoose models for users and tasks
- Middleware for validating JWT tokens and securing routes

---

## 👤 Author

**Dhrubarati Sur**  
*B.Tech CSE · KIIT · MERN Stack Developer*  
[GitHub](https://github.com/Dhrubarati) • [LinkedIn](https://www.linkedin.com/in/dhrubarati-sur)

---

## 📢 Final Note

> *"If you’re ready to stop feeling busy and start feeling balanced, try the app today. Let’s make to-dos less about pressure — and more about progress."*

