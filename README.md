# Student Attendance Management System

A desktop-based Student Attendance Management System built with Python, Tkinter, and MySQL.

## Features
- Admin and Teacher login
- Student management
- Attendance tracking
- Subject-wise teacher access
- Attendance reports

## Requirements
- Python 3
- MySQL Server
- mysql-connector-python

## Setup on Windows

1. Install Python and MySQL Server.
2. Create the database:
   ```sql
   CREATE DATABASE attendance_db;
   ```
3. Install the Python dependency:
   ```powershell
   py -m pip install -r requirements.txt
   ```
4. Set your MySQL connection details in PowerShell (use your own local password; never commit it):
   ```powershell
   $env:MYSQL_HOST="localhost"
   $env:MYSQL_USER="root"
   $env:MYSQL_PASSWORD="YOUR_MYSQL_PASSWORD"
   $env:MYSQL_DATABASE="attendance_db"
   ```
5. Start the app:
   ```powershell
   py main.py
   ```

The application creates its authentication tables during startup. Other required application tables must exist in the database. Use your own local database and records.
