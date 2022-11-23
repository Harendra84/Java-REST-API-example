
# Kaiburr Assignment

## Task 1. Java REST API example
Implementd an application in java which provides a REST API with endpoints for searching,
creating and deleting “server” objects:

### Project Structure

![Screenshot_20221123_170354](https://user-images.githubusercontent.com/82948471/203539943-bb863d32-7de1-4643-9203-d2f409a3f6ea.png)

##### ● GET servers. Should return all the servers if no parameters are passed. When server id
is passed as a parameter - return a single server or 404 if there’s no such a server.

![Get All Server](https://raw.githubusercontent.com/Harendra84/assignment-kaiburr/main/screenshots/backend/get-all-data.png)

![404 Error server](https://raw.githubusercontent.com/Harendra84/assignment-kaiburr/main/screenshots/backend/404.png)

##### ● PUT a server. The server object is passed as a json-encoded message body. Here’s an
example:

![Update Server](https://raw.githubusercontent.com/Harendra84/assignment-kaiburr/main/screenshots/backend/put-data.png)

● DELETE a server. The parameter is a server ID.

![Delete Server](https://raw.githubusercontent.com/Harendra84/assignment-kaiburr/main/screenshots/backend/delete-data.png)

##### ● GET (find) servers by name. The parameter is a string. Must check if a server name
contains this string and return one or more servers found. Return 404 if nothing is found.
“Server” objects should be stored in MongoDB database.
Be sure that you can show how your application responds to requests using postman, curl or
any other HTTP client.

![Get server by name](https://raw.githubusercontent.com/Harendra84/assignment-kaiburr/main/screenshots/backend/data-by-name.png)

##### ● POST Create new Server:

![Post Server](https://raw.githubusercontent.com/Harendra84/assignment-kaiburr/main/screenshots/backend/post-data.png)


## Authors

- [@Harendra84](https://github.com/Harendra84)


## Demo

### https://hub.docker.com/repositories

