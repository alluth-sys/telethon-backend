### Introduction
* Python version: 3.9.7
* Developed using [Quart](https://quart.palletsprojects.com/en/latest/) Framework

### build the application

```
$ cd <the/path/of/the/application>
(you should see docker-compose.yml here)
$ docker-compose up --build
```

please install and build redis first following the instructions here: https://www.runoob.com/docker/docker-install-redis.html

the build command takes longer to run, as it runs the all setup commands for docker, as well as compiles the main application.

### Start the application

```
$ cd <the/path/of/the/application>
(you should see docker-compose.yml here)
$ docker-compose up
```

### Stop the application

```
$ cd <the/path/of/the/application>
(you should see docker-compose.yml here)
$ docker-compose down
```
