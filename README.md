# ちょっとだけチャットシステム

### 概要
Native JavaScriptとGoogle Apps ScriptとGoogle SpreadSheetを用いて、ちょっとしたチャットアプリを作った。

メッセージは、SpreadSheetに保存し、そのAPIをGASで開発した。

### Google Apps ScriptによるAPI

* 誰から誰に送るメッセージなのかをクエリで指定し、スプレッドシート内を検索しjsonで返す。
* 誰から誰に送るメッセージなのかをクエリで指定し、メッセージのデータを追加する。


### デプロイ先
https://www.sonneko.com/chat

---
Firestore DatabaseとNext.jsによるバックエンドアプリを用いた、上位互換のアプリを開発中。

↓↓
フロントエンド：
https://github.com/sonneko/sonneko-chat

バックエンド：
https://github.com/sonneko/sonneko-back
（private repository）
