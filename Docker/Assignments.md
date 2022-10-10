### Assignment 1 : Commands

1. docker --version -> Gives the docker version

2. docker pull nginx -> Gets an image of NGinx from Docker Hub

3. docker images a-> Lists all the images present in local

4. docker run -d -p 80:80 nginx -> Runs a docker image at Ports 80 in local and also when docker is run

5. docker ps -> List the containers running

6. docker ps -a -> Lists all containers

7. docker stop <<hashvalue of container>> -> Stops the container running

8. docker rm  <<hashvalue of container>> -> Removes the container

9. docker rmi <<image name>> -> Removes the image from the machine

10. docker logs <<container id>> -f -> gets the logs from container

11. docker create <<volume_name>> -> creates a volume

12. docker volume ls -> lists the volumes present

13. docker volume inspect <<volume name>> -> inspects the volume

14. docker volume rm <<volume name>> -> removes the volume

15. docker network prune -> removes all the networks used by any container


### Assignment 2 :Running Hello World




### Assignment 3:  FastAPI App and Docker Push to Hub

Check the files present and also the below screenshot

### Assignment 4 : 

Use this command
docker pull thehilifer/naveen_fast_api_docker_up:latest