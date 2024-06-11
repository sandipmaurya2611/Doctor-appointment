# Doctor-appointment
# Doctor Appointment Project

This repository contains a Doctor Appointment project built using PHP, MySQL, and CSS. The project aims to provide a platform for patients to schedule appointments with doctors online, simplifying the appointment booking process.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Doctor Appointment project is a web-based application that allows patients to search for doctors based on various criteria such as specialty, location, and availability, and schedule appointments with them online. It provides a convenient and efficient way for patients to book appointments without having to visit the clinic in person or make phone calls.

## Features

- **User Registration**: Patients can create accounts to book appointments.
- **Doctor Search**: Patients can search for doctors based on specialty, location, and availability.
- **Appointment Booking**: Patients can schedule appointments with doctors online.
- **Appointment Management**: Patients can view, edit, and cancel their appointments.
- **Doctor Dashboard**: Doctors can view their appointment schedule and manage appointments.
- **Admin Panel**: Admins can manage doctors, patients, and appointments.

## Technologies Used

- **Frontend**: PHP, CSS
- **Backend**: PHP
- **Database**: MySQL

## Prerequisites

- Web server with PHP support (e.g., Apache, Nginx)
- MySQL database server

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/doctor-appointment.git
    cd doctor-appointment
    ```

2. Import the SQL file (`database.sql`) into your MySQL database to create the required tables:

    ```bash
    mysql -u username -p database_name < database.sql
    ```

3. Configure your web server to serve the PHP files in the project directory.

4. Update the database configuration in the PHP files (`config.php`) with your MySQL credentials:

    ```php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'username');
    define('DB_PASSWORD', 'password');
    define('DB_NAME', 'database_name');
    ```

## Usage

1. Open the Doctor Appointment project in your web browser.
2. Patients can register for accounts and search for doctors to book appointments.
3. Doctors can log in to view their appointment schedule and manage appointments.
4. Admins can log in to access the admin panel and manage doctors, patients, and appointments.

## Project Structure

```plaintext
├── css/
│   ├── style.css          # CSS stylesheets
├── includes/
│   ├── config.php         # Database configuration
│   ├── db.php             # Database connection functions
├── js/
│   ├── script.js          # JavaScript functions
├── database.sql           # SQL file for database setup
├── index.php              # Main PHP file for the project
├── login.php              # Login page
├── register.php           # Registration page
├── README.md              # Project documentation
