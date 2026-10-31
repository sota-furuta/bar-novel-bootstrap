# bar-novel-bootstrap

BAR NOVEL（伊勢原のバー）のホームページ。
公開中のベースページ https://sota-furuta.github.io/bar-novel/
（元リポジトリ `sota-furuta/bar-novel` の feature-bar-novel-oner-review ブランチ）の
デザイン・内容・数値をそのままに、実装だけ Bootstrap 5.3.8 に置き換えた版です。

## ベースページからの変更点（見た目は変えない）
- 開閉セクション: 素の details + 独自JS → Bootstrap Collapse（同時に開くのは1つだけ、ベースのJSと同じ挙動）
- ギャラリー: 独自スライダーJS → Bootstrap Carousel（10秒自動送り、送りボタンはベースの四角ボタンに合わせて調整）
- ヘッダー: Bootstrap Navbar（中身はベースどおりロゴのみ）
- 背景色だけ琥珀色グラデーション（feature-bar-novel-amber-color ブランチ）に変更

## 画像
写真は元リポジトリの images/（exterior / interior / pasta / food）を raw URL でリンク表示しています。
