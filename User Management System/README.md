# User Management System Using NodeJS

![NodeJS](https://img.shields.io/badge/Node.js-v18-green)
![Express](https://img.shields.io/badge/Express-v4.18-blue)
![EJS](https://img.shields.io/badge/EJS-v3.1-orange)

A simple User Management System built with NodeJS, Express.js, and EJS.  
This project allows administrators to manage users: add, view, update, and delete user accounts.

---

## Features

- Add new users with details: unique ID, name, email, age  
- View all users in a table  
- Update existing user details  
- Delete users from the system  

---

## Project Structure
```
User Management System/
├── node_modules/ # Installed dependencies (usually not pushed to GitHub)
├── views/ # EJS templates
│ └── home.ejs # Main view template
├── README.md # Project documentation
├── app.js # Main server file
├── package-lock.json # Auto-generated lock file
└── package.json # NodeJS project configuration
```



---

## How to Build User Management System Using NodeJS?

A User Management System is an essential application for handling user accounts and information. It involves creating, reading, updating, and deleting user accounts, also known as CRUD operations. Below is a simple way to build this system.

---

### Steps to Build

#### Step 1: Create a Project Folder
```
mkdir user-management-system
cd user-management-system
```

#### Step 2: Initialize a NodeJS Project
```
npm init -y
```

#### Step 3: Install Dependencies
```
npm install express ejs body-parser
```

#### Step 4: Create Server File (`app.js`)


#### Step 5: Set Up Views Directory
```

Create a folder named `views` and inside it create `home.ejs` with the following content:
```
#### Running the Application
```
1. Make sure you have Node.js installed.
2. From the project root directory, run:
      node app.js
3. Open your browser and navigate to:
      http://localhost:3000
```
#### Usage
```
1. Add a User: Fill in the form and click Submit.
2. Update a User: Enter user ID and new details then click Update.
3. Delete a User: Click Delete button next to a user.
4. View Users: The table displays all current users.
```

#### How It Works
```
1. Server: app.js uses Express to handle HTTP requests.
2. View Engine: EJS renders dynamic HTML views with user data.
3. Middleware: Body Parser processes form submissions.
4. User Data: Users are kept in an in-memory array (for demo purposes).
```
