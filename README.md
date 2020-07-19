# nodejs docker environment

```sh
docker-compose up -d
docker-compose exec app yarn install
docker-compose exec app yarn run browser-sync:init
docker-compose exec app yarn run browser-sync:start
```

## browersync

http://localhost:3000
http://localhost:3001
