---
title: gitee
date: 2023-04-10 20:29:35
tags: 
---
## 简单入手命令
### 改变目录
``` bash
cd : 
```
### 回退到上一个目录，直接cd进入默认目录
``` bash
cd . . 
```
### 显示当前所在的目录路径。
``` bash
pwd : 
```
### 都是列出当前目录中的所有文件，只不过ll(两个ll)列出的内容更为详细。
``` bash
ls(ll):  
```
### 新建一个文件 如 touch index.js 就会在当前目录下新建一个index.js文件。
``` bash
touch : 
```
### 删除一个文件, rm index.js 就会把index.js文件删除。
``` bash
rm:  
```
### 新建一个目录,就是新建一个文件夹。
``` bash
mkdir:  
```
### 删除一个文件夹, rm -r src 删除src目录
``` bash
rm -r :  
```
### 切勿在Linux中尝试！删除电脑中全部文件！
``` bash
rm -rf / 
```
### 移动文件, mv index.html src index.html 是我们要移动的文件, src 是目标文件夹,当然, 这样写,必须保证文件和目标文件夹在同一目录下。
``` bash
mv 
```
### 重新初始化终端/清屏。
``` bash
reset 
```
### 清屏。
``` bash
clear 
```
### 查看命令历史。
``` bash
history 
```
### 帮助。
``` bash
help 
```
### 退出。
``` bash
exit 
```
``` bash
、#表示注释
```
## 查看配置命令
### 查看配置
``` bash
 git config -l
```
### 查看系统config
``` bash
git config --system --list
```
### 查看当前用户（global）配置
``` bash
git config --global  --list
```
## Git相关的配置文件：
``` bash
（1）、Git\etc\gitconfig  ：Git 安装目录下的 gitconfig     --system 系统级
``` bash
（2）、C:\Users\Administrator\ .gitconfig    只适用于当前登录用户的配置  --global 全局
```
``` bash
git config --global user.name "zilin"  #名称
```
``` bash
git config --global user.email 24736743@qq.com   #邮箱
```
``` bash
git config --global --list
```