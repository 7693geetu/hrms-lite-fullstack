HRMS Lite - Human Resource Management System
A professional, full-stack Human Resource Management System (HRMS) built to streamline employee record management and automate daily attendance tracking.

🔗 Deployment Links
Live Frontend URL: https://hrms-lite-fullstack.vercel.app

Hosted Backend API: https://hrms-lite-fullstack-pl4h.onrender.com

GitHub Repository: https://github.com/7693geetu/hrms-lite-fullstack

🚀 Project Overview
This application was developed to solve core HR needs: managing a workforce database and maintaining accurate attendance logs. It features a responsive React dashboard connected to a robust Flask REST API.

Key Functionality:

Employee Management: Add and delete employee profiles with server-side validation.

Attendance System: Mark employees as "Present" or "Absent" for any specific date.

Dashboard Summary (Bonus): Real-time tracking of total staff, present counts, and absent counts for the current day.

Persistence: All data is stored in a relational SQLite database via SQLAlchemy.

🛠 Tech Stack
Frontend: React.js, CSS3 (Custom UI Components)

Backend: Python, Flask, Flask-CORS

Database: SQLite

Deployment: Vercel (Frontend), Render (Backend)

⚙️ Steps to Run Locally
1. Clone the Repository
Bash
git clone https://github.com/7693geetu/hrms-lite-fullstack.git
cd hrms-lite-fullstack
2. Backend Setup
Navigate to the directory: cd Backend

Install dependencies: pip install -r requirements.txt

Run the server: python app.py

The API will be available at http://localhost:5000.

3. Frontend Setup
Navigate to the directory: cd frontend/my-app

Install packages: npm install

Start the app: npm start

The UI will be available at http://localhost:3000.

📌 Assumptions & Limitations
Render Free Tier: The backend is hosted on a free tier. If the site has been inactive, please allow 60 seconds for the server to "wake up" on the first request.

Data Persistence: SQLite is used for this implementation. On Render's free tier, the database may reset if the server restarts.

Single Admin: The current version assumes an internal network/admin use case; user authentication (Login/Sign-up) is not included in this scope.
