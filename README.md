# practice
練習用リポジトリです

Step0. 準備
* git clone
* git branch <作業用ブランチ>
* git checkout <作業用ブランチ>
* git checkout master

Step1. 自分用のディレクトリを作ってReadme.md ファイルを作り、practice 直下に設置してください
* git checkout <作業用ブランチ>
* git add <README.md パス>
* git commit
* git push
* プルリクを投げる

Step2. 複数ファイルを作成し、一部のファイルのみコミットしてください
* git add <コミット対象ファイル> or git commit <コミット対象ファイル>

Step3. コミットの取り消し
* git log --oneline -5
* git status
* git diff
* git reset HEAD^

Step3. Common ディレクトリ配下のReadme の中身を修正してください
* git fetch -p
* git merge origin/master
