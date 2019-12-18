# Docker
## Nginx + httpd + php + mariadb + phpmyadmin

### Comands
`docker-compose up --build`

`docker stop $(docker ps -a -q)`

`docker rm $(docker ps -a -q)`

### MariaDB
In DB confing replace `127.0.0.1` => `mariadb` 

### Httpd
Change `DocumentRoot`
