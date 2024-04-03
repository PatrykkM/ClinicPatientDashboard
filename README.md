# Clinic Patient Dashboard

Welcome to the Clinic Patient Dashboard, an advanced and efficient application for managing patient records in clinical settings. This application is designed to empower healthcare professionals with comprehensive control over patient information, streamlining operations such as adding, editing, deleting, and efficiently searching for patients by surname. It also features robust sorting capabilities, ensuring that patient management is both intuitive and efficient. By leveraging MySQL for database operations, the Clinic Patient Dashboard ensures reliability and performance at the core of patient data handling.

## Highlights

- 🚀 **Rapid Development**: Completed within a tight 3-day deadline, demonstrating effective time management and coding skills.
- 📚 **Valuable Learning Experience**: This project has been an incredible learning journey, enhancing my back-end skills and understanding of practical application development.
- 📝 **Comprehensive Patient Management**: Facilitates adding, editing, and deleting patient data, enabling seamless management of patient information.
- 🔍 **Advanced Search and Sorting**: Offers powerful search functionality, including the ability to find patients by surname, and sorting options to navigate patient data effortlessly.
- 🖥 **User-Friendly Interface**: Designed with user experience in mind, making it easy for medical staff to manage patient records efficiently.
- 📱 **Responsive Design**: Guarantees an optimal viewing experience across all devices, ensuring accessibility in various clinical environments.
- 🔒 **Commitment to Quality**: Emphasizes clean code, best practices, and the secure handling of patient data, showcasing a professional approach to software development.

## Technologies

[![React](https://img.shields.io/badge/React-gray?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-gray?style=for-the-badge&logo=express)](https://expressjs.com/)
[![MySQL](https://img.shields.io/badge/MySQL-gray?style=for-the-badge&logo=mysql)](https://www.mysql.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-gray?style=for-the-badge&logo=tailwind-css&logoColor=06B6D4)](https://tailwindcss.com/)
[![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-gray?style=for-the-badge&logo=redux&logoColor=764ABC)](https://redux-toolkit.js.org/)

# How to run local app

## Prerequisites

- Make sure you have Node.js installed on your system (https://nodejs.org/).
- Make sure you have MySQL installed on your system (https://dev.mysql.com/downloads/mysql/).

## Installation Steps

1. Clone the app from GitHub:
   git clone https://github.com/PatrykkM/ClinicPatientDashboard.git
2. Change directory to the app's folder:
   cd ClinicPatientDashboard
3. Install npm packages:
   npm install
4. Create a MySQL database and set up the schema and seed data
   code to create database and values to database is in patients.sql file
5. Configure the database connection:

   - Navigate to the `server` folder.
   - Create a `.env` file in the `server` directory.
   - Add the following content to the `.env` file, replacing the placeholders with your actual MySQL credentials:
     ```
     DB_HOST=localhost
     DB_USER=root
     DB_PASSWORD=your_mysql_root_password
     DB_NAME=clinic_db
     ```
   - Make sure the MySQL service is running and the credentials match the user and password of your MySQL database.

6. Start the server:
   cd server
   node index.js
7. Start the client
   npm run dev
   ## CLIENT MUST WORK ON PORT 5173
8. Enjoy the view :D

   ![App](src/assets/img/adminPanel.jpg "App")
