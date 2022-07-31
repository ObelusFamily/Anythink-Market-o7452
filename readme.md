# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Prerequisites
Make sure you have `docker` and `docker-composev1.25.5~` installed. Run `docker -v` and `docker-compose -v` to check the installation.

### Running the app
Run `docker-compose up -d` to start the app. The first run might take a few minutes, so be patient :)

Test by hitting http://localhost:3000/api/ping in the browser.
If the response is successful, try creating a new user at http://localhost:3001/register

Congratulations, your local Anythink Market is up and running!
