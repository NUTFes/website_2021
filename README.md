# website_2021
## 制作コンセプト
[HackMD](https://hackmd.io/@kobayashi-ryota/HyvOAgXwd)

## ワイヤーフレーム(Figma)
Figmaにログインしていなければ閲覧のみ可能です。編集権限が必要な場合はRyotakobayashに連絡してください <br>
[スマホ版レイアウト](https://www.figma.com/file/OZ6HOJcTBCmReeEUfpbI7o/40thHP_%E3%82%B9%E3%83%9E%E3%83%9B?node-id=0%3A1)<br>
[PC版レイアウト](https://www.figma.com/file/dge02Vnj6DjMmrl3f7GdwO/40th_PC)<br>

## ファイル構成
- images：
  画像ファイルを入れる場所
- js：
  JavaScriptファイルを入る場所
- scss：
  scssファイルを入れる場所
  - [ページ名].scss：
    各ページに当てたいscssファイルをここで'@import'する。生成されるcssファイルをHTMLに当てる
  - base：
    mixinやリセットcss等を入れる
  - components：
    HTMLでページを構成する要素ごとに別のcssファイルを作り、ここに保存する。
    - common：
      コンポーネントの中でも共通となるコンポーネントを入れる。headerやfutter等どのページでも使うようなものを入れる
    - parts：
      コンポーネントを構成するパーツを入れる。ボタンの装飾やフォーム等
  - pages：
    ページ固有のデザインを担当するscssファイルを入れる
  - utils：
    コンポーネントのデザインを一時的に上書きするscssファイルを入れる


## セットアップ
[sass・scssとは？導入方法や使い方を解説する【Win/Mac対応】](https://miya-system-works.com/blog/detail/112)
