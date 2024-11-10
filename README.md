# Node.js Clock Docker Project

This project is a simple Node.js application that logs the current time to the console every second. The application is containerized using Docker, making it easy to deploy in any environment.

## Description

The `index.js` file contains a script that uses `setInterval` to repeatedly log the current time in `HH:MM:SS` format every second. This provides a continuous display of the current time in the console.

## Files

- `index.js`: Node.js script that logs the current time every second.
- `package.json`: Configuration file for the Node.js project, including dependencies and the start script.
- `Dockerfile`: Docker configuration file to build and run the application.

## Technology Version

- **Node.js**: Version 14 (specified in the Dockerfile)
- **Docker**: Compatible with the latest version (required for containerization)

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed on your machine.
