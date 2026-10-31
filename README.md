# bar-novel-bootstrap

BAR NOVEL（伊勢原のバー）のホームページを Bootstrap 5.3 でリファクタリングした版です。
元リポジトリ: sota-furuta/bar-novel

## 変更点
- Bootstrap 5.3（CDN）を導入し、レイアウトをユーティリティクラスへ移行
- ヘッダーを Bootstrap Navbar 化（スマホではハンバーガーメニュー）
- ギャラリーの自前スライダーJSを Bootstrap Carousel に置換し、カスタムJSを削除（自動再生10秒は維持）
- style.css はテーマ変数・フォント・ヒーロー演出・アクセントボタンのみに削減

## 画像
写真はリポジトリ直下の IMG_8580〜8584.jpeg を使用します（ヒーロー背景: IMG_8581、ギャラリー: 全5枚）。
