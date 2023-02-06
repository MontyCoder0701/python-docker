# Flask Docker

Flask backend made with Python.  
Containerized with Docker.  
Deployed on Azure.  

## Running on localhost with Flask

```sh
py app.py
```

## Running on localhost with Docker

Build docker image

```sh
docker build -f Dockerfile -t flaskwebapp:latest .
```

```sh
docker run -p 5000:5000 --rm flaskwebapp
```

The site should be running on <http://localhost:5000/>

## Azure website

<https://python-docker.azurewebsites.net/>
