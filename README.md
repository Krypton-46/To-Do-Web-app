To-Do Web App

A simple and interactive web application built with Node.js, EJS, and JavaScript that allows users to manage tasks efficiently.
Features

    View a list of to-dos

    Add new to-dos

    SQL-based persistence using queries.sql (e.g., insert, update, delete, list operations)

    Backend logic implemented in solution.js

    Basic routing and templating with EJS

    Organized project structure:

        /public – static files (CSS, client-side JS, images)

        /views – EJS templates

        index.js – server entry point

        queries.sql – SQL schema and scripts for setup

Prerequisites

    Node.js (v14 or above recommended)

    npm (usually installed with Node.js)

    SQLite (or another SQL database) if needed to run SQL scripts

Installation & Setup

    Clone the repo:

git clone https://github.com/Krypton-46/To-Do-Web-app.git
cd To-Do-Web-app

Install dependencies:

npm install

Set up your database:

    Run the SQL in queries.sql to create tables and seed (if any)

    Adjust DB connection settings in index.js or the appropriate file

Start the server:

    npm start

    Visit the app at http://localhost:3000 (or your configured port)

Usage

    Navigate to the home page to see the current to-do list.

    Use the form to add new tasks.

    Complete or delete tasks (if supported via UI).

    The app stores data via SQL and renders dynamic pages using EJS.

Folder Structure

To-Do-Web-app/
├── public/
│   └── (stylesheets, JS, images)
├── views/
│   └── (EJS templates)
├── index.js
├── solution.js
├── queries.sql
├── package.json
└── .gitignore

Roadmap

    Add Edit Task feature

    Enable sorting/filtering (e.g., completed, pending)

    Implement user authentication

    Persist tasks in a remote database (e.g., PostgreSQL, MongoDB)

    Make UI responsive and improve styling

Contributing

Contributions are welcome! Feel free to:

    Open an issue for bugs or feature suggestions

    Submit pull requests with improvements

License

This project is open source and available under the MIT License. See the LICENSE file for details (or add one if none exists).
