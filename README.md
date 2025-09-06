# OdooxNMIT-25
OdooxNMIT-25
OdooxNMIT-25 is a team collaboration platform built by NMIT students for the Odoo x NMIT Hackathon '25. This repository contains a full-stack project with separate client and server codebases, designed to help teams manage projects, tasks, and collaboration efficiently.

Table of Contents
Project Overview
Repository Structure
Tech Stack
Getting Started
Available Scripts
Features
Contributing
License
Contact
Project Overview
OdooxNMIT-25 is intended as a collaborative platform for hackathon teams. The main features planned include:

Authentication (login/signup)
User dashboard
Project management (create projects, add tasks)
Team management
Real-time updates
Currently, core authentication and basic dashboard functionality are available (see client/src/App.js, client/src/components/Signup.js, client/src/services/authService.js).

Repository Structure
OdooxNMIT-25/
├── client/      # Frontend (React)
│   ├── src/
│   │   ├── App.js
│   │   ├── components/
│   │   ├── services/
│   ├── public/
│   ├── README.md
├── server/      # Backend (Express) [structure may vary]
├── docs/        # Documentation
├── scripts/     # Utility scripts
├── README.md
├── LICENSE
client/: React frontend bootstrapped with Create React App.
server/: Backend API (Express); details depend on implementation.
docs/: Documentation and reference material.
scripts/: Utilities for setup and maintenance.
Tech Stack
Frontend: React (Create React App)
Backend: Express (Node.js)
Auth: JWT-based authentication (see client/src/services/authService.js)
Database: [To be defined]
Other: Axios for API requests
Getting Started
Clone the repository

git clone https://github.com/chiragveerwani/OdooxNMIT-25.git
cd OdooxNMIT-25
Install dependencies

Frontend:
cd client
npm install
Backend:
cd server
npm install
Run the application

Start Backend (Express):
cd server
npm start
Start Frontend (React):
cd client
npm start
The frontend runs at http://localhost:3000 by default.
Available Scripts (Frontend)
npm start – Runs the app in development mode.
npm test – Launches the test runner.
npm run build – Builds the app for production.
npm run eject – Ejects configuration (irreversible).
See more in Create React App documentation.

Features
Current:

User authentication (register, login, logout)
Persistent login via localStorage
Basic dashboard interface
Planned (see Dashboard):

Project creation
Task management
Team features
Real-time updates
Contributing
Contributions are welcome!
Please fork the repo, create a feature branch, make your changes, and open a pull request.

License
This project is licensed under the MIT License.

Contact
Maintainer: chiragveerwani
For issues and suggestions, use GitHub Issues
Acknowledgements
Create React App
Express
NMIT Hackathon '25 Team
