# docker-nginx-deploy

# NGINX Deployment on AWS EC2 using Docker

## 🚀 Overview
This project shows how to deploy a Dockerized NGINX web server on an AWS EC2 instance.

## 🔧 Technologies Used
- AWS EC2
- Docker
- NGINX
- Linux (Amazon Linux 2)

## 📝 Steps Performed
1. Launched EC2 instance
2. Installed Docker
3. Pulled NGINX image
4. Exposed port 80 to access NGINX
5. Verified site via public IP

## 📸 Screenshot
![Output](./screenshots/nginx-running.png)

## 📁 Project Structure


# NGINX Docker Deployment on AWS EC2

This project deploys the NGINX web server using Docker on an AWS EC2 instance.

## Steps

1. Launch an EC2 instance (Amazon Linux 2 or Ubuntu).
2. Install Docker:
   ```bash
   sudo yum update -y
   sudo yum install docker -y
   sudo systemctl start docker
   sudo systemctl enable docker

DockerFile

FROM nginx:latest
EXPOSE 80
