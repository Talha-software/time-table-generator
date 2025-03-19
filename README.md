# Time Table Generator

## Overview
The **Time Table Generator** is a web-based application that allows users to generate, manage, and view timetables efficiently. The system includes an admin panel where administrators can configure schedules and assign resources.

## Features
- Automated timetable generation
- User-friendly interface
- Admin panel for managing schedules
- Secure authentication

## Installation

### Prerequisites
Make sure you have the following installed:
- PHP (>=7.4 recommended)
- MySQL Database
- Apache or any other web server
- Git

### Clone the Repository
To get started, clone the repository using the following command:
```sh
 git clone https://github.com/Talha-software/time-table-generator.git
```

### Setup Instructions
1. Navigate to the project directory:
   ```sh
   cd time-table-generator
   ```
2. Move the project files to your web server's root directory (e.g., `htdocs` for XAMPP or `/var/www/html` for Apache).
3. Import the database:
   - Locate the SQL file inside the project directory (e.g., `database.sql`).
   - Open **phpMyAdmin** or use the MySQL command line to create a new database and import the file.
   ```sql
   CREATE DATABASE timetable_db;
   USE timetable_db;
   SOURCE database.sql;
   ```
4. Configure the database connection:
   - Open the configuration file (e.g., `config.php`).
   - Set your database credentials (host, username, password, database name).

### Run the Application
1. Start your local server (XAMPP, WAMP, or LAMP).
2. Open your browser and go to:
   ```
   http://localhost/time-table-generator
   ```

## Admin Login
Use the following credentials to log in to the admin panel:
- **Username:** Admin  
- **Password:** Test@123

## Contributing
If you’d like to contribute:
1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m "Your commit message"
   ```
4. Push to your branch:
   ```sh
   git push origin feature-branch
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any issues or feature requests, please open an issue in the repository.

