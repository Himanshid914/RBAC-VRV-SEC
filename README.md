# Role-Based Access Control (RBAC) System

This project is a simple **User Management System** built with **React-JS**. It allows you to manage users and roles in a table format, with the ability to add, edit, and delete users and roles. Each user has a **name**, **email**, **role**, and **status (active/inactive)**. The app stores user data in **localStorage**, so your data persists even after a page refresh.

## Technologies Used

- **React** for building the UI
- **Tailwind CSS** for styling and responsiveness
- **localStorage** for persisting user data



## Features

- **User Management**: Create, update, and manage user profiles and their associated roles and permissions.
- **Role Management**: Easily manage and assign roles to users.
- **Dynamic Permission Adjustment**: Modify permissions for users or roles as needed.
- **Advanced Filtering and Sorting**: Sort and filter users or roles by different criteria for quick access.
- **Real-Time Validation**: Input validation with real-time feedback for errors or conflicts.
- **Activity Logs**: Keeps track of all actions taken for audit purposes and compliance.
- **Interactive Dashboard**: Intuitive UI for easy navigation through users and roles.

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Himanshid914/RBAC-VRV-SEC.git

2. **Install dependencies:**

   - (Assuming you have Node.js and npm installed)
   - Run the below command to install all the required dependencies.
   
    npm install

2. **Start the application:**

   - Run the below command to start the project locally.
   
    npm start


## Interacting with the Application

- Initally create a role that can eventually be assigned to any User.
- Adding Users: Click on the designated "Add User" button to add a new user.
- Editing Users: Locate the "Edit" button next to a user's record in the table and click it to modify details, including their role.
- Deleting Users: Click the corresponding "Delete" button to permanently remove a user.
- Role Management: When adding or editing a user, you can assign a specific role. This helps to control the access and permissions for each user.
- LocalStorage Utilization: The application leverages the browser's localStorage for user data persistence. This entails:
    - Saving user and role data modifications (addition, editing, deletion) locally to your browser.
    - Maintaining user and role data even upon page refreshes, as it's retrieved from localStorage upon subsequent loads.
