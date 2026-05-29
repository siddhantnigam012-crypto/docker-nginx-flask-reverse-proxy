# Docker Nginx Flask Reverse Proxy Project

A containerized Flask web application running behind an Nginx reverse proxy using Docker Compose.

## Architecture

User
 |
 v
Nginx Container (Port 80)
 |
 v
Docker Network
 |
 v
Flask Container (Port 5001)


## Technologies Used

- Docker
- Docker Compose
- Nginx
- Python Flask

## Features

- Custom Docker image for Flask application
- Multi-container setup
- Nginx reverse proxy
- Internal Docker networking
- One command deployment using Docker Compose

## Run Project

Start:

docker compose up

Stop:

docker compose down


Access:

http://localhost:8080
