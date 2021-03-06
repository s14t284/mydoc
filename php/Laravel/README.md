# Laravel

- [ディレクトリ構成](dir-structure.md)
- [Routing](routing.md)
- [Controller](controller.md)
- [Service(Service Provider)](service.md)
- [Middleware](middleware.md)
- [Validation](validation.md)
- [Database](database.md)
- [Eloquent ORM](eloquent.md)
- [RESTful API](restapi.md)
- [Session](session.md)
- [pagination](pagination.md)

## Memo

- すぐにできる環境構築（Dockerが必要）

```sh
curl -s https://laravel.build/example-app | bash  # "example-app" はなんでもいい
cd example-app
./vendor/bin/sail up  # 起動に必要な docker の設定が走り、docker-compose 上で Laravel が動作
# ただし、DB周りのコマンド(migration, seeding)では `php artisan` ではなく `./vendor/bin/sail artisan ~~` を使う
```
