# Library Management System Using NodeJS

![NodeJS](https://img.shields.io/badge/Node.js-v18-green)
![Express](https://img.shields.io/badge/Express-v4.18-blue)
![EJS](https://img.shields.io/badge/EJS-v3.1-orange)



A simple Library Management System built with NodeJS, Express.js, and EJS.  
This project allows administrators to manage books: add, issue, return, and delete books.

---

## Features

- Add new books with details: name, author, pages, price, availability  
- View all books in a table  
- Issue and return books  
- Delete books from the library  

---

## Project Structure
````
Library Management System/
├── node_modules/       # Installed dependencies (usually not pushed to GitHub)
├── views/              # EJS templates
├── README.md           # Project documentation
├── app.js              # Main server file
├── package-lock.json   # Auto-generated lock file
└── package.json        # NodeJS project configuration

````

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Avinash-Singh-13/Node-JS-Project.git
cd Node-JS-Project
```

2. Install dependencies:
```bash
npm install
```

3. Run the application:
```
node app.js
```

4. Open your browser and visit:
```
http://localhost:3000
```
## Usage

1. Add a Book: Fill in the form and click Add.

2. Issue a Book: Click Issue next to an available book.

3. Return a Book: Click Return next to an issued book.

4. Delete a Book: Click Delete to remove a book from the library.


## How It Works

-> Server: app.js handles HTTP requests with Express.js.

-> View Engine: EJS dynamically renders book data on the frontend.

-> Middleware: Body Parser handles form submissions.

->Book Data: Books are stored in an in-memory array for demonstration.
