# Todo List Program

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

![Todo List Program Screenshot](screenshot.png)

This is a Todo List program built with Django, which allows users to record and manage their daily tasks. The program provides a user-friendly interface to prevent forgetting important tasks. It also includes a REST API to retrieve data from the program. The project is Dockerized for easy deployment and management.

## Features

- **Todo List Management**: Users can create, update, and delete tasks in their todo list.
- **User Authentication**: The program uses the Django `AbstractBaseUser` to customize the user model, providing secure user authentication.
- **REST API**: The program includes a REST API for uploading and retrieving data from both the Todoapp section and the Accounts section.
- **Docker Support**: The project includes a Docker structure for easy deployment and management.

## Installation

1. Clone this repository to your local machine:

   bash
   git clone https://github.com/reza72rg/TodoApp
   2. Install the required dependencies:

   bash
   pip install -r requirements.txt
   3. Set up the database by running migrations:

   bash
   Build and run the Docker containers:
   4.docker-compose up --build

   bash
   python manage.py migrate
   5. Start the development server:

   bash
   python manage.py runserver
   6. Open the program in your web browser at `http://127.0.0.1:8000`.

## API Documentation

The API documentation can be found at `http://127.0.0.1:8000/api/v1/`, and http://127.0.0.1:8000/accounts/api/v1/ providing details on how to interact with the REST API endpoints.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Special thanks to [myself] for their assistance and feedback during the development of this project.rg
