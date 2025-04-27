Blood Bank Management System
A complete web-based Blood Bank Management System developed using PHP and MySQL.
The system helps manage blood donations, donor records, blood requests, and inventory efficiently through an easy-to-use interface for donors, recipients, and administrators.

Features
User Registration and Login for donors and recipients

Blood Request Management — request and fulfill blood donations

Donor Search based on blood group and location

Admin Dashboard for managing users, donations, requests, and blood stock

Blood Stock Monitoring — view available blood units

Secure Authentication and Session Management

User-Friendly Interface with responsive design

Technologies Used
PHP

MySQL

HTML5

CSS3

JavaScript

Bootstrap (for UI components)

XAMPP / WAMP for local server setup

Installation and Setup Instructions
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Agostinejohn/Blood-Bank.git
Server Setup

Install XAMPP or WAMP.

Start Apache and MySQL modules.

Project Configuration

Move the cloned project folder to htdocs (XAMPP) or www (WAMP).

Open http://localhost/phpmyadmin in your browser.

Create a new database named blood_bank.

Import the SQL file located in the project’s database folder (blood_bank.sql) into the newly created database.

Edit Database Connection

Open the config.php file.

Update with your database credentials:

php
Copy
Edit
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "blood_bank";
Running the Application

Visit http://localhost/Blood-Bank in your web browser.

User Roles
Donor

Register and log in.

Update profile and donation availability.

View donation history.

Recipient

Search for donors by blood group.

Request blood donations.

Track request status.

Administrator

Manage donors and recipients.

View and update blood stock.

Approve, reject, or manage blood requests.

Generate reports and oversee overall system activity.

Folder Structure
pgsql
Copy
Edit
Blood-Bank/
├── admin/
├── donor/
├── recipient/
├── config.php
├── index.php
├── login.php
├── register.php
├── blood_bank.sql
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
└── README.md
Contributing
Contributions are welcome.
If you find any bugs or want to improve the system:

Fork the repository

Create a new branch (git checkout -b feature-branch)

Commit your changes (git commit -m 'Add some feature')

Push to the branch (git push origin feature-branch)

Open a Pull Request

License
This project is licensed under the MIT License — see the LICENSE file for details.

Contact
Developed and maintained by John Maubi.
