# Wanderlust

A full-stack MERN project for travel listings built with Node.js, Express, MongoDB, and EJS.

---

## 🌍 Wanderlust – Local Setup Guide

Set up the Wanderlust travel listing project on your system in just a few steps.

### 🛠 Prerequisites

Make sure you have:

- Node.js (v18 recommended)  
- MongoDB (running locally)  
- Nodemon (installed globally)

### 🚀 Setup Instructions

1. Clone the Project

   ```bash
   git clone https://github.com/rohitvilhekar100/Wanderlust-Major-Project.git
   cd Wanderlust-Major-Project

2. Create a .env file in the root folder and add:
 
ATLASDB_URL=mongodb://127.0.0.1:27017/wanderlust
CLOUD_NAME=your_cloud_name
CLOUD_API_KEY=your_api_key
CLOUD_API_SECRET=your_api_secret
SECRET=your_session_secret

3. Install Dependencies
npm install

4. Start the Server
nodemon app.js

5. Access the Project
Open your browser and go to:
http://localhost:8080


