$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
$ git init
$ git add readme.txt
$ git commit -m "wrote a readme file"
$ git status
$ git diff readme.txt 
$ git log --pretty=oneline
$ git reset --hard HEAD^
$ git reset --hard 1094a
$ git diff HEAD -- readme.txt 
$ git checkout -- readme.txt	丢弃工作区的修改
$ git reset HEAD readme.txt		暂存区的修改撤销掉
$ git rm test.txt
$ ssh-keygen -t rsa -C "youremail@example.com"
$ git remote add origin git@github.com:michaelliao/learngit.git 	本地关联远程库
$ git push (-u) origin master		我们第一次推送master分支时，加上了-u参数
$ git clone git@github.com:michaelliao/gitskills.git
$ git checkout -b dev 	-b参数表示创建并切换
$ git branch
$ git checkout master
$ git merge dev
$ git branch -d dev
$ git merge --no-ff -m "merge with no-ff" dev
$ git stash
$ git stash list
$ git stash pop
$ git remote (-v) 	-v表示更详尽
$ git checkout -b dev origin/dev
$ git pull
$ git branch --set-upstream-to=origin/dev dev
$ git log --graph --pretty=oneline --abbrev-commit
$ git rebase
$ git tag <tagname>
$ git tag
$ git tag <tagname>
$ git show <tagname>
$ git tag -a <tagname> -m "version 0.1 released" 1094adb
$ git tag -d <tagname>
$ git push origin <tagname> 	第一次是推送，第二次是删除
$ git push origin --tags
