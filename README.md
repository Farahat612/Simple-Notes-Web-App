# Simple-Notes-Web-App

A simple Notes web app using Python and Django.

## Project Overview

This project serves as a practice during a learning journey. It allows users to perform various actions such as registration, login, logout, adding notes, viewing notes, updating notes, and deleting notes.

## Project Structure

The project directory structure is organized as follows:

- **Root Directory**: Contains the main project files.
    - **smartnotes Directory**: Contains project-specific files.
        - `asgi.py`: ASGI configuration for the project.
        - `settings.py`: Project settings file.
        - `urls.py`: URL configuration for the project.
        - `wsgi.py`: WSGI configuration for the project.
    - **home Directory**: Contains the main app files.
        - `admin.py`: Admin configuration for the app.
        - `apps.py`: Configuration for the app.
        - `models.py`: Database models for the app.
        - `tests.py`: Unit tests for the app.
        - `urls.py`: URL configuration for the app.
        - `views.py`: Views and logic for the app.
        - **templates Directory**: Contains HTML templates used in the app.
            - `authorized.html`: Template for the authorized persons page.
            - `login.html`: Template for the login page.
            - `logout.html`: Template for the logged out users page.
            - `register.html`: Template for user registration.
            - `welcome.html`: Template for the welcome page.
    - **notes Directory**: Contains the main app files.
        - `admin.py`: Admin configuration for the app.
        - `apps.py`: Configuration for the app.
        - `forms.py`: Forms used in the app.
        - `models.py`: Database models for the app.
        - `tests.py`: Unit tests for the app.
        - `urls.py`: URL configuration for the app.
        - `views.py`: Views and logic for the app.
        - **templates Directory**: Contains HTML templates used in the app.
            - `notes_delete.html`: Template for deleting a note.
            - `notes_detail.html`: Template for the details of a note.
            - `notes_form.html`: Template for adding note form.
            - `notes_list.html`: Template for displaying the notes.
    - `manage.py`: Django's command-line utility for project management.

## Getting Started

To run the CRM system on your local machine, follow these steps:

1. Clone the repository: `$ git clone <repository-url>`
2. Navigate to the project directory: `$ cd <project-directory>`
3. Install the required dependencies: `$ pip install -r requirements.txt`
4. Apply the database migrations: `$ python manage.py migrate`
5. Start the development server: `$ python manage.py runserver`
6. Open your web browser and visit `http://localhost:8000` to access the CRM system.

## Features

- User registration and authentication.
- User login and logout functionality.
- Add new notes to the app.
- View existing notes in a list format.
- Update and edit notes as needed.
- Delete unwanted notes from the database.

## Usage

- Register a new user account by accessing the registration page.
- Log in using your registered credentials.
- Add, view, update, and delete notes as needed.
- Log out when you're done using the app.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: `$ git checkout -b my-new-branch`
3. Make your changes and commit them: `$ git commit -am 'Add some feature'`
4. Push the changes to your branch: `$ git push origin my-new-branch`
5. Submit a pull request detailing your changes.

## Known Issues or Limitations

Currently, there are no known issues or limitations with this project.

## License

This project is licensed under the [MIT License](LICENSE).
