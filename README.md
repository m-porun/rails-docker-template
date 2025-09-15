お手軽Railsセットです

# 環境構築
```
docker compose build --no-cache
docker compose run --rm web bin/rails db:create
docker compose run --rm web bin/rails db:migrate
docker compose up -d
```
