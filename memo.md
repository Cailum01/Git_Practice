git config --list    
git config set --global init.defaultbranch main
git log
git status
git push -u origin master
git diff
git switch <branch name>
git checkout README.md       #取消該檔案的修改 類似undo
git branch -m <old branch name> <new branch name>
git log --oneline
git push -u origin main

mkdir my-project
cd my-project
git init
Initialized empty Git repository in
/Users/you/my-project/.git/
ls -a
•git

#加入單一檔案
git add index.html
#加入整個資料夾
git add src/
#使用萬用字元
git add *.css
加入目前目錄下所有變更
git add.
#互動式挑選部分變更
git add -p

#建立版本庫
git init
#查看狀態
git status
git add <file>
#加入暫存區#提交
git commit -m "msg"
#取消暫存
git reset <file>
#查看歷史
git log --oneline --graph
#建立並切換分支
git switch -c <branch>
#合併分支
git merge <branch>