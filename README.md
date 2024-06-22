# BookMarker API
## Purpose
I built this project with only one goal in mind understand authentication with JWT and API documentation with Swagger

## Tech Stack
BookMarker API is built using a combination of Python, JWT extended, swagger and Flask framework with postgresql database.

- **Python**: Backend logic.
- **JWT extended**: Token authentication.
- **Swagger**: Documentation.
- **Flask**: Powers the backend logic and facilitates server-side operations.
- **Postgres**: Serves as the database management system for storing application data.

## Requirements to run the project <br>
Kindly make sure you have following before proceeding to installation.
- **1.** Python 
- **2.** Text editor, VS code recommended
- **3.** Git
- **5.** Pip

## Installation
- **ubuntu@user:** git clone https://github.com/Neivanny1/bookmarker_api.git
- **ubuntu@user:** cd bookmarker_api
- **ubuntu@user:** create database and replace url QLALCHEMY_DB_URI in .flaskenv 
- **ubuntu@user:** python3 -m venv venv
- **ubuntu@user:** source venv/bin/activate
- **ubuntu@user:** pip install -r requirements
- **ubuntu@user:** flask shell ---> enters in flask shell
- **ubuntu@user:** from src import app
- **ubuntu@user:** db.create_all() ---> creates all tables in models to db
- **ubuntu@user:** flask run

  
Visit 127.0.0.1:5000 on your browser

## Contribution
Having issues with code or fixess to add feel free to fork the project and create a PR will review soon as recieved
## AUTHOR
Eric MWakazi

### Swagger Documentation page
<h2>Home</h2>
<br> <br><img src="https://github.com/Neivanny1/bookmarker_api/blob/main/screenshots/1.PNG" alt="Description of the embedded content"> <br> <br>
<h2> Endpoints </h2> 
<br> <br><img src="https://github.com/Neivanny1/bookmarker_api/blob/main/screenshots/2.PNG" alt="Description of the embedded content"> <br> <br>
