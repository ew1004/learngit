#### 本地库初始化  
git init  
#### 查看当前库状态  
git status  
#### 查看不同  
git diff filename
#### 新建分支  
git checkout -b dev  ==  git branch dev + git checkout dev  
#### 切换分支  
git checkout dev  ==  git switch dev  
#### 合并分支  
git merge dev  //将dev合并到当前分支上  
#### 删除分支  
git branch -d dev  
#### 新建标签  
git tag <tag-name>  
#### 标签信息  
git tag -a <tag-name> -m 'abcd...'  
#### 查看标签  
git tag  
#### 保护工作现场  
git stash
#### 查看远程库信息  
git remote -v  
#### 关联远程库  
git remote add <name> git@github.com:ew1004/learngit.git  
git push -u <name> master //第一次添加时，加上-u参数  
git push <name> master //后续推送即可简化命令  
