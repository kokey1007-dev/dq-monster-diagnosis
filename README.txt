ドラゴンクエスト モンスター性格診断
====================================

【起動方法】
1. ZIPを展開します。
2. dq_monster_personality_diagnosis_complete フォルダ内の index.html を開きます。

【公開モード】
通常は開発用表示が隠れています。

【開発モード】
URL末尾に ?dev=1 を付けてください。
例: index.html?dev=1

開発モードでは、システム確認・評価集計・最終判定理由・テストプレイヤー評価などを確認できます。

【構成】
index.html
style.css
app.js
images/（44タイプ分）

※非公式のファンメイド診断です。


【OGP / favicon】
ogp.png            : SNS共有時の画像（1200×630）
favicon.png        : ブラウザタブ用アイコン
apple-touch-icon.png : スマホのホーム画面用アイコン

※公開URLが決まったあと、SNS側でOGP画像が出ないサービスがある場合は、
og:image を公開先の絶対URLへ変更するとより確実です。


【結果カードPNGについて】
index.htmlを直接ダブルクリックして file:// で開いた場合、
ブラウザのセキュリティ制限によりモンスター画像をCanvasへ描けないことがあります。
その場合は自動で「画像なしPNG」に切り替わります。
公開後のHTTPS環境、またはスマホ確認用HTTPサーバー経由では画像入りPNGを利用できます。


【STEP 12E 結果カードPNG】
結果カードPNG用の軽量画像をapp.js内に埋め込みました。
そのため index.html を直接ダブルクリックした file:// 環境でも、
モンスター画像入りのPNGカードを生成できます。
