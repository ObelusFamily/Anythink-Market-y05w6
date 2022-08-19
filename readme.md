# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Yes I'm here to make your local installation process easier, follow these steps to install the docker & get the frontend & backend installed locally:

1. First Install Docker from Docker website
2. verify whether docker installed properly or not by entering docker --version or docker-compose --version on your cmdlet, if installed properly you docker version.
   3)Now its time to run docker in your root project file, go to the project you cloned & now enter docker-compose up , this loads Anythink's backend and frontend.
3. If Docker is working correctly, the backend should be running and able to connect to your local database.
   Let's test this by pointing your browser to http://localhost:3000/api/ping
   5)To check frontend ,http://localhost:3001/register.
