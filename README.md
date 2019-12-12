# docker-php-7.2


Build the image 

```bash 
docker image build --tag $DOCKER_ID/php-7.2 .
```

Run th container 

```bash 
docker container run -d --publish 80:80 --mount type=bind,source="$(pwd)",target=/var/www/html terdia07/php-7.2
```