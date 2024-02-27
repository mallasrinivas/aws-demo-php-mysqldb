# PHP and MySQL Form Submission Project

This project is a simple web application built with PHP and MySQL that allows users to submit their name and email through a form. The submitted data is then stored in a MySQL database.

## Features

- Collects user's name and email through an HTML form.
- Validates and sanitizes the input data.
- Inserts the submitted data into a MySQL database.
- Provides feedback to the user upon successful submission or error.

## Requirements

To run this project locally, you need:

- A web server with PHP support (e.g., Apache, Nginx).
- MySQL server for database storage.
- Basic understanding of PHP and MySQL.

## Installation

1. Clone or download this repository to your local machine.
2. Configure your web server to serve the project directory.
3. Import the MySQL database schema from the `database.sql` file to set up the required table structure.
4. Update the database connection details in the `index.php` file with your MySQL server credentials.

## Usage

1. Access the project through your web browser.
2. Fill out the form with your name and email address.
3. Click the "Submit" button.
4. You will receive feedback on whether the submission was successful or if there was an error.

## Security Considerations

- Avoid exposing sensitive information such as database credentials in the codebase.
- Implement proper validation and sanitization of user input to prevent SQL injection and other security vulnerabilities.
- Regularly update dependencies (e.g., PHP, MySQL) to patch security vulnerabilities.
