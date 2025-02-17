# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください

### 選択した事業側の課題

サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

###  提案内容

プロフィール機能を充実させる（性別選択、自己紹介文等）
女性の登録者自体は一定数いるが、参加者が少ない理由は、イベント主催者、参加者のとなりが見えず参加しづらい、怖い等が挙げられる。
そのため自己紹介文を書けるようにしたり、性別選択をできるようにし、同じ女性の参加者がいるから参加してみようという女性ユーザーの増加が期待できる。
プロフィールを他のユーザーが見れることで利用者が安心してイベントに参加できるようになる。

### 実装方針

・他のユーザーのプロフィールを閲覧できるようにする。
・プロフィールに自己紹介と性別を追加する。
・ユーザープロフィール画面から過去に主催したイベントや、参加したイベントが表示されるようにする。
