# Static-Website-Using-Docker
Deploy Static Website using Docker

This repository demonstrates the process of containerizing and deploying a static website using Docker. It provides a practical guide for students and developers to gain hands-on experience with Docker's core functionalities, including image creation, container management, and pushing images to Docker Hub.

Features:

Dockerized Nginx Server: Utilizes an Nginx base image to serve the static website.

Dockerfile for Custom Images: Includes a Dockerfile to create a custom Docker image for the static website.

Local Deployment: Shows how to run and access the static website in a Docker container on a local machine.

Docker Hub Integration: Covers the steps to tag and push the custom Docker image to Docker Hub for sharing and distribution.

Comparison with VMs: Provides a clear distinction between Docker containers and Virtual Machines (VMs) for better understanding of containerization benefits.

Technologies Used:

Docker

Nginx

HTML/CSS/JS (for the static website content)

Getting Started:

Clone the repository:

Bash

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Build the Docker image:

Bash

docker build -t my-static-website .
Run the Docker container:

Bash

docker run -d -p 80:80 my-static-website
Access your website: Open your web browser and navigate to http://localhost.

Further Exploration:

Learn about Docker commands like docker images, docker ps, docker info, docker pull, docker login, docker tag, and docker push.

Explore Docker Swarm for orchestrating multiple containers.

This project serves as an excellent starting point for understanding Docker fundamentals and its application in deploying web applications.

