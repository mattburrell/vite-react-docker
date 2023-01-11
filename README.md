# vite-react-docker

Demo repo showing how to Dockerize a Vite React app and run as a static website using NGINX

## Dependencies

Make sure you have the following installed:

- [Node](https://nodejs.org/en/)
- [Docker](https://docs.docker.com/get-docker/)

The React app was bootstrapped using [Vite](https://vitejs.dev/).

## Installation and running locally

```sh
npm run install
npm run dev
```

## Building and running in Docker

```sh
docker build -t vite-app .
docker run -p 80:80 vite-app
```
