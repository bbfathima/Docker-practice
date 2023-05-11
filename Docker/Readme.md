Docker (Day-3 Tasks).

The below steps indicates the docker installation , build and container running

![preview](images/1.png)

Task-1: create a MySQL dB container from official MySQL image 

1. Create an instance
2. Install Docker in Instance (till docker login)
3. Here we are pulling the mysql image from docker hub with the help of command
 docker run --name mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:8.0
 
![preview](images/2.PNG)

![preview](images/3.PNG)
   By this above command all the mysql images get pulled from the docker hub

   OR

We can simply write docker pull mysql:latest version image from docker hub
After this run the container 
and see the image on 33306 port


Task-2: login into SQL container and create a table 

![preview](images/4.PNG)

The above image indicates entering into sql container with the help of command written as  mysql -u root -p and giving password to it

b) Creation of table:
For this first we need to create mysql batabase with the help of commands

![preview](images/5.PNG)

The above image represents creation of database and using of it
