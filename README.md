# flight-booker

Flight Booker is a web app designed to facilitate flight booking for "Khan Airlines" users. The application provides functionalities for searching, booking, and managing flights, ensuring a seamless experience.

## Project Description

The flight-booker project aims to simplify the process of booking flights. Users can search for flights based on various criteria, book flights, and manage their bookings. The application is built with scalability and maintainability in mind, ensuring a smooth user experience.

## Features

- **Flight Search:** Users can search for flights based on their preferences.
- **Booking Management:** Allows users to book flights and manage their bookings.
- **User Authentication:** Secure user authentication for personalized experience.
- **Responsive Design:** Optimized for various devices and screen sizes.
- **Scalable Architecture:** Built with modern web technologies for scalability.

## Repository Structure

- `app/`: Contains the main application code.
- `config/`: Configuration files for the application.
- `db/`: Database schema and migration files.
- `public/`: Public assets such as images, stylesheets, and JavaScript files.
- `test/`: Test suite for ensuring code quality and functionality.
- `Gemfile`: Specifies the dependencies for the Ruby on Rails application.
- `README.md`: Documentation and instructions for the project.





Instructions to run:

To run the backend, navigate into the dbproj-backend folder, open it in your IDE, e.g. vscode
and run the following command in the terminal to install all dependencies:

npm install

Repeat the same process for the frontend, navigate into the dbproj-frontend, open it in your IDE
and run the following command in the terminal to install all dependencies:

npm install

To run the DB, you will need to use Postgres, simply run the entire setupSQL.sql file
in your database, it will make all the tables and populate them with the necessary data.
You should not run into any problem if the database is running on the default port 5432.

To run the backend, use the following command in the dbproj-backend directory:

npm start

Do the same for the frontend, use the following command in the dbproj-frontend directory:

npm start

This should open a page in the browser with the frontend running.

The backend is running on port 5000, and the frontend is running on port 3000.
