# bar-novel-bootstrap

BAR NOVEL（伊勢原のバー）のホームページ。元リポジトリ `sota-furuta/bar-novel` の
オーナー版ブランチ（feature-bar-novel-oner-review）のデザインを参考に、
Bootstrap 5.3.8 で再構成した版です。

## デザイン（オーナー版準拠）
- 背景はゴールドのグラデーション（#c7a678→#e0c18f→#c88b4e）、差し色 #e0b06a、濃色 #0b0a08
- ヒーローは全面写真＋暗転オーバーレイ、コピーはオーナー版の「女性一人でも気軽に。会話とお酒を楽しむ居心地の良い空間。」
- セクションはオーナー版の開閉式（details）構成を Bootstrap Accordion で再現（同時に1つだけ開く）
- メニューはオーナー版の詳細メニュー（カクテル ¥750〜、ソーセージ盛り合わせ ¥1,000 など）
- ギャラリーは Bootstrap Carousel（10秒自動送り）

## 画像
- ヒーロー背景とギャラリーの先頭4枚は、オーナー版ブランチの images/ を
  raw URL でリンクして表示（exterior / interior / pasta / food）。
- ギャラリーの残りはリポジトリ直下の IMG_8582〜8584.jpeg を使用。
