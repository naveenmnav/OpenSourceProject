### Assignment 1 : Commands

1. docker --version -> Gives the docker version  
![1](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/1.JPG)
2. docker pull nginx -> Gets an image of NGinx from Docker Hub  
![2](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/2.JPG)
3. docker images a-> Lists all the images present in local  
![3](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/3.JPG)
4. docker run -d -p 80:80 nginx -> Runs a docker image at Ports 80 in local and also when docker is run  
![4](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/4.JPG)
5. docker ps -> List the containers running  
![5](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/5_new.JPG)
6. docker ps -a -> Lists all containers  
![6](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/6.JPG)
7. docker stop <<hashvalue of container>> -> Stops the container running    
![7](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/7.JPG)
8. docker rm  <<hashvalue of container>> -> Removes the container  
![8](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/8.JPG)
9. docker rmi <<image name>> -> Removes the image from the machine  
![9](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/9.JPG)
10. docker logs <<container id>> -f -> gets the logs from container  
![10](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/10.JPG)
11. docker create <<volume_name>> -> creates a volume  
![11](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/11.JPG)
12. docker volume ls -> lists the volumes present  
![12](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/12.JPG)
13. docker volume inspect <<volume name>> -> inspects the volume  
![13](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/13.JPG)
14. docker volume rm <<volume name>> -> removes the volume  
![14](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/14.JPG)
15. docker network prune -> removes all the networks used by any container  
![15](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/15.JPG)

### Assignment 2 :Running Hello World  
![Assignment 2](https://github.com/naveenmnav/OpenSourceProject/blob/main/Docker/Snaps/Assignment_2.JPG)



### Assignment 3:  FastAPI App and Docker Push to Hub

Check the files present


### Assignment 4 : 

Use this command
docker pull thehilifer/naveen_fast_api_docker_up:latest
