# ビルド方法

docker build -t feem/laravel-mysql:dev .

# タグ付け

docker tag feem/laravel-mysql:dev feem/laravel-mysql:5.7.28

# プッシュ

docker push feem/laravel-mysql:5.7.28
