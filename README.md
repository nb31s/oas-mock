# OpenAPI Specification Doc & Mock Server

## 初回起動方法
1. `$ yarn install`

## ドキュメントページ起動
1. `$ yarn docs --port=4444` ※ 4444portで起動する場合です。必要に応じてポートは変更してください。
2. `http://127.0.0.1:4444` へアクセスする

## HTML出力
1. `$ yarn docs:export` ./public/index.html に出力されます。

## モックサーバー起動方法
1. `$ yarn mock -p 4040` ※ 4040でモックを立ち上げる場合。必要に応じてポートは変更してください。
