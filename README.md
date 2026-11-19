# py-realtime-forum

WebSocketを利用したリアルタイム通信を実装した、オンラインゲーム開発向けの掲示板サーバー・クライアントです。

## 構成

|  | クライアント | サーバー |
|:---|:---:|:---:|
| プラットフォーム | GitHub Pages | Render |
| 技術 | HTML / JavaScript | Python / WebSocket |
| 役割 | メッセージの送受信・表示 | 接続管理・メッセージ処理 |

## 技術

- Python (`websockets`)
- JavaScript (WebSocket API)
- HTML
- GitHub Pages（フロントエンド）
- Render（バックエンド）

## デモ

**クライアントサイト：**  
https://dev-haku.github.io/py-realtime-forum/

### 接続時の注意

本サーバーはRenderの無料プランを利用しているため、一定時間アクセスがない場合、サーバーがスリープ状態になることがあります。

スリープ状態から復帰する際、サーバーの起動に数十秒かかる場合があるため、初回接続時に接続エラーが発生することがあります。

その場合は、しばらく時間をおいてから再度接続してください。サーバーの起動が完了すると、正常に接続できるようになります。
