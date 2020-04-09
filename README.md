## 使い方

```
git clone git@github.com:yoritin/laravel_docker.git app_name

cd app_name
```
[app_name]は適当に変更してください

## 変更箇所
- `docker-compose.yml`
の`laravel_docker`の部分を`app_name`に変更
- `Makefile`の`laravel_docker`の部分を`app_name`に変更

## コンテナの起動、コンテナに入る
```
make in
```

### .gitignoreが反映されない場合は
```
git rm -r --cached .
```

## Laravelのインストール
```
composer create-project --prefer-dist laravel/laravel ./
```
