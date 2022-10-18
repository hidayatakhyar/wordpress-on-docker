![](https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png)

## Wordpress on Docker
Docker is an open platform for developing, shipping, and running applications. This is only a simple case to install wordpress on docker with docker-compose.

Please make sure you already install Docker on your local machine before try this module. If you still not have installed it, you can check how to install Docker [here](https://docs.docker.com/engine/install/).

**Notes**
WordPress Multisite works only on ports 80 and 443

## Usage
```
#Download project
wget https://github.com/hidayatakhyar/wordpress-on-docker.git
cd wordpress-on-docker

#Compile environment
docker-compose build

#Run environment
docker-compose up -d
```
After the test, delete the environment with the following command.
`docker-compose down -v`

