```
cp .env.example .env.dev
```
to run staging 
```
docker compose -f docker-compose.dev.yml --env-file .env.dev up
```

to run production

```
docker compose -f docker-compose.prod.yml --env-file .env.dev up
```
