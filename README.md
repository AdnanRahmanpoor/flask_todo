
# Flask To-Do Application

## Project Overview

This Flask To-Do application is a web-based task management tool that allows users to register, log in, and manage their tasks effectively. Built with Flask, SQLAlchemy, and Flask-Login, this project implements essential features for user authentication and CRUD operations on tasks, providing a practical example of web development using Python.

## Features Implemented

1. **User Registration and Authentication**:
   - Users can create an account with a unique username and password.
   - Secure password hashing using Werkzeug's `generate_password_hash`.
   - Login functionality with session management to keep users authenticated across sessions.
   - Users can log out of their accounts.

2. **Task Management**:
   - Users can create new tasks with titles and optional descriptions.
   - Tasks are displayed in a user-friendly interface, with options to update or delete tasks.
   - Tasks are associated with individual users, ensuring that users can only see and manage their own tasks.

3. **Database Management**:
   - The application uses SQLite as the database to store user information and tasks.
   - SQLAlchemy is utilized for ORM (Object Relational Mapping), enabling easy interaction with the database.

4. **Responsive UI with Bootstrap**:
   - The application uses Bootstrap for a responsive and visually appealing user interface.
   - HTML templates are rendered with dynamic data passed from the Flask application, enhancing user experience.

## Learning Outcomes

Building this Flask To-Do application has been a valuable learning experience, enhancing my skills in several areas:

- **Flask Framework**: I gained hands-on experience in developing web applications using Flask, understanding its structure and the request-response lifecycle.
  
- **User Authentication**: Implementing user registration and authentication helped me learn about session management and secure handling of user credentials.

- **Database Interactions**: Working with SQLAlchemy provided insights into how to perform CRUD operations, define relationships between models, and handle migrations effectively.

- **Front-End Development**: Integrating Bootstrap improved my understanding of front-end development, enabling me to create a responsive design that enhances user interaction.

- **Application Structure**: I learned the importance of organizing code within a Flask application using blueprints, which promotes maintainability and scalability.

## Future Improvements

While this project serves as a solid foundation for a task management application, there are several features I plan to implement in the future:

- **Task Categories**: Allow users to categorize their tasks for better organization.
- **Due Dates**: Enable users to set due dates for their tasks and receive notifications for upcoming deadlines.
- **User Profile Management**: Allow users to manage their profiles, including the option to change passwords.
- **Deployment**: Host the application on a cloud platform to make it accessible online.

## Usage

Clone this repo
```bash
git clone https://github.com/AdnanRahmanpoor/flask_todo.git
```

## Conclusion

This project has been a significant step in my journey as a developer. It has solidified my understanding of web development with Flask and equipped me with the skills necessary to create functional, user-friendly web applications. I look forward to enhancing this application and exploring new features in the future.