Employee Activity Dashboard
Introduction
The Employee Activity Dashboard is a React web application built with Vite. It provides insights into employee activities, including their ranking, name, designation, hours worked, and changes in working hours.

Key Features
Employee List: View detailed information about each employee.
Employee of the Month: Highlight exceptional employees.
Navbar: Display current date and time for easy reference.
Responsive Design: Ensures a seamless experience across various devices.
Getting Started
To run the project locally, follow these steps:

Install Dependencies:

Copy code
npm install
Start Development Server:

arduino
Copy code
npm run dev
The application will be available at http://localhost:3000.

Available Scripts
dev: Start the development server.
build: Build the application for production.
lint: Run ESLint to check for linting issues.
preview: Preview the built application.
Directory Structure
public/: Contains the HTML template.
src/: Contains React components and styles.
assets/: Images of employees.
components/: React components like Dashboard, EmployeeCard, EmployeeOfMonth, and Navbar.
data/: Employee data.
styles.css: Custom styles for the project.
App.js: Main app component.
main.jsx: Entry point of the React application.
Components
Dashboard
Main component displaying the employee list and Employee of the Month.

EmployeeCard
Displays individual employee details.

EmployeeOfMonth
Highlights the Employee of the Month.

Navbar
Shows current date and time.

Styling
Custom styles defined in styles.css, featuring a modern and clean design.

Employee Data
Employee data stored in src/data.js.

Customization
Feel free to customize styles, components, and data to suit your requirements.

Dependencies
@emotion/react
@emotion/styled
@mui/icons-material
@mui/material
bootstrap
react
react-dom
Dev Dependencies
@types/react
@types/react-dom
@vitejs/plugin-react
eslint
eslint-plugin-react
eslint-plugin-react-hooks
eslint-plugin-react-refresh
vite