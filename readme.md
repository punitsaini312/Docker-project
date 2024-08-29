
Dockerized WordPress and MariaDB Setup

This project demonstrates how to set up a WordPress website with a MariaDB database using Docker containers.

## Prerequisites

- Docker installed on your machine
- Basic understanding of Docker commands

## Setup Instructions

### 1. Run MariaDB Container

Start the MariaDB container with environment variables for the root password and database name:

```bash
docker container run -d --name database -e MARIADB_ROOT_PASSWORD=punit312 -e MARIADB_DATABASE=wordpress mariadb:latest

