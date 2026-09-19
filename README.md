# Project 4 - Dockerized Application Deployment on AWS EC2

## Project Overview

This project demonstrates how to deploy a Dockerized web application on an AWS EC2 Ubuntu server.

## Technologies Used

- AWS EC2
- Ubuntu
- Docker
- Nginx
- Docker Hub
- GitHub

## Architecture

Application  
↓  
Dockerfile  
↓  
Docker Image  
↓  
Docker Hub  
↓  
AWS EC2  
↓  
Docker Container  
↓  
Nginx  
↓  
Web Browser

## Project Steps

1. Created an AWS EC2 Ubuntu instance
2. Installed Docker
3. Created a simple HTML application
4. Created a Dockerfile using Nginx
5. Built the Docker image
6. Ran the application inside a Docker container
7. Configured HTTP port 80
8. Tested the application
9. Tagged the Docker image
10. Pushed the Docker image to Docker Hub
11. Added the project to GitHub

## Docker Image

Docker Hub:

jjebinlal/project4-docker-aws

## Docker Commands

### Build Docker Image

```bash
docker build -t project4-docker-aws .
