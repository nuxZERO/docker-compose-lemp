# Docker Compose for Wordpress

The template for using Wordpress with Docker Compose.


## Installation

- Install `docker-compose up -d`.
- Start all container `docker-compose start`.
- Stop all container `docker-compose stop`.
- Destry all container `docker-compose down`.
- Shell to container `docker exec -it mysql sh` and `mysql -u user -p password`.


## Environments

- nginx
- phpfpm
- mysql


## Database connection

- `DATABASE_NAME=database`
- `DATABASE_HOST=dockerdb`
- `USER=root`
- `PASSWORD=123456`
