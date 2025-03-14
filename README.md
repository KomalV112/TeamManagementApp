# TeamManagementApp

Team & Project Management System (MERN Stack with GraphQL & Apollo)
🚀 Overview
A full-stack Team & Project Management System built with the MERN stack (MongoDB, Express, React, Node.js). It features a GraphQL API with Apollo Server and a React Vite frontend for managing users, teams, and projects.

📌 Features
🔹 Express GraphQL API
Users: Create, read, update, delete (CRUD) users with authentication (JWT, HTTPOnly cookies).
Teams: Manage teams with members, descriptions, and statuses.
Projects: Assign projects to teams and update statuses.
Authorization: Role-based access for admins and members.
🔹 React Vite Frontend
User Login: Secure authentication with JWT.
Team Management: View team details, projects, and update statuses.
Admin Controls: Create users, teams, and assign projects.
UI Design: Built with React-Bootstrap for responsiveness and accessibility.
🛠️ Tech Stack
Backend: Node.js, Express.js, GraphQL, Apollo Server, MongoDB, Mongoose.
Frontend: React (Vite), Apollo Client, React-Bootstrap.
Authentication: JWT, HTTPOnly Cookies.

🚀 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/team-management-system.git
cd team-management-system

2️⃣ Backend Setup
cd server
npm install
npm start
Create a .env file for database connection and JWT secrets.

3️⃣ Frontend Setup
cd client
npm install
npm run dev



📜 API Endpoints (GraphQL)
users: Query, create, update, delete users.
teams: Manage teams and assign members.
projects: Create, update, and assign projects.

🔐 Authentication & Authorization
Admin: Manage users, teams, and projects.
Member: View teams, update project status.

]
