# To-do List

この To-do List は HTML と CSS, JavaScript の 3 つで構成される Web アプリケーションです。

<!-- - To-do データは Web Storage API の localStorage を使用してローカル(ブラウザ)に保存
- localStorage はオリジン単位でデータを保存
  - オリジンとは URL の「スキーム://ホスト:ポート」の組み合わせ
  - 開発時に Web サーバーの起動が必要 -->

このアプリケーションの To-do データは、Web Storage API の localStorage を使用してローカル環境(ブラウザ)に保存します。この localStorage はオリジン単位でデータを保存するため、開発時に Web サーバーの起動が必要になります。

(オリジンとは、URL の「スキーム://ホスト:ポート」の組み合わせのことです。)

## サーバーの起動方法

開発時には Web サーバーの起動が必要ですが、どんな方法で起動しても構いません。ここでは、Visual Studio Code を用いたサーバーの起動方法を以下で紹介します。

- Visual Studio Code に `Live Server` という拡張機能を導入
  - Visual Studio Code の左側から拡張機能のタブを開いて検索
  - Ctrl + Shift + X でも拡張機能のタブを表示できる
- html ファイルが入っているディレクトリを Visual Studio Code で開く
  - ドラッグ & ドロップで開けます
- 右下の `Go Live` をクリックしてサーバーを起動
  - 停止するには右下の `Port : xxxx` と書いてるところを選択

## template の状態

### HTML(inedx.html)

- [Delete selected items] ボタンから、個別削除する関数 `deleteOne()` 呼び出してみましょう

### CSS(style.css)

- 大見出しを中央揃えにしてみましょう

### JavaScript(main.js)

- 特になし

---

tmp

- To-do の追加機能 (テキストボックスに入力されている状態)
  - テキストボックス上で Enter: 実装済み
  - [Add To-do] ボタン: 実装済み
- To-do の削除機能
  - 各アイテム右側の 'Delete': 実装済み

## CSS

- 大見出し: To-do List
  - 背景: 塗りつぶし
  - 見出し: 中央揃え

## JavaScript: 機能実装済み
