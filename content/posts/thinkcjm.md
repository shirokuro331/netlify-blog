---
title: "ひさしぶりにカスタマージャーニーマップ作ったので自分なりの作り方と所感など"
date: 2017-07-29T11:23:01+09:00

---

[入社して](/posts/joincampfire/)今のプロジェクトにアサインされたとき、携わるサービスに対する理解を深めたかったということと、同じタイミングで入社したスタッフも同時にアサインされたので、メンバー間のサービスに対する認識のすり合わせも兼ねてまず取り掛かったのはカスタマージャーニーマップの作成だった。

ひさしぶりに作ったということもあり、今後も作ったり説明する機会も増えると思うので、今回実践した自分なりのカスタマージャーニーマップの作り方を残しておく。

参考にした記事はこちら
[カスタマージャーニーマップは、いつどのように作るべきか − U-Site前提として](https://u-site.jp/alertbox/customer-journey-mapping)


## 前提として

カスタマージャーニーマップを作る目的は「サービスを利用するユーザーの行動や感情などを見える化して最適だと思われる施策を考案すること」と「プロジェクトメンバー間での認識共有」だと個人的には考えている。

しかしジャーニーマップを作れば施策が成功するというわけではなく、あくまでユーザー体験の整理を行いユーザーとのタッチポイントを探るためのツールで、サービス運営にともない内容は適宜アップデートを図るべきもなので最初に作る時はそこまで時間をかけないように心がけている。

なにより、機能実装を行ったほうがユーザー的にもビジネス的にも生産的だと思うのでリソースの配分には気をつけていきたい。

## 作り方

こちらが今回つくったカスタマージャーニーマップ。

![](/images/thinkcjm/01.png "")

上部がペルソナとかで下部がジャーニーマップ。同じドキュメント内にペルソナとジャーニーマップを書いておくと複数のドキュメントを行ったりきたりする必要がないのでわかりやすかった。

各要素をそれぞれ解説していく。

### ペルソナ

- ペルソナ
- シナリオ
- ユーザーの目的

「誰のためのサービスか」をざっくりと定義するためにもターゲットとしたいユーザー層や実際のデータをもとにして、サービスを利用する人物像を想定する。そしてその人がどういう生活シーンのなかでサービスが必要になるかをイメージしてシナリオをおこす。そのシナリオから見えるユーザーの目的（ゴール）も合わせて定義しておく。

![](/images/thinkcjm/02.png "")

こんな感じ。

ペルソナとシナリオを立てることで、物語として「○○さんはこういう行動をするはずなのでこういう機能が必要。逆にこういう行動をあまりしないはずなのでこの機能追加は今は優先度を下げよう」といった認識の共有と会話をメンバー間で行うことができる。

もちろん特定の誰かだけが使うサービスではないのでここで表す内容は大勢の中のひとりのものにはなる。ビジネス的にリーチすべき層の中から母数が多い層から優先的にペルソナを作っていったほうが予算の最適化にもつながってくると考えている。

### ジャーニーマップ

- フェーズ
- 期間
- 行動
- 方法
- 思考
- 感情
- 施策
- バッドケース
- KPI

上記の項目を縦軸、ユーザーの目的達成とその後までの行動を横軸にしてジャーニーマップの大枠をつくる。

横軸についてはAIDMAなどの購買行動をベースにユーザーの目的達成までの流れを考えてフェーズを分解していくことと、UX白書にある利用前・利用中・利用後といったユーザー体験の段階を分類していく。こうすることで、「ここまでは集客のための施策」「ここまではサイトの機能についての施策」「ここからはリピートのための施策」というふうにも分けることができるので、ピンポイントなフェーズに対しての施策だけではなく、利用前・利用中・利用後といった期間で俯瞰して施策を考えることができる。


![](/images/thinkcjm/03.png "")

大枠をつくったならば後は内容を埋めていく。

このフェーズならユーザーはどういう行動をするのか
このフェーズに到達するまでは何日くらいかかるのか
その行動をするためのツールはなにか
その行動をしているときユーザーはどういうことを考えるのか
そういうことを考えて行動するならサービス提供側としてはどのような価値を提供すべきでどのようにユーザーと接点を持てるのか
その接点をもって価値を提供するための施策はどのようなもので、その施策を評価するためのKPIはなんなのか
このフェーズにおいてユーザーとサービス提供側がもっとも避けることはなんなのか
などなどを考えながら埋めていく。

本当はユーザー観察などを行って事実を書いていくのが望ましいと思うが、現実的には目に見えるものがない状況でジャーニーマップに対する理解がまだ得られていないなどといったこともあると思うので、まずは仮説や想像をベースとして内容を埋めていけばよい。
その後プロジェクトメンバーに見せてどういったものかを少しでも理解を得られてからメンバー間でディスカッションしたりユーザーインタビューなどを行ってアップデートしていけばよい。

メンバー間で共有・ディスカッションなどを行なうことで「こういうフェーズもあるよね」「このフェーズはこういう施策もできるからフェーズを分解したほうがいいよね」「ここって時間かかりすぎてるからここを短くできるとユーザー満足度あがるよね」といったことを議論することができ、メンバー全体でドキュメントに対する理解と愛着が深まっていくと思う。

## まとめ

おおまかだが現状の自分なりのジャーニーマップの作り方は上記のような感じ。
適宜アップデートしたい。