####新建分支  
git checkout -b dev  ==  git branch dev + git checkout dev  
####切换分支  
git checkout dev  ==  git switch dev  
####合并分支  
git merge dev  //将dev合并到当前分支上  
####删除分支  
git branch -d dev  
####新建标签  
git tag <tag-name>  
####标签信息  
git tag -a <tag-name> -m 'abcd...'  
####查看标签  
git tag  
####保护工作现场  
git stash
