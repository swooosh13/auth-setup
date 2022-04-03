# Setup traefik


## start
    $ docker-compose up -d

for start server:
1. uncomment `.env` in `.gitignore`
2. create if not exists `.env`
3. copy from .env.example to .env & put your values

> if you want to run local -> set `TRAEFIK_URL=localhost` from `.env` file