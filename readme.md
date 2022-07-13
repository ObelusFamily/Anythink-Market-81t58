# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Clone the Repository

    ```git clone https://github.com/ObelusFamily/Anythink-Market-81t58.git```

- Install Docker and Launch it after it is installed

    https://docs.docker.com/get-docker/

- Run ```docker-compose up -d``` from the root of the directory to launch the application

- Verify the backend application is running at http://localhost:3000/api/ping

- Verify, and create if possible, a user on the frontend app at http://localhost:3001/register