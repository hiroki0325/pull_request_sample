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
