# Assignment 11 Docker File
#Arshpreet Kaur

This project runs a Create React App website using Docker.

## Website

The website displays:

<h1>Codin 1</h1>

## Container Name

kaur_arshpreet_coding_assignment11

## Workdir

kaur_arshpreet_site

## Run Instructions

Build the Docker image:

```bash
docker build -t assignment11-react .
```

Run the Docker container:

```bash
docker run --name kaur_arshpreet_coding_assignment11 -p 7775:3000 assignment11-react
```

Open in browser:

http://127.0.0.1:7775