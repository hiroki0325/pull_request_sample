# pull request の練習リポジトリ

GithubのREADMEファイルはGithubマークダウン記法を使って記述する。
[markdownで行こう](https://gist.github.com/wate/7072365)

## git -> Githubへのpush(流れ)
1. ローカル上でディレクトリ作成(プロジェクト)
2. ディレクトリ内で`git init` コマンドを使い初期化
3. 何かしらの作成 or 編集
4. `git add ファイル名`コマンドで更新したものをステージングエリアに上げる
5. `git commit -m "コメント"`コマンドで変更を保存する
6. Github上でリモートリポジトリを作成
7. git remote add と git pushのコマンドをコピー
8. `git remote add origin githubのURL`コマンドでローカルとリモートを接続
9. `git push -u origin master`コマンドで保存したソースコードをリモートへ送る

## pullの流れ
1. リモートリポジトリをローカルより育てる
2. `git pull origin master`コマンドでリモート上の最新リポジトリをローカルに持ってくる

## Pull Requestの流れ
1. `git checkout -b ブランチ名`コマンドで新規ブランチを作成(同時にブランチの切り替えも行ってくれる)
2. なにかしらのアップデートをする
3. `git add .``git commit -m "コメント"`の順で保存する
4. `git push origin 新しいブランチ名`コマンドでリモート上に新しくブランチを作成してpush

### ブランチの切り替え方
+ `git checkout ブランチ名` コマンドでブランチを行き来出来る
    + 現在いるブランチ上で何かしらの変更を行っていた場合はその変更内容を保存もしくは削除してからブランチを移動すること

