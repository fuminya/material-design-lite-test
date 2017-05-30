# sample-material-design-lite

[Material Desgin Lite](https://github.com/google/material-design-lite)の勉強のためのテストリポジトリ。

## 動作方法

yarnとwebpackを利用しています。
yarnのインストールは[こちら](https://yarnpkg.com/lang/en/docs/install/)を参考。

```terminal
$ yarn install
$ 
$ yarn run webpack-dev-server -- --inline --hot
$ # webpack-dev-serverを使う
```

サーバが起動したら、```http://localhost:8080```で確認

ビルドは```yarn run webpack```を実行

## その他利用パッケージ

* htmlhint
* csslint
* eslint
