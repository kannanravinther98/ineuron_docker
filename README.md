# Docker Basics
## 1. For Docker virtualization should be enabled.
![image](https://user-images.githubusercontent.com/28582315/196292881-c50938e7-1f35-46e0-9ecc-12cd64683633.png)

## 2. docker -v
Gives the latest installest docker version in your machine.
![image](https://user-images.githubusercontent.com/28582315/196293091-32bd2b0b-5f82-4e98-bf51-6c7678d3d2ea.png)

## 3. docker images
![image](https://user-images.githubusercontent.com/28582315/196295920-1e69421c-9b84-489c-b3f2-4aec08c4bc89.png)

## 4.docker run -d -p 80:80 docker/getting-started

![image](https://user-images.githubusercontent.com/28582315/196295967-8c1162d0-fc5e-4684-8445-f7cc45f637b2.png)

## 5.docker ps
![image](https://user-images.githubusercontent.com/28582315/196296052-1f4bb9b9-15b4-419f-a1c5-1ab2ec7b8a98.png)

## 6. docker stop <container id>
![image](https://user-images.githubusercontent.com/28582315/196296097-3bc2044f-1c82-4aa1-a903-68ac8bce5395.png)

## 7.docker image rm -f <image id>
![image](https://user-images.githubusercontent.com/28582315/196296181-3090bea9-89e4-4b49-a7c5-0277f50198b8.png)

## 8.How to create Docker file in VScode
![image](https://user-images.githubusercontent.com/28582315/196304427-d7c83274-94fb-44eb-b269-ce1abda93957.png)

## 9.docker build -t username/dockername
This command is used to build the docker image. We try to create the name using username and then the image name user want.

## 10.docker push username/dockername:latest
This command is used to push the docker image locally build into docker hub.

## 11.docker restart
This command first stops the container and then automatically start it back.

## 12.docker ps -a
This command lists all the containers(running + exited)

## 13.docker top
This command shows the list of processes running inside a container

## 14.docker inspect
This command shows the low level info of the image

## 15.docker pull image name
This command pulls the docker image from docker hub in the local system
