# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To run the project, this are the steps you should follow: 
 - git clone git@github.com:ObelusFamily/Anythink-Market-4ahyc.git
 - cd Anythink-Market-4ahyc
 - docker-compose up

After this you can check the api by accessing http://localhost:3000/api/ping.
To ensure everything is connected, you can create a user by accessing http://localhost:3001/register and fill up the form and submit.
