设置

1.设置全局用户名,信息在~/.gitconfig中
git config --global user.name xxxx

2.设置全局邮箱地址，信息在~/.gitconfig中
git config --global user.email xxx@xxx.com

3.将当前目录配置成git仓库，信息隐藏在.git文件夹中
git init

**4.将xx文件添加到暂存区
git add xxx
git add .   将所有待加入暂存区的文件加入暂存区

**5.将暂存区的内容提交到当前分支
git commit -m "xxxxx"

6.查看仓库状态
git status

7.查看xx文件相对于暂存区修改了什么内容
git differ xx

**8.将当前分支推送到远程仓库
git push -u

9.将远程仓库xx下载到当前目录下
git clone git@...

**10.将远程仓库的当前分支与本地仓库的当前分支合并
git pull

