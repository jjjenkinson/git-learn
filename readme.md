学习git
================

@Author:    Jenkinson
@DateTiem:  2017-11-25 18:19:44


- 工作区(workspace)
- 暂存区(stage)
- 本地仓库(repository)
- 远程仓库(remote)

- master git默认创建的主分支
- origin 远程库的名字

常用的命令:

--------------
![Alt](./fig/bg2015120901.png "命令图示")

| 命令        | 功能        | 备注    |
|:-----------|:-----------|:--------|
| git status    | 显示有变更的文件 |   |
| git add       | 添加文件到暂存区  |   |
| git commit    | 提交暂存区到仓库区  |   |
| git push      | 上传本地分支到远程仓库   |   |
| git rm        | 删除工作区文件   |   |
| git pull      | 取回远程仓库的变化，并与本地分支合并    | 相当与git fetch + git merge |
| git merge     | 合并分支   |   |
| git clone     | 下载一个项目和它的整个代码历史   |   |
| git branch    | 列出本地所有分支  |   |
| git log       | 显示当前分支的版本历史   |   |
| git diff      | 显示暂存区和工作区的差异  |   |
| git fetch     | 将远程仓库的变动下载到本地仓库   |   |
