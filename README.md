# linebot-6th

## これは何？

[シンデレラガールズ 6th ライブ](https://idolmaster.jp/event/cinderella6th.php) の出演者情報を教えてくれる **非公式** LINE bot です。

![ios](https://user-images.githubusercontent.com/8451003/47545740-d4635900-d928-11e8-8d19-5a13017b31af.png)

## 友達登録

![qrcode](https://qr-official.line.me/M/jmCLYHzxNv.png)

## 開発者向け（＝ 自分向け）メモ

### Heroku アプリ作成（初回のみ）

```bash
heroku create linebot-6th
```

### 環境変数登録

```bash
heroku config:set LINE_CHANNEL_SECRET=mojamoja
heroku config:set LINE_CHANNEL_TOKEN=mojamoja
```

### デプロイ

```bash
git push heroku master
```
