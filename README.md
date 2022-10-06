# Java-SpringBoot-Thymeleaf

## 参考

https://zenn.dev/junki555/articles/1073408293050f

## コマンド

```
# バックグラウンドでコンテナを実行(--detach)
docker-compose up -d

# サービス(app)で任意のコマンド(bash)を実行している
docker-compose exec app bash

# ビルド
sh gradlew build

# JARファイルの中にカプセル化されたプログラムを実行
java -jar build/libs/demo-0.0.1-SNAPSHOT.jar 

# ローカルホストへアクセス
http://localhost:8080/

# 稼働中のコンテナを停止
docker-compose stop

# コンテナとネットワークの削除
docker-compose down
```