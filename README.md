# 概要

lamp laravel のための mysql イメージを作成します。  
MySQL の公式 Docker イメージを利用しています。

https://hub.docker.com/_/mysql

# ビルド方法

docker build -t feem/laravel-mysql:dev .

# タグ付け

docker tag feem/laravel-mysql:dev feem/laravel-mysql:5.7.28

# プッシュ

docker push feem/laravel-mysql:5.7.28

# テスト実行

docker run --rm -it -e MYSQL_ROOT_PASSWORD=my-secret-pw feem/laravel-mysql:dev
