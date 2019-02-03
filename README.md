# README

```
$ echo 'RAILS_ENV=production' >> .env
$ echo 'APP_DATABASE_PASSWORD=password' >> .env
$ docker-compose run web rails active_storage:install
$ docker-compose run web rails db:create
$ docker-compose run web rails db:migrate
$ docker-compose up -d
```
