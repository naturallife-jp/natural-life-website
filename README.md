# Natural Life 公式サイト

HTML・CSS・JavaScriptだけで動く1ページのサイトです。アプリのインストールやビルドは不要です。

## 表示する

`index.html` をブラウザで開くと表示できます。ローカルサーバーを使う場合は、ターミナルでこのフォルダに移動して `python3 -m http.server 8000` を実行し、ブラウザで `http://localhost:8000` を開いてください。スマートフォン幅で確認するときは、ブラウザの開発者ツールでモバイル表示に切り替えます。

## よく変更する場所

- **公式LINE**: `index.html` の「https://lin.ee/uIrapsE」を公式の友だち追加URLに置き換えます。トップ、CONTACT、フッターの3か所に同じリンクを設定しています。
- **プロフィール写真**: `assets/images/profile.jpg` を追加し、`index.html` の「profile-placeholder」ブロックを画像表示に差し替えます。
- **トップ写真**: `assets/images/forest-hero.jpg` を同じファイル名の写真に置き換えます。横幅の広い写真がおすすめです。
- **文章**: `index.html` の該当する見出しや文章を編集します。
- **色・レイアウト**: `styles.css` を編集します。基本色はファイル先頭のCSS変数にまとめています。

Google Fontsの読み込みにはインターネット接続が必要です。接続できない場合は端末の標準フォントで表示されます。
