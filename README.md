# 使い方
1. ソースコード一式をダウンロードする
2. Google Chromeの拡張機能設定ページを開く
3. [デベロッパー モード]にチェックを入れる
4. [パッケージ化されていない拡張機能を読み込む]ボタンを押して、ダウンロードしてきたソースコード一式が含まれるディレクトリを指定する(これで拡張機能がインストールされる)
5. Google Chromeの[開発/管理]メニューから[デベロッパー ツール]を起動する( **デベロッパーツールを起動させておかないと動作しません** )
6. 上記手順で拡張機能をインストールしたGoogle Chromeで艦これにアクセスする
7. 艦これを操作する(母港画面を開いたりする)と、ゲーム画面の右に疲労度が数値で表示される(49が平常、50以上でキラキラ)

# 仕組みなど
元々Google Chromeにあるネットワークをモニタリングする機能を使って、疲労度だけを見やすくしている。
余計なリクエストを増やしたり、怪しい動作を埋め込んだりはしていないが、気になる方はソースコードのご確認を。
(以前、次マスの敵IDを表示する機能をやっつけで追加したままコミットしてしまい、そのままになっています。すみません)

