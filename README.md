Finflow: Expense vs Income Visualizer
Live Demo Link: https://finflow.free.nf/

Finflow is a dynamic web application designed to provide a comprehensive solution for personal financial management. It offers an intuitive platform for users to track income and expenses, set and monitor budgets, and visualize their financial data through an interactive dashboard. This project was developed as the capstone project for my Web Development Summer Internship.

🚀 Core Features
User Authentication: Secure user registration and login system to protect personal financial data.

Interactive Dashboard: An at-a-glance summary of total income, expenses, and net balance. Includes dynamic charts for yearly/monthly trends and a pie chart for spending breakdowns by category.

Transaction Management: Full CRUD (Create, Read, Update, Delete) functionality for both income and expense records. Transactions can be filtered and sorted for easy viewing.

Budgeting Tools: Users can set, update, and track monthly budgets for various categories. The system provides real-time progress bars and alerts when spending exceeds the set limits.

Financial Reporting: Generate detailed financial reports for custom time periods. Users can visualize spending patterns and download their transaction data as a CSV file for offline analysis.

🛠️ Technology Stack
This project is a full-stack application built with the following technologies:

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

⚙️ Getting Started
To get a local copy up and running, follow these simple steps.

Prerequisites
A web server environment like XAMPP or WAMP which includes PHP and MySQL.

Git for cloning the repository.

Installation
Clone the repository into your web server's root directory (e.g., htdocs in XAMPP):

git clone [https://github.com/](https://github.com/)[YOUR_GITHUB_USERNAME]/[YOUR_REPOSITORY_NAME].git

Set up the database:

Open phpMyAdmin (usually found at http://localhost/phpmyadmin).

Create a new database and name it finflow_db.

Select the new database and go to the "Import" tab.

Upload and import the database.sql file (included in the repository) to set up the necessary tables.

Configure the database connection:

Open the db_connect.php file in your code editor.

Update the database credentials (hostname, username, password, and database name) to match your local server setup.

$servername = "localhost";
$username = "root";
$password = ""; // Your password, often empty by default in XAMPP
$dbname = "finflow_db";

Run the application:

Make sure your Apache and MySQL servers are running from the XAMPP/WAMP control panel.

Open your web browser and navigate to http://localhost/[YOUR_REPOSITORY_NAME]/.

You should now be able to register a new user and use the application.

📂 Project Structure
The repository is organized with a clear separation between the frontend presentation files and the backend PHP logic.

index.html: The main landing page.

signin.html / signup.html: User authentication pages.

dashboard.php: The main user dashboard after login.

transactions.php, budgets.php, reports.php: Core feature pages.

*_process.php: Backend PHP scripts that handle form submissions, data processing, and database interactions.

db_connect.php: Handles the connection to the MySQL database.

style.css: Main stylesheet for the application.

✨ Acknowledgements
This project was completed as part of my summer internship training provided by Kistechnosoftware, Jaipur.