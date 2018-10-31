# git心得体会 #
- 为什么用
- 目标
- 常用命令
- 资料

----------
## 为什么用

> 能够开始使用git常用命令进行项目上传clone，结合idea工具开发springboot
## 目标

> 快速掌握git常用命令，从而使用git代替svn工具（达到分布式提交）
 
## 常用命令(备注-加粗是用的最多的)
> 1.git --no-ff(分支管理策略)   
> 2.git stash (bug修复)  
> 3.git pull --rebase origin master (本地库与远程库不同)  
> 4.**git remote -v (显示更详细的github信息)**  
> 5.git log --graph （分支图）  
> 6.git stash list （刚才存index的地方）  
> 7.git commit -m （提交）  
> 8.**git add . (全部文件) **   
> 9.git push -u origin master （向远程库更新数据）  
> 10.git branch （查看分支）  
> 11.git branch -D dev （删除掉没有合并的分支）  
> 12.git log （查看日志）  
> 13.git reflog（历史日志）  
> 14.git reset --HEAD (撤回)  
> 15.ls -ah (查看数据)  
> 16.git status （查看状态）  
> 17.git tag -a v1.0 -m "Version 1.0" (指定版本，标签)  
> 18.git show v1.0 （查看标签说明文字）    
> 19.git log --pretty=online --abbrev-commit （找到历史提交的commit id）     
> 20.git checkout -b dev (创建分支)    
> 21.git branch -d dev(删除分支)    
> 22.git merge dev （合并某分支到master）    
> 23.git checkout master(切换分支)     
> 24.git clone git@github.com:Zhangzhuogh/demo.git (clone)    
> 25.**git remote rm origin (删除已关联的origin远程库)**    
> 26.git remote add origin git@github.com:Zhangzhuogh/demo.git(关联github远程库)    
> 27.**git push origin master(推送到github)**       
> 28.git reset HEAD <file> （把暂存区修改撤销掉，重新放回工作区）  
> 29.git rebase （可以把本地未push，由原来的分支改变成一条）
> 30.git branch --set-upstream branch-name origin/branch-name(建立本地分支与远程分支的关联)    

## 资料
- git  
  [[git教程]](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
