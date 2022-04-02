#### 生成公钥

ssh-keygen 

#### 创建仓库命令

git init 初始化仓库
git clone 拷贝一份远程仓库，也就是下载一个项目

#### 提交与修改

git add	添加文件到仓库 git add . 添加全部
git status	查看仓库当前的状态，显示有变更的文件
git diff	比较文件的不同，即暂存区和工作区差异
git commit	提交暂存区到本地仓库
git checkout -- <file>	撤销修改
git rm 	删除工作区文件
git mv	移动或重命名工作区文件

#### 时光穿梭机

git reset --hard HEAD 回退版本 HEAD指向的版本就是当前版本 ^回退一次 ^^回退两次……
git reset --hard commit_id 回到指定版本
git log	查看历史提交记录
git reflog 查看历史命令

#### 提交日志

git log	查看历史提交记录
git blame <file> 以列表心事查看指定文件的历史修改记录

#### 远程操作

git remote 	远程仓库操作
git fetch	从远程获取代码库
git pull	下载远程代码并合并
git push	上传远程代码并合并 

#### Git分支管理

git branch (branchname)	创建分支
git checkout (brachname)	切换分支
git merge	合并分支
git branch	列出分支
git branch -d (branchname)	删除分支

