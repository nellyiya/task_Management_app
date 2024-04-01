# Simple Task Manager Web Application

This is a simple web application built using HTML, CSS, JavaScript and react. It allows users to add tasks, view the list of tasks,
mark tasks as completed ,edit and delete the tasks.

## Getting Started

To run the web application locally, simply run npm start in project terminal 
and the the `index.html` file  will open itself in a web browser.

## Dockerization

To containerize the application using Docker, follow these steps:

1. Build the Docker image:
docker build -t task-manager .

2. Run the Docker container:
 docker run -p 8080:8080 task-manager

## Deployed Application

The Docker image for this web application is available on Docker Hub: [task-manager](https://hub.docker.com/r/your-docker-hub-username/task-manager)

## Author
Nelly Iyabikoze
dockerhub link:https://hub.docker.com/repository/docker/nellyiyabikoze/task_management_app
