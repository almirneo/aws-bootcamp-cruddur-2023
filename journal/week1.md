# Week 1 — App Containerization

## Required HomeWork/Tasks

### Containerize Application (Dockerfiles, Docker Compose)

I was able to successfully carry out the Containerize Application following the video guidance.

![Proof of Working Containerize Application](assets/week-1-port-3000.png)

### Write a Flask Backend Endpoint for Notifications and React Page for Notifications

I was successfully able to add the endpoints and notification page.

![Proof of Working Endpoint and Page](assets/week-1-notification.png)

### Run DynamoDB Local and PostgreSQL local

I was successfully able to run both of database.

![Proof of Working DynamoDB](assets/week-1-dynamodb.png)

![Proof of Working PostgreSQL](assets/week-1-postgres.png)

## Homework Challenges

### Push and Tag a image to DockerHub

I pushed a image to DockerHub.

![Proof of Working Docker Hub](assets/week-1-docker-hub-image-push.png)

### Install Docker on your loalmachine

I already had docker installed on my personal machine.
I configured it via git and downloaded the entire repository locally, and built the images.

![Proof of Working Docker local](assets/week-1-docker-image-local.png)

I needed to change the environment variables, initially I couldn't get the frontend to run successfully.
I realized that I needed to install the npm manager and install the packages from the frontend directory.
After that, it was possible to upload the entire environment using Docker Compose.

![Proof of Working Docker Compose](assets/week-1-docker-compose-local.png)

![Proof of Working API Working local](assets/week-1-project-locall.png)

![Proof of Working App working local](assets/week-1-challenge-app-local.png)

### Launch an EC2 Instance that has docker installed and pull a container

I launched an EC2 instance and used bootstrap to install docker and was able to use the image I uploaded on Docker Hub.

![Proof of Lanch EC2 Instance](assets/week-1-challenge-aws-ec2-docker.png)
