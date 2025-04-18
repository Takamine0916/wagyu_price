# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
・リモートリポジトリは、GitHubなどのネット上にあるリポジトリのこと(チーム)<br>
・ローカルリポジトリは自身のPCのGitないのリポジトリのこと(個人)<br>
⇒リモートとローカルに分けることにより、効率よく、安全にチームで開発できる<br>
　(リポジトリ＝プロジェクトのファイルと、その変更履歴をまとめて管理する場所のこと)
## プッシュとマージの違いは何でしょうか？
.・プッシュ：ローカルリポジトリからリモートリポジトリに変更を変更させる<br>
・マージ：ローカルリポジトリ内にブランチを統合する<br>
　(ブランチ＝複数人で作業分担ができるよう、制作物を切り取ること)
## コミットとプッシュの違い
・コミット：ローカルリポジトリ内で変更履歴を残すこと<br>
・プッシュ：ローカルリポジトリでコミットした履歴をリモートリポジトリへ送ること
## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
コミット名の頭に接頭辞（プレフィックス）をつける。<br>
これによりコミットの内容を予想しやすくなるため、レビュアーの負荷を軽減させたり、コミットを検索できる。<br>
また変更した箇所と変更した機能の内容が伝わるようなるべく端的に書く<br>
<br>
(プレフィックスの例)<br>
feat: 新しい機能の追加<br>
fix: バグの修正<br>

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
・ローカルでマージ：ブランチの辺功を取り込むための操作だが、自分のPCだけで完結する(個人作業)<br>
・プルリクエストでマージ：ブランチの変更を取り込むための操作だが、リモート状で操作する(チーム開発)
## コンフリクトを起こしてしまった場合、どう対処すべきですか？
どのファイルがコンフリクトしているかを確認し、どちらの変更を採用するか編集する。<br>編集後はマージする。