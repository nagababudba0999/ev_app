# GITAM Transportation System

## Overview

The GITAM Transportation System is a web application designed to help users find and book available buses efficiently. It offers a user-friendly interface for searching buses based on source and destination, and allows users to book their seats directly.

## Features

- **Search Buses**: Users can search for available buses by selecting their source and destination.
- **Book Tickets**: Users can book tickets by entering their personal details and the number of seats required.
- **Responsive Design**: The application is designed to work seamlessly on both desktop and mobile devices.
- **Eco-Friendly Message**: Promotes eco-friendly transportation options.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (for interactivity)
- **Backend**: Flask (Python) for server-side logic
- **Database**: SQLite (or your choice of database)

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nagababudba0999/ev_app.git
   cd ev_app
   sudo yum install  pip -y 
   pip install flask
   pip install pymysql

### Update database settings in `config.py`
Before running the application, you need to update the `config.py` file with your database details. 

Modify the following fields with your MySQL database credentials:
class Config:
  MYSQL_HOST = 'your_host'           # Replace with your MySQL host (e.g., 'localhost' or IP address)
  MYSQL_USER = 'your_username'       # Replace with your MySQL username
  MYSQL_PASSWORD = 'your_password'    # Replace with your MySQL password
  MYSQL_DB = 'gitam_transportation_db'  # Keep this as is, or change to your desired database name

