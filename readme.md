# 環境構築手順

## 環境を立ち上げる

```bash
$ cd laradock
$ ./start_docker.sh
$ ./login_docker.sh

// workspaceに入る
$ cd app
$ composer install
$ yarn install
$ yarn run watch

// ビルド
$ yarn run dev
```

## 環境を閉じる
```bash
$ exit
$ ./stop_docker.sh
```