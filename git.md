## Git 与 SVN 区别
Git 不仅仅是个版本控制系统，它也是个内容管理系统(CMS)，工作管理系统等。

如果你是一个具有使用 SVN 背景的人，你需要做一定的思想转换，来适应 Git 提供的一些概念和特征。

Git 与 SVN 区别点：


1. [git下载](https://git-scm.com/)
2. [tortoisegit下载](https://tortoisegit.org/download/)
3. [git教程参考](https://backlog.com/git-tutorial/cn/)

创建git账户
git-bash

* 先安装 git,然后安装 torotise，再安装 torotise语言包

## 远程的git库
gitlib 与 github

## 以github 
* 注册 github 账号

* https://github.com/15013716105/0420.git
* git@github.com:15013716105/0420.git

```
//…或在命令行上创建新的存储库
echo "# 0420" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/15013716105/0420.git
git push -u origin master
```
```
…或从命令行推送现有存储库
git remote add origin https://github.com/15013716105/0420.git
git push -u原始主机
```



