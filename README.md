ModernTech HR Tracker


A full-stack real-time employee tracking and performance monitoring web application built by Urswin Faro, Armien Beggs and Abdul Felton for our Life Choices assignment. ModernTech HR Tracker empowers HR managers with tools to monitor employee performance, maintain accurate records, and manage tech portfolios efficiently.

Table of Contents
- Live Demo
- Technologies Used
- Setup Instructions
- Key Features
- Usage Instructions
- Potential Improvements
- Credits
- Author

Live Demo
Access the live demo here: https://github.com/Urswin-Faro/Project_02_Node.git

Technologies Used
- Frontend: HTML, CSS, JavaScript, Vue.js
- Backend: Node.js, MySQL, Bcrypt
- Other Tools: ChatGPT, GitHub, Thunderclient

Setup Instructions
Follow these steps to run the ModernTech HR Tracker on your local machine:

1. Prerequisites
- Node.js and NPM installed
- MySQL running with a database named moderntech_db
2. Clone the Repository
git clone https://github.com/Urswin-Faro/Project_02_Node.git

3. Install Dependencies
Backend:
cd Project_02_Node
npm install
node --watch index.js

Frontend:
cd frontendproject
npm install
npm run serve

4. Environment Variables
- Add .env files to the root directories of both the frontend and backend.
- Include your MySQL credentials and relevant config values.

Your application should now be running locally:
- Frontend: http://localhost:8080
- Backend API: http://localhost:3030

Key Features
- User Authentication: Sign up, log in, and manage sessions using JWT-based authentication.
- Real-Time Updates: Performance and employee data are reflected instantly (real-time updates where applicable).
- CRUD Operations: Full Create, Read, Update, Delete capabilities for employee records.
- Responsive Design: Mobile-first design for usability on all devices.
- Error Handling: Comprehensive client and server-side error validation.
- Secure Password Handling: User passwords hashed securely with Bcrypt.
- API-Driven Architecture: Clean and RESTful API structure for data handling.

Usage Instructions
1. Visit http://localhost:8080 in your browser.
2. Register or log in with your credentials.
3. Use the dashboard to:
- View employee performance metrics
- Add/update/delete employee records
- Track real-time changes and status

Potential Improvements
- Role-based access (Admin/Manager/User)
- Employee feedback and review module
- Integration with external tools (e.g., Slack, email notifications)
- Enhanced analytics dashboard with charts and performance trends
- Mobile app version for HR on-the-go

Credits
- Vue.js: https://vuejs.org
- Node.js: https://nodejs.org
- Bcrypt: https://www.npmjs.com/package/bcrypt
- MySQL: https://www.mysql.com
- Thunderclient: https://www.thunderclient.com


Author
Urswin Faro
Armien Beggs
Abdul Felton

GitHub: https://github.com/Urswin-Faro
