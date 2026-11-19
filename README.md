# py-realtime-forum

WebSocketを使ってオンラインゲームを開発するためのリポジトリです。

## 構成

- クライアント：GitHub Pages
- サーバー：Render（Python WebSocketサーバー）

## 技術
- Python（websockets）
- JavaScript（WebSocket API）
- GitHub Pages（フロントエンド）
- Render（バックエンド）

## お試しサイト（クライアント）
https://dev-haku.github.io/py-realtime-forum/
### 利用の際の注意点
接続に失敗した際は時間をおいて、再度アクセスすると接続できます。
理由と致しましては、サーバ側がしばらくアクセスされていないと、サーバーを落としてしまっていまして、
そのあとにクライアントが接続を介してサーバーにアクセスした際に起動し、その起動時間が数十秒あり、起動完了までは接続完了ができないからであります。

## サーバー
Renderで起動しています（WebSocket）
