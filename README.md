## 项目介绍

非web开发的模板项目, 仅集成了git规范流程的工具, 适用于任何语言

- commitizen(**帮助git commit时规范提交**)
- husky(**检查git commit时, 是否遵守了规范提交**)

## 使用流程

1. git clone项目到本地后, 修改文件夹名称为你的项目名称

2. 安装依赖(要求本地有node开发环境, 如果没有, 可下载`nvm`)

   ```
   pnpm i 
   ```

3. 安装完依赖后, 可以用命令提交一次(不需要执行git add ., 已集成在commit命令里面), 作为项目的init commit

   ```
   pnpm run commit
   ```

4. 开始业务开发, 记得提交时一定用`pnpm run commit`! 否则会commit失败

## 版本记录

- node 16.20.2
- npm 8.9.14