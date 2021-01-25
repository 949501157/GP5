# readme文档
- 项目说明

# git操作
## 初始化版本库
- git init
- 初始化成功后，当前目录后面有（master）
- 

## 工作区
- 持有实际文件
- 我们平时增删改查的文件

# 提交到暂存区
-可以理解我们看不到的

## 本地仓库
- 可以理解为我们看到的一个地方
- 也是存在于用户电脑中
- 用于存储项目代码及版本项目记录等信息

## 提交到暂存区
- git add 文件名
- git 打的 . 将所有变动暂存区

## 提交到本地仓库
- git commit -m '第一次'

## 查看日志
- git log
- git reflog

## 版本回退
- git reset --hard HEAD^ 回退到上一个版本
- git reset --hard 版本号 回到指定版本

## 将本地仓库提交到远程

##正常提交