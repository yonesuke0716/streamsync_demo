# Streamsync-demo

## Dockerコンテナ作成
```
docker image build -t streamsync_demo .
docker container run --rm -it -v $(pwd):/app -p 8080:8080 streamsync_demo bash
```

### Streamsync
編集
```
streamsync edit hello --port 8080 --host 0.0.0.0 --enable-remote-edit
```
実行
```
streamsync run hello --port 8080 --host 0.0.0.0
```
以下にアクセス。

http://0.0.0.0:8080





