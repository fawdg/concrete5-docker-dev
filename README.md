Concrete 5 Development Docker environment


## Requirements

[Docker][]
[Docker compose][]

[Docker]: https://docs.docker.com/linux/
[Docker compose]: https://docs.docker.com/compose/install/

## Running the environment

    ./install # only run this the first time
    docker-compose up # run this command to start the environment CTRL+c shuts down the env

When both containers are fully booted go to [localhost:8000](http://localhost:8000) to install the site.

When asked for the database hostname use `db`

Database credentials are:

      MYSQL_DATABASE: concrete5
      MYSQL_USER: concrete5
      MYSQL_PASSWORD: concrete5