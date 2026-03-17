# Weather App - DataOps

## Description

Mouse meow meow you are my owner so here is a dead rat and climb leg poop on floor and watch human clean up, yet attack dog, run away and pretend to be victim and it's 3am, time to create some chaos but poop on the floor, break a planter, sprint, eat own hair, vomit hair, hiss, chirp at birds, eat a squirrel, hide from fireworks, lick toe beans, attack christmas tree.

## Installation

- Clone this repo
- On your terminal 
    - `cd` to root folder
    - delete data folder to start your own
    - setup `.env` with:
        - `PORT` of your choosing
        - `CITY` of your choosing
        - `API_KEY` from openweather
    - `npm i` to install dependencies
    - `node fetchWeather.js` to create/update data folder
    - `node app.js` to start server
- Open browser on `PORT` to see weather and graph

### Using Docker

- Open your Docker Desktop
- Make sure you are on same path as Dockerfile
- On your terminal run:
    - `docker build -t <app-name>:<tag> .` or `docker build -t weatherapp:1.0 .` - to build an image based on Dockerfile
    - `docker run -p <local-port>:<container-port> <image-name>` or `docker run -p 3000:5000 weatherapp` - to run a container based on an image


## Tests

We have tests to check if files inside the data folder is correct