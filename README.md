# OpenAPI Specification Docs & Mock Server

## ローカルで起動する場合
### 前提
nodejsを使うので、FEの環境と同様に[volta](https://volta.sh/)を利用しています。

### 初回起動
1. `$ yarn install`

### ドキュメントページ起動
1. `$ yarn docs --port=4444` ※ 4444portで起動する場合。必要に応じてポートは変更してください。
2. `http://127.0.0.1:4444` へアクセス

### HTML出力
1. `$ yarn docs:export` ./public/index.html に出力されます。

### モックサーバー起動方法
1. `$ yarn mock -p 4040` ※ 4040でモックを立ち上げる場合。必要に応じてポートは変更してください。

## Dockerで起動する場合
1. `$ docker compose up -d`
2. 立ち上がったら以下でアクセスできます。
  - ドキュメントページ: `http://localhost:3031`
  - モックサーバー: `http://localhost:3030/xxx`