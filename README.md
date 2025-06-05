Task Manager

A full-stack Task Manager application built with a React frontend and a Node.js backend, designed to manage teams and tasks efficiently. This project allows users to create teams, add members, assign tasks, and track progress.


Project Structure

frontend/: Contains the React-based user interface.
Built with React, Vite, and Tailwind CSS.
Key files: src/Dashboard.jsx (main dashboard component).


backend/: Contains the Node.js/Express server.
Provides API endpoints for managing teams, tasks, and users.
Uses a database (e.g., SQLite/PostgreSQL) for persistent storage.



Features

Create and manage teams.
Add members to teams.
Create, edit, and delete tasks.
Assign tasks to team members.
Filter tasks by team, assignee, or search query.
Responsive design for mobile and desktop.

Prerequisites
Before running the project, ensure you have the following installed:

Node.js (v16 or higher)
npm (v8 or higher)
Git

Setup Instructions
1. Clone the Repository
git clone https://github.com/i23-2082/task.git
cd task

2. Set Up the Backend
Navigate to the backend folder and install dependencies:
cd backend
npm install


Configure environment variables (e.g., database URL) in a .env file (see .env.example if provided).
Start the backend server:npm start


The backend typically runs on http://localhost:5000.



3. Set Up the Frontend
Open a new terminal, navigate to the frontend folder, and install dependencies:
cd frontend
npm install


Start the frontend development server:npm run dev


The frontend typically runs on http://localhost:5173.



4. Access the Application

Open your browser and go to http://localhost:5173.
Log in or sign up to start managing tasks and teams.

API Endpoints (Backend)

GET /teams: Fetch all teams.
POST /teams: Create a new team.
GET /tasks/get-task: Fetch all tasks.
POST /tasks/create-task: Create a new task.
PUT /tasks/:id: Update a task.
DELETE /tasks/:id: Delete a task.

Technologies Used

Frontend:
React
Vite
Tailwind CSS
Lucide React (for icons)


Backend:
Node.js
Express
SQLite/PostgreSQL (or your chosen database)


Other:
Axios (for API requests)
Git (for version control)



Contributing

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

License
This project is licensed under the MIT License.
Contact
For questions or suggestions, reach out to:

GitHub: i23-2082

