# Student Registration System

## Project Description

The Student Registration System is a Python-based application designed to manage student registrations efficiently. It utilizes an SQL database to store and retrieve student information. This system allows users to add new students, update existing student information, delete students, and view all registered students.

## Features

- Add new students
- Update student information
- Delete students
- View all registered students
- Search for a student by ID

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.x.
- You have installed MySQL.
- You have installed the necessary Python libraries: Tkinter

## Installation

To install this project, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/student-registration-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd student-registration-system
    ```

3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

5. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

6. Set up the database:

    ```bash
    python setup_database.py
    ```

## Usage

To use the Student Registration System, follow these steps:

1. Ensure the virtual environment is activated (if you created one).

2. Run the main application:

    ```bash
    python main.py
    ```

3. Follow the on-screen prompts to interact with the system.

### Example Commands

- **Add a new student**: Follow the prompts to enter student details.
- **Update student information**: Enter the student ID and update the necessary fields.
- **Delete a student**: Enter the student ID to remove the student from the database.
- **View all students**: List all registered students.
- **Search for a student**: Enter the student ID to retrieve their information.

## Database Schema

The SQLite database includes the following table:

- **students**:
  - `id` 
  - `name`

## Contributing

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Submit a pull request.



## Screenshots
* AdminLogin
![img](/img/AdminLogin.png)
* Main Windows
![img](/img/MainWindows.png)
* Student Login
![img](/img/StudentLogin.png)
* Version Number
![img](/img/VersionNumber.png)