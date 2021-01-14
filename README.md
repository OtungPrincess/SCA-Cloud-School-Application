# SCA-Cloud-School-Application

# Instructions and documentations for the deployment

A dockerfile and docker-compose, python file and python requirement documents were created using notepad++ and saved in a folder. The four files are needed to create a web application.
The python file contains lines of code that displays "Welcome to SCA Cloud School Application" in a webpage.
The requirements helps to install flask and redis.
The dockerfile is used to create docker images.
The docker compose contains the services (web and redis).

To run both of these services(containers), the "docker-compose up" is inputed in the windows powershell and run.
After this has been run, a docker image named "myapp_web" was created. 
The output is shown on the docker desktop while the webapp is run on a web browser using  "localhost:5000".
This same process is repeated to create the text "Welcome to SCA Cloud School Application, this is my first assessment" in a webpage. The docker image created for this is named "myapp1_web".

After this, a repository named "sca" was created in dockerhub with a path "otungprincess/sca"
A tag was created using the command "docker tag myapp1_web otungprincess/sca:latest"
The docker image created was pushed to docker-hub using the command "docker push otungprincess/sca:latest"
The pushed docker image is seen in the below link. 

# Access to my docker-hub repository
https://hub.docker.com/repository/docker/otungprincess/sca


