# Grocery Aid

## About
UIUC CS 411 Database Systems group project. A web app for exploring grocery store products and prices. 

## Built With
* Node.js
* React.js
* Typescript
* MySQL
* Docker

## Getting Started - Running with Docker

### Prerequisites 
* Docker

### Running the project
* Create a copy of the `docker-template.env` and name it `.env`
* Edit `.env` to change passwords to something more secure
* Run `docker compose up -d` to start the app (this may take a while due to the need to populate the database)
* App should be accessible on the port set in the `.env` file
