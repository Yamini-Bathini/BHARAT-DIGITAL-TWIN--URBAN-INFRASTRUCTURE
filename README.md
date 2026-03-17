# 🏙️ BHARAT-DIGITAL-TWIN--URBAN-INFRASTRUCTURE
A web platform designed to monitor and manage urban infrastructure assets through a centralized dashboard.  
The system integrates Digital Twin concepts to represent physical city infrastructure in a digital environment, enabling better monitoring, management, and decision-making.

---

# 🚀 Live Demo
https://urban-infrastructure.vercel.app

---

# 🌐 What is a Digital Twin?

A Digital Twin is a virtual representation of real-world systems, infrastructure, or assets. It mirrors physical objects in a digital environment and updates them using real-time or stored data.

In urban infrastructure, digital twins help cities:

- Monitor infrastructure performance
- Track infrastructure assets
- Analyze system behavior
- Improve maintenance and planning
- Support data-driven decision making

In this project, infrastructure assets are digitally represented and managed through a dashboard and backend system, forming a basic digital twin model of urban infrastructure.

---

# 📌 Features

- 🔐 User Authentication (Register / Login)
- 👨‍💼 Admin Dashboard
- 🏗 Infrastructure Asset Management
- 📊 Infrastructure Monitoring Dashboard
- 🗄 SQLite Database Integration
- ⚡ REST API Backend with Node.js

---

# 🛠 Tech Stack

Frontend
- HTML
- CSS
- JavaScript

Backend
- Node.js
- Express.js

Database
- SQLite

Deployment
- Vercel

---

# 📂 Project Structure

hackzz/

backend/
- middleware/
  - auth.js
- models/
  - Assets.js
  - User.js
- routes/
  - adminRoutes.js
  - assetRoutes.js
  - authRoutes.js
- database.sqlite
- server.js
- .env

Frontend
- admin.html
- dashboard.html
- index.html
- login.html
- register.html
- script.js
- styles.css

Other
- package.json
- vercel.json
- README.md

---

# ⚙️ Installation

Clone the repository

git clone https://github.com/Yamini-Bathini/BHARAT-DIGITAL-TWIN--URBAN-INFRASTRUCTURE.git

Navigate into the project folder

cd BHARAT-DIGITAL-TWIN--URBAN-INFRASTRUCTURE

Install dependencies

npm install

Start the backend server

node backend/server.js

---

# 🔑 Environment Variables

Create a .env file inside the backend folder.

Example:

PORT=5000  
JWT_SECRET=your_secret_key

---

# 👨‍💻 Usage

1. Register a new user  
2. Login with credentials  
3. Access the infrastructure dashboard  
4. Admin can manage and monitor infrastructure assets
