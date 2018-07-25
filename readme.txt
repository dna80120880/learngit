Git is a version control system.
Git is free software.

git init （将当前目录变成版本库）
git add readme.txt (添加文件)
git rm test.txt(删除文件)
git commit -m "wrote a readme file"(提交)
i "xxxx" esc : wq enter
git commit --amend （可以对上一次的提交做修改）
git log （查看提交日志）
git log --pretty=oneline （单行显示提交日志）
git reset --hard HEAD^
git reset 1094a(版本回退)
git reflog （查看历史操作）
git status (查看状态)
git diff HEAD -- readme.txt(查看工作区和版本库里面最新版本的区别)
git checkout -- readme.txt(回到最近一次commit或add时的状态)
git reset HEAD readme.txt（撤销暂存区的修改）
git remote add origin git@github.com:dna80120880/learning.git()
git remote -v(查看远程库的地址)
git remote set-url origin [url]
git remote rm origin
git remote add origin [url]      (修改远程库地址)
git push -u origin master (将本地库内容推送至远程库   由于远程库是空的，我们第一次推送master分支时，加上了-u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。)
ssh-keygen -t rsa -C “857201129@qq.com”(生成SSHKEY)（33445566）
ssh-add 文件名 （添加密钥到ssh）
git clone git@github.com:michaelliao/gitskills.git（克隆一个本地库）
git checkout -b dev（创建并切换至一个新的分支dev）相当于git branch dev // git checkout dev两条命令
git branch (查看当前分支)

Creating a new branch is quick and simple
