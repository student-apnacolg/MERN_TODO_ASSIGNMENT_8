### Implementing To-Do List Backend APIs  & Integrating Frontend

M: MongoDB (Database)
E: ExpressJS (Backend)
R: ReactJS (Frontend)
N: NodeJs (Backend)

## Backend

npm init
npm i express
npm i --save-dev nodemon(as a dev dependency)
npm i -g nodemon(global)
npm i dotenv

npm run dev

npm i mongoose


## API Endpoints

GET     /list         --> Get all the taks.
Post    /list         --> Create a New Task.
GET     /list/:id     --> Get a Single task by ID.
PATCH     /list/:id     --> Update a single task by ID.
DELETE  /list/:id     --> Delete a single task by ID.

## Tech Stack

- Node.js
- Express
- MongoDB + Mongoose
- dotenv
- CORS


## Live API

- **Base URL**: [`https://todo-backend-evep.onrender.com`](https://todo-backend-evep.onrender.com)
- Health Check: [`/`](https://todo-backend-evep.onrender.com/)
- API Routes: `/api/tasks`


## Frontend

## Frontend - To-Do List App (React + Vite)

This is the **frontend** of the MERN To-Do List App, built using **React**, **Vite**, **Toastify** and **Axios**. It connects to the backend API to perform CRUD operations on tasks.

## Tech Stack

- React + Vite
- Axios
- React Toastify

## Dependencies 

  "axios"
  "react"
  "react-dom"
  "react-router-dom"
  "react-toastify"

## API_URI

'https://todo-backend-evep.onrender.com/api/tasks'

