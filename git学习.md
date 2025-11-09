|功能|命令|例子|注|
|:---:|:---:|:---:|:---:|
|创建库|git init||在一个空目录下创建|
|添加文件|git add,git commit|Git is a version control system.Git is free software.....|commit可提交多个修改|
|告诉我们历史记录|git log||使用--pretty=oneline可以简化信息|
|回档|git reset|git reset --hard HEAD^，git reset --hard 1094a|--hard会回退到上个版本的已提交状态，而--soft会回退到上个版本的未提交状态，--mixed会回退到上个版本已添加但未提交的状态;HEAD^上一个版本，HEAD^^，HEAD~100,可用commit id前几位代替|
|查看一下状态|git status|
|查看工作区和版本库里面最新版本的区别|git diff HEAD -- file|git diff HEAD -- readme.txt|
|弃工作区的修改|git checkout -- file|
|把暂存区的修改撤销掉|git reset HEAD <file>|git reset HEAD readme.txt|
|从版本库中删除该文件|用命令git rm删掉，并且git commit|
|把本地库的内容推送到远程|git push[^push]|
|查看远程库信息|git remote -v|
|删除远程库|git remote rm <name>|
|克隆一个本地库|git clone|git clone git@github.com:michaelliao/gitskills.git|


[^push]:先创建SSH Key,看看有没有.ssh目录，如果有，再看看这个目录下有没有id_rsa和id_rsa.pub这两个文件,如果没有，打开Shell（Windows下打开Git Bash），创建SSH Key：ssh-keygen -t rsa -C "youremail@example.com"
