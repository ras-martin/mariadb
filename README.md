# Docker-Image for MariaDB based on Alpine Linux

* [GitHub](https://github.com/ras-martin/mariadb)
* [DockerHub](https://hub.docker.com/r/rasmartin/mariadb)

## Architectures
* Tag `amd64` or `latest`
* Tag `arm` (armhf, arm32v7) for 32-bit ARM-architectures (e.g. Raspberry Pi)

## Environment Variables
* `MYSQL_ROOT_PASSWORD`: set the specified root password
* `MYSQL_RANDOM_ROOT_PASSWORD`: generate a random root password for MySQL

A root password is only set if MySQL was not initizialized.

## Configuration

### Data-Dir
The MySQL data is stored at `/var/lib/mysql`

### Logs
Log files are written to `/var/log/mysql`
