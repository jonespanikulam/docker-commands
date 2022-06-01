# docker-commands
Docker

Install docker: https://docs.docker.com/desktop/windows/install/

![image](https://user-images.githubusercontent.com/59678465/171041667-3709573d-c389-4a58-b289-9410eb3ed19f.png)

![image](https://user-images.githubusercontent.com/59678465/171041707-742b7159-bc11-46b6-9304-c883ff02766b.png)

docker ps = list of running docker container

docker pull <image> = image can be from docker hub. pull used to donwload the image to your system
  
docker run <image>=  to run the image in a container. if image not present locally it is pullled from the docker hub
  - docker run -d <image> = run image in new container
  
docker stop <id of container>
docker start <id of the container>
docker ps -a  = Gives all the container that are running and not running.
  

When there are two containers needed to be running in the same ports, we have to bind different host ports to bind.  
  
![image](https://user-images.githubusercontent.com/59678465/171157965-90d605f0-ccf1-49ba-ae72-22bcdf84d06c.png)
  
Binded two ports for the redis containers.
  
  ![image](https://user-images.githubusercontent.com/59678465/171160994-94a163b5-f939-4331-9e67-75436d4160d6.png)

  
docker logs <container id>

![image](https://user-images.githubusercontent.com/59678465/171174928-a3584199-98d8-433f-98de-1aba8e6afeb6.png)
    
  
Name is added randomly when ran. But we can add name to container while running image
  
  ![image](https://user-images.githubusercontent.com/59678465/171174394-c85a82d7-bf15-4868-8004-16430200f599.png)
  
  
docker exec can be used to enter the bash mode of container for debugging
  
  ![image](https://user-images.githubusercontent.com/59678465/171179562-8fe310e2-48f8-4e2b-ab8a-6264e7ff2740.png)
  
  



