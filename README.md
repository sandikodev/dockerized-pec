## easies way to get stable development environment for django project!

## how to working with this project
1. requirement\
    a. [install docker](https://docs.docker.com/engine/install/)\
    b. [install docker-compose](https://docs.docker.com/compose/install/)
2. clone this project\
    `git clone git@github.com:sandikodev/dockerized-pec.git`
3. copy `env.example` to `.env`\
    `cp env.example .env`
4. start docker build by one click\
    `docker-compose up`
5. your services has been running!
6. how to migrate or makemigration\
    `docker-compose exec web python manage.py migrate`

## what's going on behind this project
1. `git submodule add git@github.com:adhamcahyo/lms_pec_jogja.git app`
2. `touch docker-compose.yml`
3. `cd app`
4. `fly launch`
