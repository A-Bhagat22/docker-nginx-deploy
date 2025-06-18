# docker-nginx-deploy

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
