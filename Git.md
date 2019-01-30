> 创建分支
> `git checkout -b 新分支名称` 相当于 
* `git branch 新分支名称`
* `git checkout 新分支名称`
> 查看远程库分支
* `git branch -r`
> 将本地分支推送到远程分支
* `git push origin new_branch:new_branch` (本地分支与远程分支同名)
> 删除远程分支
* 方法一 `git push origin  :new_branch` (推送一个空分支到远程分支)
* 方法二 `git push origin --delete new_branch`
> 查看分支状态 
* `git status`