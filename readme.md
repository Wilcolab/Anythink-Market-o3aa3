# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.


## Getting started

### Prerequisite

* [Docker](https://docs.docker.com/get-docker/)
* [Docker Compose](https://docs.docker.com/get-started/08_using_compose/) – this comes included with Docker Desktop for Mac/Windows. You may need to install it manually on other platforms. 


1. `docker-compose up` – this may take some time on the first run as the docker images are downloaded. 
2. Verify the frontend is available at `http://localhost:3001`
3. Verify the backend is available at `http://localhost:3000/api/ping`