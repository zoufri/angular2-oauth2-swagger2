# angular2-oauth2-swagger2

There is a back end server (Spring Boot) with OAuth2 server and a basic Spring Rest web service (to retrieve users).


The front end (web) is an Angular2 app that performs a login by calling the back end oauth2 server.

# Install mongo db
Any version 3 will do.

# To build

mvn clean install (from top level).


# Start server
cd server
./start
http:localhost:8080

# Start web
cd web
npm install
npm start

http://localhost:3000


# Swagger
http://localhost:8080/v2/api-docs
http://localhost:8080/swagger-ui.html

