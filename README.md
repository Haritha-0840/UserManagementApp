USER MANAGEMENT WEB APPLICATION

## Project Overview

This is a User Management Web Application developed using Python Flask and SQLite. The application allows users to perform basic CRUD (Create, Read, Update, Delete) operations through a simple and user-friendly web interface.

## Features

- Add new users
- View all users
- Edit existing user details
- Delete users
- Store data permanently using SQLite
- Responsive and simple user interface

## Technologies Used

- Python
- Flask
- HTML
- CSS
- SQLite

## Project Structure

```
UserManagementApp/
│── app.py
│── database.db
│── README.md
│
├── templates/
│   ├── index.html
│   └── edit.html
│
├── static/
│   └── style.css
│
└── screenshots/
    ├── home.png
    ├── add-user.png
    ├── add-user2.png
    ├── add-user3.png
    ├── edit.png
    ├── delete-user.png
    ├── after-edit.png
    └── database.png
```

## Project Workflow

1. User enters details in the form.
2. Flask receives the submitted data.
3. Data is stored in the SQLite database.
4. Stored records are retrieved from the database.
5. All user records are displayed in a table.
6. Users can edit or delete existing records.

## Installation

1. Clone the repository

```bash
git clone https://github.com/Haritha-0840/UserManagementApp.git
```

2. Open the project folder

```bash
cd UserManagementApp
```

3. Install Flask

```bash
pip install flask
```

4. Run the application

```bash
python app.py
```

5. Open your browser and visit

```
http://127.0.0.1:5000
```

## Screenshots

Screenshots of the application are available in the **screenshots** folder.

## Author

**Haritha Ramesh**

Python Full Stack Development Intern
