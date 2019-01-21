# docker_dev_env
This repository contains startup development environments for docker

I use this file to keep some of my setups that i will have to rewrite everytime i have to start a project

# Setup:
*install docker* 


1. Wordpress
    * docker-compose.yml file *
    * copy and paste from the docker-compose.yml file in the repositpry *
    * change the environment variables to yours * 
        - MYSQL_ROOT_PASSWORD: **your password**
        - WORDPRESS_DB_USER: **your username**
        - WORDPRESS_DB_PASSWORD: **your password**
    * run commands *
    * docker-compose up -d *
    * localhost:8000 -> to view your site*
    * localhost:8080 -> phpmyadmin *
