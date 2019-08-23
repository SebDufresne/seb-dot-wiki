# Quick Sheets

## Removes EVERYTHING (DON'T USE!!!)

### Stops ALL containers

docker container stop $(docker container ls -aq)

### Remove ALL containers

docker container rm $(docker container ls -aq)

### Removes (and un-tags) ALL images from the host node

docker rmi $(docker images -a -q)

### List Volumes

docker volume ls
docker volume rm <file_name>

## Build Our Project From Nothing

docker-compose up -d --build

docker-compose ps

docker exec -it <container_name> bash

/app#  composer create-project drupal-composer/drupal-project:8.x-dev /app --stability dev --no-interaction
/app#  mkdir -p /app/config/sync
/app#  chown -R www-data:www-data /app/web
