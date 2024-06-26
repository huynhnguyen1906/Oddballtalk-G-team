[英語版](README.en.md)

# OddballTalk

OddballTalk は ３日間の WEB 合宿エベントで Express.js で構築されたマッチングアプリケーションです。

<p align="center">
  <img src="./src/public/images/readme1.png" width="24%"  />
  <img src="./src/public/images/readme2.png" width="24%"  />
  <img src="./src/public/images/readme3.png" width="24%"  />
  <img src="./src/public/images/readme4.png" width="24%"  />
</p>

## 説明

このアプリケーションは、ユーザーが会話を作成および管理できるようにします。

## インストール

このアプリケーションをインストールして実行するには、次の手順に従ってください。

1. このリポジトリをクローンします。
2. `npm install` を実行して依存関係をインストールします。
3. `.env.example` ファイルを元に `.env` ファイルを作成し、必要な情報を記入します。
4. `npm run dev` を実行してアプリケーションを起動します。

## プロジェクトの構造

このプロジェクトには、次のディレクトリが含まれています。

- `src/config`: `firebase-config.js` や `viewEngine.js` などの構成ファイルが含まれています。
- `src/controllers`: `apiControllers.js` などのコントローラが含まれています。
- `src/public`: CSS、JavaScript、画像などのリソースが含まれています。
- `src/routers`: `api.js`、`uploadTest.js`、`web.js` などのルータが含まれています。
- `src/views`: EJS ビューファイルが含まれています。

## 著者

OddballTalk は、[Huynh](https://github.com/huynhnguyen1906) と [IidaTomonari](https://github.com/Iidaaaaaa) によって作成されました。

## 貢献

貢献は歓迎します。リポジトリをフォークして変更を加えたプルリクエストを作成してください。
