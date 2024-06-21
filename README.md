# Library Management System

## Introduction

The Library Management System is a software application designed to manage and automate the operations of a library. It helps in cataloging, tracking circulation (borrowed/returned books), managing member accounts, and more. This system is intended to make library management more efficient and user-friendly.

## Features

- **Book Management**: Add, edit, delete, and search for books in the library's catalog.
- **Member Management**: Manage library members, including adding new members, updating member information, and tracking member borrowing history.
- **Circulation Management**: Handle the borrowing and returning of books, including due dates, fines, and reservation management.
- **Reporting**: Generate reports on book circulation, member activity, and inventory status.
- **User Authentication**: Secure login for librarians and library staff with different levels of access.

## Technologies Used

- **Backend**: Python
- **Database**: SQL (MySQL, PostgreSQL, or SQLite)
- **Version Control**: Git

## Installation and Setup

### Prerequisites

- Python (version 3.x)
- PyCharm IDE
- SQL database (MySQL, PostgreSQL, or SQLite)

### Steps

1. **Clone the repository**
    ```sh
    git clone https://github.com/yourusername/library-management-system.git
    cd library-management-system
    ```

2. **Open the project in PyCharm**
    - Launch PyCharm.
    - Open the cloned repository folder as a new project.

3. **Create a virtual environment**
    - PyCharm usually prompts you to create a virtual environment when opening a project. Follow the prompts to set up a virtual environment.

4. **Install dependencies**
    - Open the terminal within PyCharm and run:
      ```sh
      pip install -r requirements.txt
      ```

5. **Set up the database**
    - Create a database and update the configuration file with your database credentials.
    - Run database migrations:
      ```sh
      python manage.py migrate
      ```

6. **Configure environment variables**
    - Create a `.env` file in the root directory and add the required environment variables (e.g., database credentials, secret key):
      ```
      SECRET_KEY=your_secret_key
      DATABASE_URL=your_database_url
      ```

7. **Run the application**
    - In PyCharm, locate the `manage.py` file.
    - Right-click on `manage.py` and select "Run 'manage.py'".
    - In the terminal, you can also run:
      ```sh
      python manage.py runserver
      ```

8. **Access the application**
    - Open your web browser and go to `http://127.0.0.1:8000` to access the Library Management System.

## Usage

1. **Admin Login**
    - Use the admin credentials to log in.
    - Add books, manage members, and handle book circulation.

2. **Member Registration**
    - Register new members with the required details.

3. **Book Management**
    - Add new books with details such as title, author, genre, and ISBN.
    - Edit or delete existing book records.

4. **Borrowing and Returning Books**
    - Issue books to members and track due dates.
    - Manage the return of books and handle any fines for overdue items.

5. **Reports**
    - Generate reports on book circulation, member activity, and inventory status.

## Contributing

We welcome contributions to improve this project. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

# Here is the example how this Project will give output

![Screenshot 2024-06-21 164552](https://github.com/RudraArora/Library-management-System/assets/100142404/8fd125ea-375a-4ad7-9fde-bc76d168c3d9)


