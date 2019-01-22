# Docker Network による Lumen のエミュレーション

WSL と Docker for Windows の連携設定を済ませて、以下のコマンドを叩けば Lumen が動く。

```
$ docker-compose up -d
```

動作確認はWebブラウザから `http://127.0.0.1:8080` へアクセスするだけ。
