# Basic CRUD app

+ Deployed using
    - Docker
    - Heroku (Container Registry)

+ Database
    - MongoDB



## Env variables
> Create .env in parent directory

| KEY | VALUE |
|---|---|
| MONGO_URI_PRODUCTION | Mongo DB URI for production |
| MONGO_URI_DEVELOPMENT | Mongo DB URI for development |
| RAILS_SERVE_STATIC_FILES | To serve local static files (true/false) |



## Run Locally
```
git clone https://github.com/kaydee0502/deploy_app

```
> Make sure you have docker installed!

```
docker-compose up -d
```

`Your app should be running on localhost:3000`

