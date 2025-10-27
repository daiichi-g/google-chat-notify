## 使い方
```yaml
uses: daiichi-g/google-chat-notify
with:
  webhook-url: <Webhook URL>
  message: <送信するメッセージ>
```

### ワークフローリンクなどの前にテキストを配置する
```yaml
uses: daiichi-g/google-chat-notify
with:
  webhook-url: <Webhook URL>
  message: <送信するメッセージ>
  icon: <ワークフローリンクなどの前に配置するテキスト>
```

### スレッドに送信
```yaml
uses: daiichi-g/google-chat-notify
with:
  webhook-url: <Webhook URL>
  message: <送信するメッセージ>
  topic-id: <送信先スレッド>
```

## パラメータ
| パラメータ名 | 必須 | 説明 |
|:---|:---:|:---|
|webhook-url |必須 |Google Chat Webhook URL ([取得方法](https://developers.google.com/hangouts/chat/how-tos/webhooks#define_an_incoming_webhook)) |
|message |必須 |送信するメッセージ |
|icon | |ワークフローリンクなどの前に配置するテキスト |
|topic-id | |スレッドのtopic-id |
