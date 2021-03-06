# Loucos F.C.

This project is the source code for the Loucos F.C. application.

The backend application is generated by [LoopBack](http://loopback.io).

The frontend application is generated by [create-react-app]().

# Requirements
- Node.JS
- Docker and docker-compose installed

# Stack

We are currently using:

- LoopBack v3 (for API)
- React (for front-end)
- Redux
- MongoDB (via Docker)

## Why use LoopBack?

This makes our backend API enterprise-ready. It forces a lot of useful patterns, and makes a CLI available to make the development more productive.

## Why use React?

This is the most powerful library for front-end development.

## Why use MongoDB?

This makes our database document oriented and highly scalable. Dynamics schemas are powerful for managing games data.

# How to install

First you will need to clone this repository.

After this, you will need to install all dependencies:

```
npm install
```

You will need to run the database service:

```
docker-compose up -d
```

After that you can finally run the backend service:

```
npm start
```