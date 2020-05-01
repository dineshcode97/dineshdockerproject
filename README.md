# dineshdockerproject

images used in the project:
      - mysql:5.7
      - wordpress:5.1.1-php7.3-apache
      - phpmyadmin/phpmyadmin:latest

Points to be considered:
1: You have to install docker-compose rpm first if you haven't install before .
2: Use docker-comopse up command to start whole infrastructure.
3: you can change database name, root password ,username and password according you in docker-compose.yml file.
4: I used volumes to store the data permanently 
5: if you down the infrastructure using docker-compose down data still available because of volumes
