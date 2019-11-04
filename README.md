# Flask web chat application

## Modules

### Application
It is a basic web chat application which live updates and persistent storage using Flask(flask-socketio) and Mongodb.

[The source of application code](https://codeburst.io/building-your-first-chat-application-using-flask-in-7-minutes-f98de4adfa5d)

### Database
The Mongodb is represented as a tree nodes. There are one primary node and two secondary nodes.

[The source of docker config](https://37yonub.ru/articles/mongo-replica-set-docker-localhost)

## Make it work

Build images for database and application.

Image links:
[flask-web-chat](https://hub.docker.com/r/gafmnd/flask-chap-app)
[mongodb](https://hub.docker.com/r/gafmnd/mongo)

All containers have to be built from the proper Dockerfile.

`docker-compose up`

## Using Swarm

Containers can be deployed with this command

`docker stack deploy -c docker-compose.yaml web_chat`


# Report

Output of commands

```
rs.status()
rs.config()
```

## First step
Screenshot 2019-11-05 at 00.45.04


## Second step
Screenshot 2019-11-05 at 00.49.50

[Screenshots](https://github.com/gafmn/flask-web-chat/tree/master/screenshots)
