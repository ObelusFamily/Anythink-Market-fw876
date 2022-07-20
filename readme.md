# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repository locally
2. Install Docker by following the instructions here: https://docs.docker.com/get-docker/
3. Ensure that docker and docker compose are installed and working by running "docker -v" and "docker-compose -v" in a fresh terminal
4. cd to the root of the repo and run the Docker Compose script with "docker-compose up"
5. If there were no errors and a build message saying webpack has been built appears you're done. Congrats!