# Komodo Hub

Komodo Hub is a children’s educational web platform developed as a group university project at Coventry University.

The platform combines interactive learning, endangered-animal education, games, user accounts, community posts and role-based dashboards in a rainforest-themed website.

## Project Overview

Komodo Hub was designed to make learning about endangered animals more engaging for children.

Users can create accounts, explore educational animal content, play interactive games, view community posts and collect points through activities.

Different account types provide different permissions and dashboard features.

## Main Features

* User registration and login
* Secure password hashing
* Role-based accounts for:

  * Students
  * Teachers
  * Members
  * Principals
  * Administrators
* Educational information about endangered animals
* Interactive children’s games
* Points and score tracking
* User profiles and avatars
* School and community posts
* Post creation and deletion
* Trusted role-based moderation
* Teacher and student access codes
* Simulated membership registration workflow
* SQLite database integration
* Responsive rainforest-themed interface

## Games

The platform includes interactive educational games such as:

* Word Search
* Jigsaw Puzzle

Game scores are saved to the user’s profile and contribute to their total points.

## Technology Stack

### Front End

* HTML
* CSS
* JavaScript

### Back End

* Python
* Flask
* Flask-CORS
* Werkzeug

### Database

* SQLite
* SQL

## Project Structure

```text
komodo-hub/
├── Web Pages/
│   ├── Images/
│   ├── Homepage.html
│   ├── RegisterPage.html
│   ├── LoginRegister.css
│   ├── JavaScript files
│   └── Additional pages and assets
├── KH_Database.db
├── Insert_Samples.sql
├── main.sql
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

## My Contribution

This was a group project.

My contributions included:

* Developing front-end features for the website
* Building interactive game functionality
* Contributing to the Word Search and Jigsaw Puzzle features
* Implementing score updates and points tracking
* Supporting database design and application structure
* Contributing to user-interface design
* Working as Product Owner during part of the project
* Working as Scrum Master during part of the project
* Participating in Agile planning, task management and team coordination
* Supporting system architecture and database-related decisions

The repository also contains contributions from other team members. Their work remains credited within the source code where applicable.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Riyaazx/komodo-hub.git
cd komodo-hub
```

### 2. Create a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

macOS or Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install the required Python packages

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python main.py
```

The application should open automatically in your browser.

It can also be opened manually at:

```text
http://127.0.0.1:5001/
```

## Database

The application uses:

```text
KH_Database.db
```

The included SQLite database contains the tables required by the application.

The database structure is also documented in:

```text
main.sql
```

Example demonstration data is stored in:

```text
Insert_Samples.sql
```

All usernames, passwords, access codes, school names and posts in the sample SQL file are fictional and intended only for demonstration purposes.

### Viewing the database

The database can be opened using DB Browser for SQLite:

https://sqlitebrowser.org/dl/

After installing the program:

1. Open DB Browser for SQLite
2. Select **Open Database**
3. Choose `KH_Database.db`
4. Open the **Browse Data** tab
5. Select a table to view its contents

## Security Features

The project includes:

* Password hashing using Werkzeug
* Parameterised SQL queries
* Role-based permissions
* User-type validation
* Restricted post-deletion permissions
* Access-code validation for student and teacher accounts

This is an educational prototype and has not been prepared for production deployment.

## Known Limitations

* The application uses a local SQLite database
* User sessions are handled through simplified prototype logic
* The membership payment process is a demonstration workflow
* The application has not been deployed to a production server
* Some user-interface features were designed primarily for desktop browsers
* The educational animal population figures are sample project data and may not represent current conservation statistics
* Additional security testing would be required before production use

## Future Improvements

* Add proper Flask session management
* Add email verification
* Improve mobile responsiveness
* Add automated testing
* Add stronger form validation
* Replace the simulated payment workflow with a secure payment provider
* Deploy the application online
* Add more educational games
* Improve accessibility support
* Add updated animal data from verified conservation sources

## Academic Context

Komodo Hub was developed as part of a Coventry University group project.

The repository is presented as a portfolio project to demonstrate experience in:

* Full-stack web development
* Flask development
* SQLite database integration
* Front-end development
* Role-based functionality
* Agile teamwork
* Product ownership
* Scrum coordination
* Educational game development

## Licence

This repository contains an academic prototype created for educational and portfolio purposes.

It is not intended for production or commercial use.
