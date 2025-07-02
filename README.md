🧾 Smart Expense Manager (MERN Stack)
A full-stack Expense Tracker built with the MERN stack (MongoDB, Express, React, Node.js). This app allows users to register, log in, and manage their personal expenses with a clean and responsive UI.

🔑 Features
🔐 User Authentication (Signup/Login with JWT)

➕ Add Expense with Name & Amount

📅 Real-Time Date & Time Display

🗑️ Delete Single or All Expenses

📱 Responsive Design

🚪 Logout Functionality

🛠️ Tech Stack
Frontend: React.js, Reactstrap

Backend: Node.js, Express.js

Database: MongoDB (Local)

Authentication: JWT, bcrypt

Version Control: Git & GitHub

 How to Run Locally
Prerequisites:
Node.js installed

MongoDB installed and running locally

Git installed

1. Clone the Repository

git clone https://github.com/your-username/expense-tracker-mern.git
cd expense-tracker-mern

2. Set Up the Backend

cd backend
npm install

🔐 Create .env File in backend Folder:
PORT=5000
MONGO_URI=mongodb://localhost:27017/expenseDB
JWT_SECRET=yourSecretKey

3. Start the Backend Server
npm run server

4. Set Up the Frontend
Open a new terminal and navigate to the frontend folder:

cd ../frontend
npm install

5. Start the Frontend App
npm start
