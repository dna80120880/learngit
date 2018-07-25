Git is a version control system.
Git is free software.

git init （将当前目录变成版本库）
git add readme.txt (添加文件)
git commit -m "wrote a readme file"(提交)
i "xxxx" esc : wq enter
git commit --amend （可以对上一次的提交做修改）
git log （查看提交日志）
git log --pretty=oneline （单行显示提交日志）
git reset --hard HEAD^
git reset 1094a(版本回退)
git reflog （查看历史操作）
git diff HEAD -- readme.txt(查看工作区和版本库里面最新版本的区别)
