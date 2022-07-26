# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker
2. verify Docker is installed with "docker -v" and "docker-compose -v" from the terminal
3. Start Docker (eg. Docker for Windows) if not already started
4. From the project root directory, run "docker-compose up"
5. Once finished  - open up http://localhost:3000/api/ping to make sure the server is up
6. Open the frontend at http://localhost:3001/register and test you can create a new user
7. Make sure to run any scripts in one of the container you created only - you can use docker exec to run commands on running containers
