# docker_tutorial
description of docker
build docker image:docker build -t mlops-docker-demo .
Run the container:docker run -p 5000:5000 mlops-docker-demo
Tag your image:docker tag mlops-docker-demo ankitarajdeep/mlops-docker-demo:v1(userid from docker hub)
you are login:docker login
Push image to docker hub:docker push ankitarajdeep/mlops-docker-demo:v1  
pull image from docker hub:docker pull ankitarajdeep/mlops-docker-demo:v1 
Run pulled image:docker run -p 5000:5000 ankitarajdeep/mlops-docker-demo:v1
