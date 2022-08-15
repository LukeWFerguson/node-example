# node-example

## Running Locally

1) Make sure you have [Node](https://nodejs.org/en/) installed.
2) Run `npm install`.
3) Run `node server.js`.
4) Visit http://localhost:80/ to view the application.

> Reference: https://nodejs.org/en/docs/guides/getting-started-guide/

## Running via Docker

You will need to instal Docker on your local machine before running the below commands.

Build your Docker image:
```bash
docker build . -t simple-node-app
```

Run your Docker image:
```bash
docker run -p 49160:80 -d simple-node-app
```

Visit http://localhost:49160/ to view the application.

> Reference: https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
