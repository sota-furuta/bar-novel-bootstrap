# bar-novel-bootstrap

BAR NOVEL（伊勢原のバー）のホームページを Bootstrap 5.3 でリファクタリングした版です。
元リポジトリ: sota-furuta/bar-novel

## 変更点
- Bootstrap 5.3（CDN）を導入し、レイアウトをユーティリティクラスへ移行
- ヘッダーを Bootstrap Navbar 化（スマホではハンバーガーメニュー）
- ギャラリーの自前スライダーJSを Bootstrap Carousel に置換し、カスタムJSを削除（自動再生10秒は維持）
- style.css はテーマ変数・フォント・ヒーロー演出・アクセントボタンのみに削減

## 注意
画像（images/ フォルダ）は元リポジトリと同じものを使用します。
