# app_wifi-cafe-search

環境構築手順メモ[WIP]

参考
- https://facebook.github.io/react-native/docs/getting-started.html(公式)
- https://mae.chab.in/archives/59673


## ReactNativeの導入
#### 下記実行

```
# yarnインストール
npm install -g yarn

# create-react-native-appコマンドの追加
yarn global add create-react-native-app

# ReactNativeプロジェクトを作成したいディレクトリに移動し、create-react-native-appコマンドを叩く
create-react-native-app　XXXX(任意のアプリ名)
(Choose a template type: blank)

# アプリのフィルダに移動し、シュミレーターを起動
cd XXXX
expo start
※ nodeのバーションでreact-native initができない場合
nvm install 8.3 --reinstall-packages-from=node 

# ①でブラウザが表示されたら、QRコードをクリックしてシュミレーター起動
Run on iOS simulator

```

## Typescript


## flow
http://tomoima525.hatenablog.com/entry/2017/10/03/141733

## expoの導入
https://tech.maricuru.com/entry/2018/04/09/142341
https://qiita.com/yutasuzuki/items/046e120eac9b20bed487
https://qiita.com/YutamaKotaro/items/dac047715896dc11e555

## redux
https://qiita.com/clocker/items/331f20c02cc0d01be062


## サーバー
・firebase
https://qiita.com/MeiTen/items/67c97254d2ebeecbf4a2
