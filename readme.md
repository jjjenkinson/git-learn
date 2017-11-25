
# 学习git

@Author:    Jenkinson

@DateTiem:  2017-11-25 18:19:44

- [学习git](#%E5%AD%A6%E4%B9%A0git)
    - [git介绍](#git%E4%BB%8B%E7%BB%8D)
    - [常用的命令](#%E5%B8%B8%E7%94%A8%E7%9A%84%E5%91%BD%E4%BB%A4)
    - [github 上的markdown语法](#github-%E4%B8%8A%E7%9A%84markdown%E8%AF%AD%E6%B3%95)
        - [latex公式](#latex%E5%85%AC%E5%BC%8F)
        - [图片](#%E5%9B%BE%E7%89%87)
    - [参考资料](#%E5%8F%82%E8%80%83%E8%B5%84%E6%96%99)

## git介绍

- 工作区(workspace)
- 暂存区(stage)
- 本地仓库(repository)
- 远程仓库(remote)

- master git默认创建的主分支
- origin 远程库的名字

## 常用的命令

![Alt](./fig/bg2015120901.png "命令图示")

| 命令       | 功能                                 | 备注                        |
| :--------- | :----------------------------------- | :-------------------------- |
| git status | 显示有变更的文件                     |                             |
| git add    | 添加文件到暂存区                     |                             |
| git commit | 提交暂存区到仓库区                   |                             |
| git push   | 上传本地分支到远程仓库               |                             |
| git rm     | 删除工作区文件                       |                             |
| git pull   | 取回远程仓库的变化，并与本地分支合并 | 相当与git fetch + git merge |
| git merge  | 合并分支                             |                             |
| git clone  | 下载一个项目和它的整个代码历史       |                             |
| git branch | 列出本地所有分支                     |                             |
| git log    | 显示当前分支的版本历史               |                             |
| git diff   | 显示暂存区和工作区的差异             |                             |
| git fetch  | 将远程仓库的变动下载到本地仓库       |                             |

## github 上的markdown语法

### latex公式

暂时都不成功

$$ ax^{2} + by^{2} + c = 0 $$

![equation](http://latex.codecogs.com/gif.latex?x^2+y^2=z^2)

![equation](http://chart.googleapis.com/chart?cht=tx&chl=\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a})

![](http://latex.codecogs.com/gif.latex? \\frac{1}{1+sin(x)})

### 图片


参考资料
-------------------

1. [常用 Git 命令清单](http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html)
1. [Markdown语法手册](http://blog.leanote.com/post/freewalk/Markdown-%E8%AF%AD%E6%B3%95%E6%89%8B%E5%86%8C#title-9)
1. [如何在 GitHub 录入数学公式](http://www.jianshu.com/p/c169599726e1)