# bar-novel-bootstrap

BAR NOVEL（伊勢原のバー）のホームページを Bootstrap 5.3 で1から作り直した版です。
元リポジトリ: sota-furuta/bar-novel

## デザイン
- カラーパレットはオーナー版ブランチ（feature-bar-novel-oner-review）に合わせた: 背景はゴールドのグラデーション（#c7a678→#e0c18f→#c88b4e）、文字 #3b2a18、差し色 #e0b06a、濃色部分 #0b0a08。フォントは Playfair Display + Noto Sans JP
- Bootstrap 5.3.8 使用
- レイアウトは新規構成: ヒーローは左テキスト・右写真（ゴールドのずらし枠＋縦書き装飾）、コンセプト帯、番号付き見出し、スクロールでふわっと表示
- Information はテーブル、Menu はカード、Gallery はグリッド＋モーダル拡大、Access はボタン2種
- カスタムJSなし（Navbar の開閉、モーダルはすべて Bootstrap の機能で実現）

## 画像
写真はリポジトリ直下の IMG_8580〜8584.jpeg を使用します（ヒーロー: IMG_8581、ギャラリー: 全5枚）。
