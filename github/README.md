## 現在のGithubファイルをダウンロード
  
`$ git clone https://github.com/tsukaharakazuki/td.git`
 
## branchの作成 

- branchの確認 ->DLしたフォルダにCD
  
`$ git branch`
  
- 新しいbranchを作成 (以下ではremove_directoryという名前のブランチ)

`$ git checkout -b remove_directory origin/master`

## ファイルの削除

`$ rm -rf tieup_report_gtm`
  
- 作業ログ確認

`$ git status`
  
- Githuからも削除_Git remove

`$ git rm -r tieup_report_gtm`

## 作業内容を確定

- Git commit 
  
`$ git commit -m "remove tieup_report_gtm"`

## 作業をGitに送信

- Push
  
`$ git push origin remove_directory`
  
## Githubホームページ上で作業
  
  
>参考
  
$ git checkout master
  
git branch -D remove_directory
  
git pull
最新版更新
  
mv
ファイル名変更
  
コメントつけない場合
:q
  
- tieup-reportを追加
git add tieup_report
