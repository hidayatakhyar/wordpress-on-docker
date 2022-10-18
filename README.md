![](https://imgs.search.brave.com/WRQQo7EJyPOUNEoXdM4CUNTp-cofeiZvoHIGKAv6oag/rs:fit:924:636:1/g:ce/aHR0cHM6Ly9kd2ds/b2dvLmNvbS93cC1j/b250ZW50L3VwbG9h/ZHMvMjAxNy8wOS8x/MzAwcHgtRG9ja2Vy/X2NvbnRhaW5lcl9l/bmdpbmVfbG9nby5w/bmc)

## Wordpress on Docker
Docker is an open platform for developing, shipping, and running applications. This is only a simple case to install wordpress on docker with docker-compose.

Please make sure you already install Docker on your local machine before try this module. If you still not have installed it, you can check how to install Docker [here](https://docs.docker.com/engine/install/).

**Notes**
WordPress Multisite works only on ports 80 and 443

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

#delete the environment with the following command.
docker-compose down -v
```

