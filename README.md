# docker-sample-nginx
a sample nginx container to display static html

clone
```
git clone --recursive https://github.com/afreisinger/www.git
```

run
```
docker-compose up -d
```

debug
```
docker-compose up -d && docker-compose logs www
docker-compose logs -f www
```
