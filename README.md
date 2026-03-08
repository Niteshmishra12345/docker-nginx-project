# Docker Nginx Project

This is my first DevOps project.

## Tools Used
- Docker
- Git
- GitHub
- Nginx

## Project Description
I created a simple HTML web page and containerized it using Docker.

## Steps
1. Created index.html
2. Wrote a Dockerfile using nginx base image
3. Built Docker image
4. Ran container with port mapping

## Run the Project

docker build -t my-nginx .
docker run -d -p 8080:80 my-nginx
