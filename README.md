# Marchettidockerproject
RESTful Web Service in Docker container

This RESTful webservice accepts, retrieves, and deletes user information from a website. This repository is also made to be opened in a docker container.

The docker-compose.yml file may need to be changed to the host computer's working directory under the environment variable MONGO_DATA_DIR. Run this web service with docker-compose up command in your terminal/command prompt window. The Docker file contains a link to MongoDB as well as the command, "npm start," in order to start the web service. 

To view the web service, enter in your browser http://localhost:3000 . Feel free to add and delete from the database, whether it be from the running web service or the mongo command prompt. 

Thank you for viewing my project and please feel free to let me know if there are any questions!
