# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Install [Docker](https://docs.docker.com/get-docker/)
2. Confirm that you have Docker and Docker Compose installed and running. 
   1. Run `docker -v` and `docker-compose -v`
3. Once you've cloned the repository, run `docker-compose up` from the project root directory
   1. NB: If you get an error like `docker.errors.DockerException: Error while fetching server API version`, you probably forgot to start your Docker Desktop app
4. Once running, confirm your backend connection by [visiting]( http://localhost:3000/api/ping)
5. Then finally confirm your frontend connection by [visiting](http://localhost:3001/register)  