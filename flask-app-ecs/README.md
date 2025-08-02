vim Dockerfile
create a docker file

docker run -d -p 80:80  flaskapp
port matching n mapping with the container n the os ports 

docker ps 

docker logs container id

docker attach container id 
our terminal n containers terminal attaches 

 Docker stop container id
 unblock 



-enter into a container 
docker exec -it f9d2498a2f53 bash
bash-5.1# mysql -u root -p
show databases
mysql> create database devops;
exit out of container
exit - out of instance


7.Find all images
      Docker images


       docker run -itd ubuntu 
       to keep the img running in detached mode
       

 

  1.Install a new image
      Docker run -it image-name
  2.Start a new container
      Docker start image-name
  3.Stop a container
      Docker stop image-name
4.Run docker within the terminal
      Docker exec -it image-name bash 
5.List all active containers
      Docker container ls
6.List all containers
      Docker container ls -a
7.Find all images
      Docker images
8.Exit the terminal
    ctrl + D
9.Build a docker
    Docker build -t name
10.create your own netwrok
    Docker network create -d bridge name
