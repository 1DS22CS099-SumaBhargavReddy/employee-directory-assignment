📘 Employee Directory Dashboard
🧾 Overview
This repository contains the code for a React-based Employee Management Dashboard built as part of the Frontend Assignment for Ajackus.
The app allows users to create, read, update, and delete (CRUD) employee records. It also provides capabilities for filtering, sorting, and searching employees — all within a responsive and elegantly styled UI.

No backend is connected; data is managed in the browser using localStorage for persistence.

💻 Technologies Used (Frontend)
Tech	Description
React.js	Frontend framework for building the UI
React Router	Routing between dashboard and form pages
CSS (custom)	Responsive and multi-colored modern UI styling
JavaScript (ES6+)	Core logic for state and interactivity
localStorage	For storing and persisting employee data

🌐 Deployment
Optional: You can deploy this project using Netlify or Vercel.
After deployment, add the live link here:

📍Live Demo: https://your-app-name.netlify.app

📦 How to Run Locally
🔧 Installation Steps
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/employee-directory-react.git
Navigate to the project directory:

bash
Copy
Edit
cd employee-directory-react
Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm start
Open your browser and visit:

arduino
Copy
Edit
http://localhost:3000
🔍 Features
Feature	Description
✅ Create New Employee	Add a new employee record with first name, email, etc.
📄 View Employees	View all employees in a responsive card/grid layout
✏️ Edit Existing Employee	Update employee details using a pre-filled form
❌ Delete Employee	Remove an employee from the dashboard
🔎 Search Employees	Search by name or email
🎛 Filter Options	Filter by first name, department, or role
↕️ Sort Employees	Sort alphabetically by first name or department
📱 Responsive UI	Optimized for mobile, tablet, and desktop screens
💾 localStorage Persistence	Data is saved across browser reloads with no backend needed

📡 Endpoints (If Backend Were Connected)
Since this is a frontend-only app, the data is stored in localStorage.
But if integrated with a backend, the typical RESTful endpoints would be:

Action	Endpoint	Method
Get all employees	/employees	GET
Add employee	/employees	POST
Edit employee	/employees/:id	PUT / PATCH
Delete employee	/employees/:id	DELETE

🔗 You can simulate these using tools like json-server or mockapi.io if needed.

📁 Folder Structure
graphql
Copy
Edit
employee-directory-react/
├── public/
│   └── index.html
├── src/
│   ├── components/      # EmployeeCard, FilterBar, Form, Pagination
│   ├── pages/           # Dashboard and FormPage (route-based views)
│   ├── data.js          # Initial mock employee data
│   ├── App.js           # Main routing logic
│   ├── App.css          # Custom multi-colored responsive styling
│   └── index.js         # Entry point
🧠 Reflection

✅ Challenges Faced
Managing shared employee state between dashboard and form routes.

Implementing filter + sort + search in a combined logic flow.

Designing a creative yet clean UI without any UI framework (e.g., Bootstrap).

🔧 What I’d Improve with More Time
Add image/avatar upload support.

Backend integration with Express or Firebase.

Role-based access (admin vs viewer).

Export data as CSV.

Dark mode toggle 🌙

👨‍💻 Author
Developed by Kaipa Suma Bhargav Reddy

