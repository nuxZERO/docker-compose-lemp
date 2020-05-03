# Docker Compose for LEMP stack

The template for using LEMP stack with Docker Compose.


## Installation

- Copy `.env-sample` file and rename it to `.env`. So, you can change values to your config.
- Install `docker-compose build` and `docker-compose up -d`.
- Start all container `docker-compose start`.
- Stop all container `docker-compose stop`.
- Destry all container `docker-compose down`.
- Shell to container `docker exec -it mysql sh` and `mysql -u user -p password`.


## Environments

- nginx
- phpfpm
- mysql


## Default Database connection

- `DATABASE_NAME=database`
- `DATABASE_HOST=dockerdb`
- `USER=root`
- `PASSWORD=root`
