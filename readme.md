# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Make sure you have [Docker installed](https://docs.docker.com/get-docker/). Once installed, run the following commands to ensure the installation went well: `docker -v` and `docker-compose -v`.

Next, in the root directory of this repo, run `docker-compose up`. Once the container is created and everything is running, test if the backend is up and running by going to <http://localhost:3000/api/ping>.

To test the frontend, go to <http://localhost:3001/register>. Assuming everything is working, please create a user.
