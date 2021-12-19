# Todo Application using the PERN stack 
## Application functionality 
The application allows a user to add, update, and remove todos from their list.
The app uses a Postgres database to store data in the backend, an Express server to access the database and a ReactJS frontend

## Prerequisites
- PostgreSQL (newest version)
- NodeJS
- npm/npx

## How to run the app
- Download the zip file from GitHub
- Extract the file to a location of your choosing 
- Open the database.sql file in the server directory
- Copy the contents and run it in psql command line to create the database needed for the app
- Open a terminal and navigate to the server directory (e.g. `cd /server`)
- Run `npm i` to install the required dependencies
- Run `npm start index` in the server directory to execute the server
- Open a new terminal and navigate to the client directory (e.g. `cd /client`)
- Run `npm i` to install the required dependencies
- Run `npm start` in the client directory to execute the frontend
- In a web browser open http://localhost:3000 to access the application frontend
- The app is now usable