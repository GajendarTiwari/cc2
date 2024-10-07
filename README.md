# Overview of the Project
The web application shown in this project was set up on an AWS EC2 instance. Along with extra credit features like file uploads, word count computation, and persistent user data storage, the application facilitates user registration, login, and profile management.

## Important Features

**User registration:** Collects email, first and last names, passwords, and usernames; securely stores this data in a SQLite3 database.

**Login**: Uses the user's username and password to confirm their identity.

**Profile**: Displays user information, including email, first and last names, and username. It shows the word count and offers a download link if a file has been uploaded.

**File upload**: Users can upload text files, which are safely saved on the EC2 instance, using the File Upload (Extra Credit) feature. The program determines and shows the files' word count.
