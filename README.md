<p align="center">
  <img width="350px" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"/>
</p>

## Wordpress on Docker
WordPress is the simplest, most popular way to create your own website or blog. Wordpress is a free, open-source website creation platform. On a more technical level, WordPress is a content management system (CMS) written in PHP that uses a MySQL database.

Docker is an open platform for developing, shipping, and running applications.
This is only a simple case to install wordpress on docker with docker-compose.

Please make sure you already install Docker on your local machine before try this module. If you still not have installed it, you can check how to install Docker [here](https://docs.docker.com/engine/install/).

**Notes**
: WordPress Multisite works only on ports 80 and 443

## Usage
```
#Download project
wget https://github.com/hidayatakhyar/wordpress-on-docker.git

#open file
cd wordpress-on-docker

#Compile environment
docker-compose build

#Run environment
docker-compose up -d

#if you finished, delete the environment with the following command.
docker-compose down -v
```

