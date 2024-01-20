# docker-compose
A set of docker-compose files for a variety of project

### Requirements
You must have installed and set on your computer:
- [Docker](https://www.docker.com/get-started/)
- [Docker Compose](https://docs.docker.com/compose/). Should already be installed with docker.

### How to use it
- Add a docker-compose.yml file under the root directory of your project.
- Add the content of the docker-compose file
- under the folder where reside the docker-compose file, run the command `docker compose up`. 

```shell
# Execute the docker-compose file, create and configure the containers
$ docker compose up -d
# `-d` for detach. That run the command on background

# Start the services (containers) set in the compose file
$ docker compose start

# Stop the services (containers) set in the compose file
$ docker compose stop

# Remove all the services (containers) set in the compose file
$ docker compose down
```

### MySQL

[docker-compose.yml](/mysql.docker-compose.yml)

### PostgreSQL (Alpine Linux Container)

[docker-compose.yml](/postgres.docker-compose.yml)

### PostgreSQL + PGadmin

[docker-compose.yml](/postgres.pgadmin.docker-compose.yml)

### PostgreSQL + Adminer

[docker-compose.yml](/postgres.adminer.docker-compose.yml)


### Collaboration

Please submit your pull requests. They are all WELCOME. 
    
> Together for a World even BETTER.

Main maintainer [christian80gabi](https://github.com/christian80gabi)
This project is under the [MIT Licence](/LICENSE).