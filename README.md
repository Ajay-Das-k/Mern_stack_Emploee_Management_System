
# Employee Management System

A comprehensive web application built with the MERN stack (MongoDB, Express.js, Node.js, EJS) for managing employee records, administrative dashboards, and user authentication.

## 🚀 Key Features

- **🔑 Admin Authentication & Security**:
  - Secure login with `bcryptjs` password encryption
  - Session management via `express-session`
  - Protected routes with authentication middleware
  - Prevents unauthorized back-navigation post-logout

- **👥 Employee Management (Full CRUD)**:
  - Add new employees with Name, Email, Mobile Number, Designation (HR, Manager, Sales), Gender, and Courses (MCA, BCA, BSC)
  - List and view all employee details
  - Edit and update existing employee profiles
  - Delete employee records dynamically
  - Real-time display of total employee count on Dashboard

- **🖼️ Image Upload & Processing**:
  - Profile image uploads handled by `Multer`
  - Image resizing and optimization using `Sharp`

- **✅ Form Validation & Constraints**:
  - Client-side JavaScript validation for form input fields
  - Server-side validations preventing duplicate Email and Mobile Number registrations

- **⚙️ Architecture & Database**:
  - Built with clean MVC (Model-View-Controller) design pattern
  - MongoDB Atlas database integration via `Mongoose` schemas
  - Dynamic server-side UI rendering with `EJS` templates


![Clone](https://i.pinimg.com/originals/e3/52/6f/e3526f9d3757ec5610f24e25d4be4acc.gif)

## GitHub Repo : github.com/Ajay-Das-k/Mern_stack_Emploee_Management_System
(https://github.com/Ajay-Das-k/Mern_stack_Emploee_Management_System.git)

## Live Link: mern-stack-employee-management-system.onrender.com/
(https://mern-stack-employee-management-system.onrender.com/)
(free instance will spin down with inactivity, which can delay first requests by 50 seconds or more)

![0](0.png)
![1](1.png)
![2](2.png)
![4](3.png)



## Getting Started

create .env with variables

PORT=5000
sessionSecret =mysitesessionsecret;
MONGODB_URL=mongodb+srv://user:Password@cluster.mongodb.net/?retryWrites=true&w=majority&appName=EmployeeManagement

To get started with the project, follow these steps:

1. Go to the project directory.
2. Install dependencies by running:
   
   ```bash
    npm i nodemon -g
   npm install

3. Run Project by:
   
   ```bash
   npm start

  