# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the database.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To run the proyect locally, you'll need to install [Docker](https://docs.docker.com/get-docker/) in your machine.  
  - Verify that Docker is ready by running the following commands in your terminal `docker -v` and `docker-compose -v`.  
Now, to load the back and fronted run `docker-compose up` from the project root directory.  
  - Test if the backend is working propertly, click [here](http://localhost:3000/api/ping).  
  - Test if the frontend is running by clicking [here](http://localhost:3001/register) and creating a new user.
