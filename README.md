# Student Attendance Management System

A desktop-based attendance management application developed with **Python, Tkinter, and MySQL**.

## Project Overview

The application is designed to help manage student records and maintain attendance information through a desktop interface. It includes separate admin and teacher access workflows.

## Features

- Admin and teacher login
- Add and manage student records
- Record student attendance
- Subject-wise teacher access
- Attendance reports
- MySQL database connectivity

> Feature availability depends on the current application build and database setup.

## Technology Stack

| Area | Technology |
|---|---|
| Programming language | Python 3 |
| Desktop interface | Tkinter |
| Database | MySQL |
| Database connector | mysql-connector-python |

## Requirements

- Windows, macOS, or Linux
- Python 3
- MySQL Server
- Python package: `mysql-connector-python`

## Setup (Windows)

### 1. Clone the repository

```powershell
git clone https://github.com/umesh-rathod123/Student-Attendance-Management-System.git
cd Student-Attendance-Management-System
```

### 2. Create the database

Open MySQL and run:

```sql
CREATE DATABASE attendance_db;
```

### 3. Install dependencies

If the repository contains a `requirements.txt` file:

```powershell
py -m pip install -r requirements.txt
```

Otherwise, install the connector directly:

```powershell
py -m pip install mysql-connector-python
```

### 4. Configure database credentials

Set your own local MySQL credentials in PowerShell. Do not publish your database password.

```powershell
$env:MYSQL_HOST="localhost"
$env:MYSQL_USER="root"
$env:MYSQL_PASSWORD="YOUR_MYSQL_PASSWORD"
$env:MYSQL_DATABASE="attendance_db"
```

### 5. Run the application

```powershell
py main.py
```

## Security Notes

- Use your own local database credentials.
- Never commit passwords, API keys, or real student records.
- Use fictional/sample student data when demonstrating the project publicly.

## Author

**Umesh Rathod**  
GitHub: [@umesh-rathod123](https://github.com/umesh-rathod123)

---

*An academic project focused on Python desktop development and database management.*
