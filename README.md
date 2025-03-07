Project Setup

This project consists of a frontend (client) and a backend (server). Follow the steps below to set up and run the project locally.

Prerequisites

Make sure you have the following installed:

Node.js (LTS version recommended)

npm or yarn

Installation and Setup

1. Clone the Repository

Clone the repo and navigate to directory

2. Backend Setup

cd server
npm install   #Install backend dependencies
npm start     #Start the backend server

3. Frontend Setup

cd ../client
npm install   # Install frontend dependencies
npm start     # Start the frontend application

The frontend will run on http://localhost:3000 (default React app port).

Environment Variables

Create a .env file in both server and client folders (if required) and add the necessary environment variables.

Running the Application

Make sure both the backend and frontend are running simultaneously. Open http://localhost:3000 in your browser to view the application.

Tech Stack

Frontend: React, Tailwind CSS (if used)

Backend: Node.js, Express

Database: MongoDB / SQLite (as applicable)