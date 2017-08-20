# WWA Debugger
## 事前準備
Node.jsをインストールしてください。

Windowsの人は[公式サイト](https://nodejs.org/ja/download/)の`LTS推奨版`から`Windows Installer(.msi)`をダウンロードし、インストールしてください。

LinuxやmacOSの人は、apt・dnf・pacman・brewなど、お使いのパッケージマネージャーやndenvを利用して導入してください。

次に`package.json`をテキストエディタで開いてください。7行目付近の以下の記述で、このファイルがある場所からの相対パスを`../`の部分を編集して指定します。

```json
"scripts": {
    "start": "http-server ../ -o"
},
```

## 使用方法(Windowsの人)
`start.bat`をダブルクリックすると、ブラウザが開いてデバッグできるようになります。

## 使用方法(CUIに慣れている人向け)
npmで依存関係を解決すればstartできるようになります。

```bash
$ npm install
$ npm start
```
