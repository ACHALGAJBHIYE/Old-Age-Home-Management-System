# Old-Age-Home-Management-System

### Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Flowchart/Workflow](#flowchartworkflow)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The **Old Age Home Management System** is a web-based application built using PHP and MySQLi that helps manage old age homes efficiently. This system allows admins to handle services, track senior citizens’ records, manage inquiries, and generate reports. Users can explore available services, review eligibility criteria, and contact the old age home. 

This project aims to improve the operational efficiency of old age homes and provide better care for senior citizens.

## Features

### Admin Module:
- **Dashboard:** Overview of total services, senior citizens, unread inquiries.
- **Manage Pages:** Add or update pages like 'About Us' and 'Contact Us,' as well as manage rules and eligibility.
- **Manage Services:** Add, update, or delete services provided by the old age home.
- **Senior Citizen Details:** Add, update, or delete details of the senior citizens living in the old age home.
- **Inquiry Management:** View and respond to both unread and read inquiries.
- **Search:** Search for senior citizen details using a registration number.
- **Reports:** Generate reports for senior citizens and services within a specific time frame.
- **Admin Profile Management:** Update profile information and change passwords.

### User Module:
- **Home Page:** Displays a welcome page with basic information.
- **Services:** Users can view the services offered by the old age home.
- **Eligibility:** View eligibility criteria for living in the old age home.
- **Rules:** Access the rules for the old age home.
- **About Us:** Read about the old age home.
- **Contact Us:** Users can contact the old age home for inquiries.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript, AJAX, jQuery
- **Backend:** PHP 5.6 / PHP 7.x
- **Database:** MySQL 5.x
- **Software:** XAMPP server
- **Web Browsers Supported:** Mozilla Firefox, Google Chrome, IE8, Opera

## Installation

### Prerequisites:
- XAMPP/WAMP/MAMP/LAMP installed on your system.
- PHP 5.6 or higher.
- MySQL 5.x or higher.

### Steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/old-age-home-management-system.git
    ```
2. Start your XAMPP server.
3. Copy the project folder into your server's root directory (`htdocs` for XAMPP, `www` for WAMP).
4. Open the project folder in your preferred code editor.
5. Create a MySQL database:
    - Open PHPMyAdmin (`localhost/phpmyadmin`).
    - Create a new database (e.g., `oahms_db`).
    - Import the provided SQL file (`database.sql`) from the `db` folder.
6. Update the database connection details in the `config.php` file to match your local setup:
    ```php
    $servername = "localhost:3307";
    $username = "root";
    $password = "";
    $dbname = "oahms_db";
    ```

7. Open the application in your browser:
    ```bash
    http://localhost/old-age-home-management-system
    ```

## Usage

### Admin Login:
- Visit `http://localhost/old-age-home-management-system/admin`
- Use the default credentials to log in:
  - **Username:** Admin
  - **Password:** Test@123
- Once logged in, the admin can manage services, senior citizen records, inquiries, and generate reports.

### User Access:
- Visit the home page at `http://localhost/old-age-home-management-system`
- Users can view the services, eligibility, rules, and contact information provided by the old age home.

## Flowchart/Workflow
```plaintext
Step 1: User/Admin logs into the system
       ↓
Step 2: Admin manages services, senior citizen records
       ↓
Step 3: User views services, rules, eligibility
       ↓
Step 4: User makes inquiries or contacts old age home
       ↓
Step 5: Admin tracks inquiries and generates reports ```

##Contributing
We welcome contributions to enhance this project! If you'd like to contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature/your-feature-name).
Create a new Pull Request.

-----------------------------------------------------------------------------------------------------------------------------------------------

Let's build something amazing together!
