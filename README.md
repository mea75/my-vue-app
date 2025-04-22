# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about IDE Support for Vue in the [Vue Docs Scaling up Guide](https://vuejs.org/guide/scaling-up/tooling.html#ide-support).

# **日记**
# Vue入门
## 创建 Vue3 项目（用 Vite）
npm create vire@latest
输入项目名，选择 Vue，选择 JS

## 安装依赖
cd todo-list （进入项目文件夹）
npm install （安装依赖）

## 运行项目
npm run dev

***

# git入门

1. 以后每次更新项目时：（只用下面这3步）：

git add .
git commit -m "修改了 XXX"
git push


2. 想开新项目上传：在新文件夹里：
第一次用（初始化 + 绑定远程仓库）：

git init
git add .
git commit -m "项目初始化 首次提交"
（git branch -M main）
（把当前分支的名字强制改为 main，以前 Git 默认主分支叫 master，
现在为了更中性、统一，GitHub 等平台默认主分支叫 main）
git remote add origin 远程仓库地址
git push -u origin main


## 小记
* git add .
把所有修改的文件，准备提交。

* git commit -m "改了xxx"
提交一次修改，并写一个备注说明（提交日志）
-m 后面跟的是你对这次修改的说明，比如 "修复了 header 显示问题"

* git push
把刚才“提交”的内容上传到 GitHub
如果之前已经连好远程仓库，它就直接上传

* git branch -M main
把当前分支的名字强制改为 main。

* git push -u origin main（第一次上传用）
意思：第一次上传的时候告诉 Git：我以后就往这个远程仓库推了
-u 是 --set-upstream 的缩写，意思是绑定远程主干分支
origin：远程仓库的名字（默认都是 origin）
main：主分支的名字（以前叫 master，现在叫 main）
这个命令 只需要第一次 push 的时候写，以后只用 git push 就行了！

* git remote add origin [远程仓库地址]
意思：把本地项目连接到 GitHub 的远程仓库
你只需要做一次，比如新建了一个 GitHub 仓库：
git remote add origin https://github.com/mea75/my-vue-app.git



