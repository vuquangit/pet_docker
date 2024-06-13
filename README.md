# PET PROJECT

## Install Docker Desktop
- <https://docs.docker.com/desktop/install/windows-install/>
- <https://docs.docker.com/desktop/install/linux-install/>
- <https://docs.docker.com/desktop/install/mac-install/>

## Clone api and web repo
`cd pet_docker`

`git clone https://github.com/vuquangit/pet_api.git`

`git clone https://github.com/vuquangit/pet_web.git`

## Build images
 `docker-compose up -d --build`

## Run everything together

Run `docker-compose up`

### Clean the database volume

Run `npm run clean` or `docker-compose down -v`


### Start service nginx

```
docker exec nginx nginx -t
docker exec nginx nginx -s reload
docker exec nginx service nginx status

docker exec nginx curl localhost 
```

## Useful links
- <https://docs.docker.com>
