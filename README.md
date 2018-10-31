# My own docker-compose for Drupal8

It contains:
* PHP container with Apache, Composer, Drupal Console, Git
* MariaDb container 
* Adminer for managing database from browser 

Steps to get started:
1. `docker-compoe build` to build an image
2. `docker-compose run -d` to run containers
3. `docker-compose exec web /bin/bash` to get into container with php and install and work with site 