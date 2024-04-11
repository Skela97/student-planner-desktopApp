## University Obligations Assistant (University Project - 2021)

This project is designed to help university students manage their academic obligations effectively through a client-server desktop application. The project has been extended to serve as a component of a bachelor's thesis, which is included within the project repository.

### Overview

- **Admins:** Manages subjects and projects.
- **Subjects:** Represent different areas of study within the curriculum.
- **Projects:** Specific tasks or assignments within Subjects that Students work on as part of their learning journey.
- **Students:** Manages plans and plan items.
- **Plans:** -  Plan is created for a subject.
- **PlantItems:** - Plan items are created for specific projects within the subject.

### Architecture

The project consists of three main components:

- **Server:** This handles the backend logic endpoints.
- **Client:** This is the frontend application that students will interact with.
- **Common:** Contains shared code and utilities used by both the server and client.

### Technologies
- **Java SE** - Used for providing essential libraries and runtime environment.
- **MySQK** - Used for storing and managing application data.
- **JDBC** - Used to connect and interact with database.
- **Swing** - Used for UI development.
- **Sockets** - Used for communication between client and server part of the application.

Additionally,`initdb.sql` file is provided to set up the project's database schema and populate it with initial data.
