Timetable Generation System
Project Overview
The Timetable Generation System (TTGS) is a web application built using the Django Framework and SQLite as its database. The system leverages a genetic algorithm to optimize the generation of timetables while adhering to both soft and hard constraints.

The application features a simple authentication and authorization module, allowing users to access the admin dashboard upon successful login.

Key Features:
From the admin dashboard, users can input essential data required for timetable generation. The following details must be provided:

Teachers
Classrooms
Timings
Courses
Departments
Sections
Once the data is entered into the SQLite database, users can navigate to the "Generate Timetable" page, where the system generates an optimal timetable. Upon successful generation, the timetable can be downloaded in PDF format.

Technologies Used:
HTML5
CSS3
Python 3.8
Django 3.0.*
JavaScript
SQLite3
Running the Project:
Clone the repository.
Open the project using an IDE (e.g., PyCharm, Spyder) or command line.
Navigate to the project directory.
Run the command: python manage.py runserver.
Open your web browser and access the application at http://127.0.0.1:8000/.
