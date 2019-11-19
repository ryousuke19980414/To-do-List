# To-do List

この To-do List は HTML と CSS, JavaScript の 3 つで構成される Web アプリケーションです。

このアプリケーションの To-do データは、
Web Storage API の localStorage を使用してローカル環境(ブラウザ)に保存します。
この localStorage はオリジン単位でデータを保存するため、
開発時に Web サーバーの起動が必要になります。

(オリジンとは、URL の「スキーム://ホスト:ポート」の組み合わせのことです。)

## 貢献方法

- このプロジェクトをフォークする
- 学籍番号のブランチを作成して切り替える
- `submit/` 内に学生番号(小文字)のディレクトリを作成
  - 例: `ht99a999`
- `template/` の中身を、上記で作成したディレクトリ内にコピー
- 作成したディレクトリ内で作業
- ブランチをプッシュ
- プルリクエストを作成

## サーバーの起動方法

開発時には Web サーバーの起動が必要ですが、どんな方法で起動しても構いません。
ここでは、[Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/) を用いたサーバーの起動方法を紹介します。

- Visual Studio Code に `Live Server` という拡張機能を導入
  - Visual Studio Code の左側から拡張機能のタブを開いて検索
  - Ctrl + Shift + X でも拡張機能のタブを表示できる
- html ファイルが入っているディレクトリを Visual Studio Code で開く
  - ドラッグ & ドロップで開けます
- 右下の `Go Live` をクリックしてサーバーを起動
  - 起動時にポート番号が競合してなければ <http://localhost:5500/> でアクセス可能
  - 停止するには右下の `Port : xxxx` と書いてるところを選択

## template に加える変更

### HTML(inedx.html)

- [Delete selected items] ボタン
  - 選択された項目を削除する関数 `deleteSelected()` を呼び出すように

### CSS(style.css)

- 大見出し (h1) を中央揃えに
- body に対して Google Fonts を導入

### JavaScript(main.js)

- 特になし (必要な関数は実装済み)
