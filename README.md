# Dockerized-AspNetCoreApi-Angular
Docker supported application Web Api and Angular App sample.
This will help you to create single container and multiple container app using docker-compose tool

# Pre Requisites:
1. Install Docker for Desktop
2. Install Node js
3. Install Angular CLI Make sure you have the latest version of Angular CLI installed.
4. Visual Studio Code
5. Visual Studio 2019 latest 

# Steps to dockerize Angular App

1. Create Angular Dockerfile 

2. Run docker build and docker run command as below
   Also you can use docker-compose to build and run the docker image using "docker-compose up" cmd.
   
3.Create and run Angular Docker-Compose file 

# Steps to dockerize ASP.Net Core Api

1. Create New project > Select ASP.Net Core Template in Visual Studio 2019 as below
2. Check the 'Enable Docker Support'. You can all do that after ading the project by right click the project and select Add.
3. Dockerfile created automatically in the Web Api project
4. Add another project webapp to the solution following the above steps
5. Create docker-compose file
6. Run docker-compose project from visual studio (Docker compose is used for creating multi service continase for micro service application)
    This will create the docker image for the Webapi anf Webapp into local docker host and run the docker container.

# Steps for creating multi service docker container (asp.net core web api + web app + angular app)
7. Modity docker-compose file in visual studio to add 'Angular app' as well
8. run the docker-compose
9. This will deploy all the three docker images for docker host


