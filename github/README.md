- Download repository
  
git clone https://github.com/tsukaharakazuki/td.git
  
- List branches
  
git branch
  
- Create new branch (remove_directoryっていう名前のブランチ)
git checkout -b remove_directory origin/master
  
- Remove remove remove_directory
rm -rf tieup_report_gtm
  
- 作業ログ確認
git status
  
- Git remove
git rm -r tieup_report_gtm
  
- Git commit （作業内容を確定）
git commit -m "remove tieup_report_gtm"
  
- Push
git push origin remove_directory
  
>Guiで作業
  
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
