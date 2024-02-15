Employee Management System
Overview

The Employee Management System is a web application built using Flask, MySQL, and Amazon S3. It allows users to add, update, and fetch employee information, including their images. The application stores employee details in a MySQL database and their images in an Amazon S3 bucket.
Features

    Add Employee: Users can add new employees by providing their details and uploading an image.
    Update Employee: Existing employee details can be updated.
    Fetch Employee Information: Users can fetch employee information by entering their ID.
    Display Employee Image: The application displays the image of the employee alongside their details.

Technologies Used

    Python
    Flask: Web framework for building the application.
    MySQL: Database management system for storing employee information.
    Boto3: Python SDK for interacting with Amazon Web Services (AWS).
    Amazon S3: Cloud storage service for storing employee images.


    To install:(commands)
        sudo dnf update -y
        sudo dnf install mariadb105
        sudo yum update -y
        sudo yum install git -y
        sudo dnf install python3
        sudo dnf install python3-pip
        pip3 install pymysql boto3
        sudo dnf install python3-flask
        sudo dnf install python3-pymysql
        sudo pip install PyMysql
        sudo python3 -m pip install boto3



Setup Instructions

    Clone the repository to your local machine.
    Install the required Python packages using pip install -r requirements.txt.
    Create a MySQL database and update the database connection details in the config.py file.
    Set up an Amazon S3 bucket to store employee images and update the bucket name in the config.py file.
    Run the Flask application using python3 EmpApp.py.
    Access the application in your web browser at http://localhost:8080.

File Structure

    EmpApp.py: Main Flask application file.
    config.py: Configuration file containing database and AWS S3 bucket details.
    templates/: Directory containing HTML templates for rendering pages.
    static/: Directory containing static assets such as CSS files and images.

Usage

    Navigate to the homepage of the application.
    Add new employees by filling out the form and uploading their image.
    Update employee details if needed.
    Fetch employee information by entering their ID.
    View employee details along with their image.
