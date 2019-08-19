git 在开发种的正常使用

1. 创建一个普通Java项目, 然后使用git init 命令将其纳入git的管理

2. 在github创建相应的git仓库

3. 修改.gitignore文件

4. 将本地仓库上传到远程仓库

5. 使用git branch filename 创建分支(dev, test)

6. 使用git push origin branchname 命令将本地分支上传到远程分支

7. 首先使用git checkout dev 定位到dev分支, 然后使用命令git checkout -b branchname 在git dev分支创建新的分支
   使用git push origin branchname 将新的分支上传至远程仓库

8. 定位到开发分支的子分支(开始编写代码)

9. 写完之后使用git commit -m "" 命令提交写完的代码

10. 使用git push origin branchname(当前开发分支的子分支名称) 命令向远程分支推送代码

11. 首先定位到开发分支, 然后使用git merge branchname(开发分支的子分支) 命令合并开发分支的子分支

12. 使用git push origin branchname(dev) 命令向远程开发分支推送代码

13. 在开发环境自测完成之后, 将开发分支的子分支合并到test分支, 然后推送到test的远程分支上

14. 如果测试人员发现问题, 之后再在开发分支上新建一个 修改bug的分支, 然后修改bug, 后面的步骤同上

15. 如果写的代码经过了测试, 我们就可以将代码合并到主分支上面.














