# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Clone this repo.

**Install Docker
For Manjaro: `sudo pacman -S docker`

**Install docker-compose
For Manjaro: `sudo pacman -S docker-compose`

Run the containers using the docker-compose config file. 
cd to root dir of cloned repo & run `docker-compose up`

To test this has worked try navigating to `http://localhost:3001/register`