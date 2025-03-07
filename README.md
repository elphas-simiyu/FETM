# Task Manager (MERN Stack)

## Project Overview
The **Task Manager** is a full-stack web application built using the **MERN stack (MongoDB, Express.js, React, Node.js)**. It allows users to **create, read, update, and delete (CRUD)** tasks efficiently.

## Features
- User-friendly task management
- CRUD operations (Create, Read, Update, Delete)
- Task attributes: **Title, Description, Status, Due Date**
- RESTful API integration
- Responsive UI using **CSS**
- Frontend and Backend connection using **Axios**

## Folder Structure
```
mern-task-manager/
│── backend/
│   ├── models/        # Mongoose models
│   ├── routes/        # API routes
│   ├── controllers/   # Business logic
│   ├── config/        # Database configurations
│   ├── server.js      # Express.js server
│   ├── .env           # Environment variables
│── frontend/
│   ├── src/
│   ├── components/    # React components
│   ├── pages/         # Page-based components
│   ├── App.js         # Root component
│   ├── index.js       # React entry point
│── README.md
```

## Installation & Setup
### 1. Clone the Repository
```bash
git clone https://github.com/your-username/mern-task-manager.git
cd mern-task-manager
```

### 2. Backend Setup
```bash
cd backend
npm install
```
- Create a **.env** file and add the following:
```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```
- Run the server:
```bash
npm start
```

### 3. Frontend Setup
```bash
cd frontend
npm install
```
- Start the frontend server:
```bash
npm start
```

## API Endpoints
| Method | Endpoint      | Description |
|--------|--------------|-------------|
| POST   | `/tasks`     | Create a new task |
| GET    | `/tasks`     | Retrieve all tasks |
| PUT    | `/tasks/:id` | Update a task by ID |
| DELETE | `/tasks/:id` | Delete a task by ID |

## Deployment
### Backend (Render, Heroku, or other services)
- Deploy your backend to **Render**:
```bash
git push render main
```

### Frontend (Vercel, Netlify)
- Deploy the frontend to **Vercel**:
```bash
vercel
```

## Contributing
Feel free to **fork** this repository and submit a **pull request** with improvements.

## License
This project is licensed under the **MIT License**.


