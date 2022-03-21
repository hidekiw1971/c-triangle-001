# compornent（共通部品）

## イメージ画像
<img width="401" alt="image" src="https://user-images.githubusercontent.com/99580997/159255550-10aea751-3c9a-4c58-83fa-5b8c3f61cd62.png">
<img width="782" alt="image" src="https://user-images.githubusercontent.com/99580997/159255596-214d928e-c6dc-4d0b-89d5-f806f9256993.png">
<img width="1095" alt="image" src="https://user-images.githubusercontent.com/99580997/159255638-3298d303-4a31-4c4f-913a-66eb0861651b.png">


## 概要

- css で三角形を表現

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- 本体の`width`を`height`を 0 にして、`border`の線を太くして三角系を形成しているので、中身を`transparent`で透明にはできない。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> triangle をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
<img width="769" alt="image" src="https://user-images.githubusercontent.com/99580997/159255696-51e35dca-e869-46f7-b5e4-647be3cd71f8.png">

## w3c css チェック結果
<img width="1668" alt="image" src="https://user-images.githubusercontent.com/99580997/159255784-49c86cd8-080b-4361-bdf5-d2c958a0cdb9.png">

- https://jigsaw.w3.org/css-validator/

## portfolio url:

- https://c-0031.wtb.cfbx.jp/

## 参考にしたサイト

- CSS 三角形作成ツール
- http://apps.eky.hk/css-triangle-generator/ja
- CSS だけで三角形を作ろう！その 1：border プロパティの仕組みをマスター
- https://www.granfairs.com/blog/staff/make-triangle-with-css
- border-style プロパティとは
- https://beginners-hp.com/css-property/border-style.html

## 更新履歴

- 2022/3/21 初版 作成完了

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
