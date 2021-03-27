# Electron Sample - リンクをクリックすると標準ブラウザで開く

## 解説ページ
* [[Electron] リンクをクリックすると標準Webブラウザで開く](https://blog.katsubemakito.net/nodejs/electron/click-to-defaultbrowser)

## 準備
Gitでリポジトリを取得します。
```shellsession
$ git clone https://github.com/katsube/electron-sample-linkclick
```

Node.jsがインストールされている環境で以下のコマンドを実行し、必要なライブラリを取得します。
```shellsession
$ cd electron-sample-linkclick
$ npm install
```

## 実行方法
以下でプレビューを行います。
```shellsession
$ npm start
```

以下のビルド用コマンドを叩くと、各OS用のインストーラーが作成されます。
```shellsession
$ npm run build-win
$ npm run build-mac
```
