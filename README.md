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
1. Create Angular app in VS code editor using @angular/cli cmd
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/angular_1.png)
   
2. Create Angular Dockerfile 
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/angular_2.png)

3. Run docker build and docker run command as below
   Also you can use docker-compose to build and run the docker image using "docker-compose up" cmd.
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/angular_3.png)
   
4.Create and run Angular Docker-Compose
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/angular_4.png)
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/angular_5.png)
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/angular_6.png)

# Steps to dockerize ASP.Net Core Api

1. Create New project > Select ASP.Net Core Template in Visual Studio 2019 as below
2. Check the 'Enable Docker Support'. You can all do that after ading the project by right click the project and select Add.
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/aspnetcore1.png)
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/aspnetcore2.png)
3. Dockerfile created automatically in the Web Api project
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/aspnetcore3.png)
4. Add another project webapp to the solution following the above steps
5. Create docker-compose file
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/aspnetcore4.png)
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/aspnetcore5.png)
8. Run docker-compose project from visual studio (Docker compose is used for creating multi service continase for micro service application)
    This will create the docker image for the Webapi anf Webapp into local docker host and run the docker container.
    ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/aspnetcore7.png)

# Steps for creating multi service docker container (asp.net core web api + web app + angular app)
7. Modity docker-compose file in visual studio to add 'Angular app' as well
   ![alt text](https://github.com/nrawat207/Dockerized-AspNetCoreApi-Angular/blob/main/docs/aspnetcore6.png)
9. run the docker-compose
10. This will deploy all the three docker images to docker host 


