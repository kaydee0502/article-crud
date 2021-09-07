# Basic CRUD app

+ Deployed using
    - Docker
    - Heroku (Container Registry)

+ Database
    - MongoDB



## Env variables
> Create .env in parent directory

| KEY | DESCRIPTION |
|---|---|
| MONGO_URI_PRODUCTION | Mongo DB URI for production |
| MONGO_URI_DEVELOPMENT | Mongo DB URI for development |
| RAILS_SERVE_STATIC_FILES | To serve local static files (true/false) |



## Run Locally
```
git clone https://github.com/kaydee0502/article-crud
cd article-crud

```
> Make sure you have docker installed!

```
docker-compose up -d
```
Or if you have rails
```
bundle install
rails s
```

`Your app should be running on localhost:3000`

