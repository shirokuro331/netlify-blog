---
title: "Netlify で独自ドメイン設定する方法"
date: 2018-04-13T11:23:01+09:00

---

- お名前.com でドメイン取得
- `Netlify -> Settings -> Domain management` の `Custom domains` にある `Add custom domain` ボタンを押す  
![](/images/netlifydomain/1.png "")
- ダイアログが出るので取得したドメインを入力  
![](/images/netlifydomain/2.png "")  
- 画像撮り忘れたけど `~ config ~` みたいなリンクがあるのでクリックして画面の指示通り進めていくと4つのネームサーバーが表示される。あとでお名前.com の画面で使うのでタブをそのまま開いておく
- `お名前.com -> ドメイン詳細 -> ドメイン設定 -> DNS関連機能の設定 -> DNSレコード設定` からAレコードとCNAMEを追加
  - Aレコードで 104.198.14.52を追加
  - CNAMEで　Netlify で設定した URL を追加
- `お名前.com -> ドメイン詳細 -> ドメイン設定 -> DNS関連機能の設定 -> ネームサーバーの変更 -> 他のネームサーバーを利用` から4つのネームサーバーを入力する
- 設定完了。DNS が浸透すれば独自ドメインでサイトが表示される
- HTTPS 化させるために `Netlify -> Settings -> Domain management` の `HTTPS` にある `Verify DNS configration` ボタンを押す
- 画面に従って進めていけば設定完了。HTTPS でアクセス可能



