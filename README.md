# bar-novel-bootstrap

BAR NOVEL（伊勢原のバー）のホームページ。
公開中のベースページ https://sota-furuta.github.io/bar-novel/
（元リポジトリ `sota-furuta/bar-novel` の feature-bar-novel-oner-review ブランチ）の
デザイン・内容・数値をベースに、Bootstrap 5.3.8 で UI を改善した版です。
背景色は琥珀色グラデーション（feature-bar-novel-amber-color ブランチ）。

## ベースページからの UI 改善点
- ヘッダーにページ内リンクを追加（現在地が光るスクロールスパイ付き、スマホはハンバーガー）。
  リンクを押すと対象パネルが開く
- スマホ用に下部固定バー（電話する／地図／Instagram）
- 電話番号をタップで発信できるリンクに
- ギャラリーにインジケーターを追加
- パネルを開いたとき見出し位置へ自動スクロール、トップへ戻るボタン
- 開閉セクションは Bootstrap Collapse（同時に開くのは1つだけ、ベースの挙動を維持）
- ギャラリーは Bootstrap Carousel（10秒自動送り、送りボタンはベースの四角ボタンに合わせて調整）

## スマホ版
ベースページの @media（768px以下）の数値（ヒーロー55vh・タイトル5rem・見出し70px/1.8rem・
メニュー左余白35px・価格幅70px・写真80%/240px・ボタン40px など）に合わせてある。

## 画像
写真は元リポジトリの images/（exterior / interior / pasta / food）を raw URL でリンク表示しています。
