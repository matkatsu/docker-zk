# 概要

検証用zookeeper環境です。3ノードクラスタです。

https://hub.docker.com/_/zookeeper/ の内容そのままです。

## 起動
```
$ docker-compose up -d
```

### 接続

- localhost:2181
- localhost:2182
- localhost:2183

### コンテナ内部に入る
zoo1へ入る
```
$ docker-compose exec zoo1 bash
```

zookeeperのスクリプト類は`/bin`以下に入ってます。

## 停止
```
$ docker-compose down
```

