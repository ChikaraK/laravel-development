```
Docker のバージョンは >=17.05 が必須です。
```
```
# docker起動
$ docker-compose up -d

# phpコンテナに入ります
$ docker-compose exec php bash

# Laravelプロジェクト作成
$ composer create-project laravel/laravel hogehoge

# nginx/default.confのrootを書き換える
```