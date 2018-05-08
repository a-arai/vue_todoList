## vue.jsでtodoListを作成

### DEMO
動きはこちらから確認できます。
https://a-arai.github.io/DEMO/vue_todoList/

ロジックの記載がされているjsファイル
https://github.com/a-arai/vue_todoList/blob/master/js/main.js

・マウントされるタイミングでlocalStorageからデータを読み込む。
（リロードしてもリストが保持される)

・リストのデータが変更されたら、watchを使用してhandlerに記載した処理を行う
