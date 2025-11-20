# Simple-Database-Creation
SQL script to create the web_experiment_db database, the users table, and insert initial sample data. Connects to the MySQL database and fetches all records from the users table, displaying them in an HTML table. (Simple READ operation).

# 🌐 PHP & MySQL Web Development Experiments

This repository contains solutions for a series of web development assignments focused on building fundamental server-side functionality using **PHP** and **MySQL**. The experiments cover database connection, full CRUD (Create, Read, Update, Delete) operations, and basic security measures like prepared statements and password hashing.

---

## 🛠️ Setup Instructions

To run these experiments locally, you will need a server environment with PHP and MySQL (e.g., XAMPP, MAMP, or WAMP).

1.  **Clone the Repository:**
    ```bash
    git clone [YOUR_REPOSITORY_URL]
    cd [repository-name]
    ```

2.  **Database Configuration:**
    * Start your Apache and MySQL services.
    * Open your MySQL tool (phpMyAdmin, etc.).
    * Execute the SQL commands in the `setup.sql` file (located in Experiment 1) to create the `web_experiment_db` database and the initial `users` table.
    * **CRITICAL:** Update the database connection credentials (`$servername`, `$username`, `$password`, `$dbname`) in **ALL** PHP files to match your local environment.

3.  **Run Experiments:**
    * Place all PHP and HTML files in your local web server's root directory (e.g., `/htdocs` or `/www`).
    * Access the files via your browser (e.g., `http://localhost/index.php`).

---

## 🧪 Experiments Summary (CRUD Operations)

### 1. Simple Database Connection & Display (READ)

| File | Description |
| :--- | :--- |
| `setup.sql` | Initial database and table structure. |
| `index.php` | Establishes a connection, fetches all user data, and displays it dynamically in an HTML table. |
