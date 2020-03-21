## 使い方

```
git clone git@github.com:yoritin/laravel_docker.git app_name

cd app_name
```

## 変更箇所
`docker-compose.yml`
の`laravel_docker`の部分を`app_name`に変更

## コンテナの起動、コンテナに入る
```
make in
```

## Laravelのインストール
```
composer create-project --prefer-dist laravel/laravel ./
```