# starter-kit(npm-script)
npm-scriptを使ったフロントエンド開発環境

## 2017.11.19(sun)

開発途中

## 2017.11.26(sun)

- node sassからpostcssに変更
- windows環境でも使用できるようにnpm-run-allをinstall
- css:FLOCSSに変更


## 使い方

プロジェクトのディレクトリ作成
````
mkdir -m 755 PROJECT_DIR
cd PROJECT_DIR
````
クローンする
````
git clone https://github.com/cidermitaina/starter-kit-npm-script.git
````
移動してnmpをインストール
````
cd starter-kit-npm-script
npm install
````
サーバー起動
````
npm run start
````
http://localhost:3000/にブラウザーでアクセスする。

## 作業

./src以下のファイルで作業します。作業ファイルはコンパイルされて、
./public/assets/css/style.css
./public/assets/js/bundle.js
に書き込まれます。
