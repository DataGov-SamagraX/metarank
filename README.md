# Metarank Demo

This is a demo outlining how you can use Metarank in real-world scenarios. The code showcases how you can utilize deployed Metarank instance in your web application and covers ranking results, sending feedback and analyzing response.

## Prerequisites

The demo project utilizes [Node.js](https://nodejs.org) for the backend and [ReactJS](https://reactjs.org/) for the frontend, so you must have [Node.js](https://nodejs.org/) installed in order to run the project.
We also use [Yarn](https://yarnpkg.com/) for package management (`npm i -g yarn` for quick install).

## Running

### install the packages in the `frontend` and `server` folders
* `cd frontend && npm i`
* `cd server && npm i`

### run the backend
* use `METARANK_URL` environment variable to provide the URL of your Metarank installation in the format `http://localhost:8080`
* use `PORT` environment vvaraible to provide the port on which API will run. By default port 3001 is used
* `cd server && npm run start` to run application

### run the frontend
* `cd frontend && npm run start`. By default the frontend will run on port 3000