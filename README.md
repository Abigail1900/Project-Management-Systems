Project Management Systems

Overview:
Nexus Corp. faces challenges in managing multiple projects simultaneously due to inefficient tracking of tasks, resources, budgets, and communication. This project aims to develop a centralized **Project Management System** using **React (frontend)** and **Laravel (backend)** to help teams **organize work, assign tasks, monitor progress, track budgets, and improve communication** among members and stakeholders.

Features
- User Authentication: Register, login, and logout functionalities.
- Project Management: Create, update, delete, and manage projects.
- Task Assignment: Assign tasks, update progress, and set priorities.
- Resource and Budget Management*: Allocate resources, track expenditures, and monitor progress.
- Collaboration Tools: Task comments, notifications, and file sharing.
- Reporting and Analytics: Generate project reports, risk assessments, and track issues.

Tech Stack
- Frontend: React.js
- Backend: Laravel (PHP)
- Database: MySQL
- Version Control: Git & GitHub

Team Composition & Roles
- Project Manager – Oversees progress, manages sprints, and ensures deadlines.
- Frontend Developer– Develops React components and user interface.
- Backend Developer – Implements Laravel API and database structure.
- Tester/QA – Tests the system, identifies bugs, and ensures quality.
- Documentation Specialist – Prepares technical documentation and user guides.

Sprint Plan

Sprint 1: Project Setup and Basic Structure (1 Week)
✅ Set up project environment (React & Laravel)  
✅ Implement user authentication (register, login, logout)  
✅ Design database schema (projects, tasks, users)  
✅ Create basic UI components (login, dashboard)  

Deliverables:
- Working user authentication
- Database schema
- Basic UI for login and dashboard

 Installation Guide
Prerequisites
Ensure you have the following installed:
- Node.js & npm (for React frontend)
- PHP & Composer (for Laravel backend)
- MySQL (for database management)

Backend (Laravel Setup)
1. Clone the repository:
   sh
   git clone https://github.com/yourusername/project-management-system.git
   
2. Navigate to the backend directory:
   sh
   cd backend
   
3. Install dependencies:
   sh
   composer install
   
4. Copy environment file and set up database:
   sh
   cp .env.example .env
   php artisan key:generate
   
5. Migrate database:
   sh
   php artisan migrate
   
6. Run the server:
   sh
   php artisan serve
   

Frontend (React Setup)
1. Navigate to the frontend directory:
   sh
   cd frontend
   
2. Install dependencies:
   sh
   npm install
   
3. Start the development server:
   sh
   npm start

Contributors
- Project Manager: [Martin, Darren]
- Frontend Developer: [Osias, Shariel]
- Backend Developer: [Manalo, Abigail]
- Tester/QA: [Panganiban, Mica]
- Documentation Specialist: [Matira, Sherinne Anne]
