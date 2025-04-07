# Simple Notes App
This is a simple notes app built with React and Django.

# install the requiremnts 
apt update -y
apt install docker.io -y
apt intall docker-compose-v2 -y 
apt install nginx and enable nginx

## Installation
1. Clone the repository
```
git clone https://github.com/coding-chandan/django-web-app-with-nginx-mysql.git
```

## Build the app using Dockerfile
```
docker build -t <name> .
```

# Run the app using Docker image
```
docker run -d -p 8000:8000 <name>:latest
```
# run the application using docker compose 
...
docker compose up --build ( if building the image firstly )
docker compose up ( to run the application using docker compose )

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`
