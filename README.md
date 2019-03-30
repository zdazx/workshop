# workshop
git learnign

git add -p 展现出所有更改的文件

git push -u origin master
u的意思是把本地master push到远端的origin master 之后就会默认记录不需要再填写了

git branch -a 可查看远端分支

git branch查看本地分支

git checkout -b name 创建并跳转到新分支

git checkout name跳转分支

git -commit --ament 与上一次commit合二为一

git push -f  强制将本地所有东西推上去 远程仓促的东西编程自己本地的   该命令要慎用！！！ force

git rebase master 拉下来与主分支上有冲突的东西解决冲突

git rebase --continue 跳到下一个需要解决冲突的地方  如果跳出master说明冲突解决了  如果跳另外一个的话 说明还有冲突需要解决

此时push需要使用 git push -f  记住push到自己的分支上 只有解决冲突后再merge到主分支


推荐《Pro Git》