# laravel-docker

## 使用技術
- Laravel v8.49.1 (PHP v8.0.5)
- PostgreSQL v13.3

## 構築方法
1. `docker-compose build`
3. `docker-compose up`
4. http://localhost/ にアクセス
5. 初期画面ページが表示されれば構築成功！

マイグレーション実行方法
```
docker-compose exec app php artisan migrate
```

## 参考記事
- [最強のLaravel開発環境をDockerを使って構築する \- Qiita](https://qiita.com/ucan-lab/items/5fc1281cd8076c8ac9f4)
- [【超入門】20分でLaravel開発環境を爆速構築するDockerハンズオン \- Qiita](https://qiita.com/ucan-lab/items/56c9dc3cf2e6762672f4)
- [docker composeを使ってPostgreSQLを構築する \| mebee](https://mebee.info/2020/12/04/post-24686/)
- [Docker \+ Nginx \+ Laravelの開発環境構築からHerokuへのDeployまで](https://zenn.dev/nagi125/articles/ea1d314c94409341a3b0)