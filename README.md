# Online Examination System

It is a PHP based Online Examination Project. In this Student Ranking System is also introduced Student can see their ranks. A complete admin panel, Admin can add Quiz, Delete Quiz, Read Feedback by the user.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- User Authentication: Secure user authentication and registration system.
- Exam Creation: Easily create and manage different types of exams (e.g., multiple-choice, essay).
- Exam Scheduling: Schedule exams with specific start and end times.
- User Roles: Differentiate between administrators, instructors, and students.
- Exam Taking: Students can take exams within the specified time frame.
- Grading: Automatic grading for multiple-choice questions; manual grading for essays.
- Analytics: Generate reports and statistics for exam results.
- Security: Protect exam content and user data with encryption and access control.


## Installation

To set up the Online Examination System on your local machine, follow these steps:

This guide will walk you through the steps to set up and run a web-based project on XAMPP using localhost. XAMPP is a popular web server package that includes Apache, MySQL, PHP, and Perl.

## Prerequisites

- [XAMPP](https://www.apachefriends.org/) installed on your computer.

## Step 1: Install XAMPP
Download and install XAMPP from the official website based on your operating system (Windows, macOS, Linux).

## Step 2: Start XAMPP

Start the XAMPP control panel:

- On Windows, search for "XAMPP Control Panel" in the Start menu.
- On macOS and Linux, open a terminal and run:

  ```bash
  sudo /opt/lampp/lampp start
  ```

## Step 3: Start Apache and MySQL

In the XAMPP control panel, click the "Start" buttons next to Apache and MySQL to start the web server and database server.

## Step 4: Verify Apache Configuration

Open your web browser and visit [http://localhost](http://localhost). You should see the XAMPP welcome page, indicating that Apache is running correctly.

## Step 5: Create a Project Folder

Create a folder in XAMPP's "htdocs" directory to store Online based Examination folder. For example:

- On Windows:

  ```
  C:\xampp\htdocs\mywebsite
  ```

- On macOS and Linux:

  ```
  /opt/lampp/htdocs/mywebsite
  ```
## Step 6: Create a Database

Use PHPMyAdmin (http://localhost/phpmyadmin) to create a new database. Update your project's database configuration to use this database.

## Step 7: Access Your Project

Open your web browser and navigate to [http://localhost/Online-based-Examination]. You should see your web project running locally.
```

**## Usage**
Register as an administrator, instructor, or student.
Log in using your credentials.
Administrators can create exams, manage users, and view exam analytics.
Instructors can schedule exams, add questions, and grade essay questions.
Students can view their exam schedule, take exams, and view their results.
Customize the system according to your requirements by modifying the code and database structure.
