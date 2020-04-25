# docker-compose-laravel

Start the installation with below command
```sh
docker-compose up -d
```
# update .env file
```sh
mv html/.env-example html/.env
```
# composer command
```sh
docker exec -it app composer install
```
# php artisan commands
```sh
docker exec -it app php artisan <command>
```
# env file mysql connections
| Variable | Values |
| ------ | ------ |
| MYSQL_HOSTNAME | db |
| MYSQL_ROOT_PASSWORD | Mysql321 |
| MYSQL_DATABASE | laravel |
| MYSQL_USER | root |

# Test on browser 
http://localhost
