# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup


1. Install [Docker](https://docs.docker.com/get-docker/)
2. You can verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`.
3. Pull this repo to a directory on your local machine.
4. Run `docker-compose up` from the project root directory
5. Test that the backend is running by pointing your browser to http://localhost:3000/api/ping
6. Test that the frontend is working by pointing your browser to http://localhost:3001/register
7. Create a new user from the frontend home page.
