# Docker-compose簡易サンプル

## 概要
初学者向けのdocker-composeの簡易サンプルです。
docker-composeを起動するとウェブサーバーが立ち上がり、
ブラウザでアクセスすると、Hello World!と表示されます。

## 使用方法

このリポジトリを任意の場所にクローンし、
以下のコマンドを実行してDockerコンテナを起動してください。

```bash
cd sample
docker-compose up -d
```

その後ブラウザで`http://localhost:8080`にアクセスしてください。

詳細は次の記事を参照してください。\
https://qiita.com/joyrswd/items/99460a9920c93ff66351


## ファイル構成
```
.
├── docker-compose.yml # dockerの設定ファイル
├── README.md          # このファイル
├── LICENSE            # ライセンスファイル
└── html               # ウェブサーバーのルートディレクトリ
    └── index.html     # ウェブサーバーのトップページ
```


## ラインセンス

このプロジェクトは[MITライセンス](LICENSE)の下でライセンスされています。

