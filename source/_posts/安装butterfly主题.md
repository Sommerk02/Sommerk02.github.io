---
title: 安装butterfly主题
date: 2023-06-13 11:10:50
tags:
---
# 安装butterfly主题
克隆到themes文件夹中
在终端中运行
```POWERSHELL
git clone -b master https://github.com/jerryc127/hexo-theme-butterfly.git themes/butterfly
```
# 应用主题
修改 Hexo 根目录下的 _config.yml，把主题改为 butterfly
```POWERSHELL
theme: butterfly
```
# 安装渲染插件
```POWERSHELL
npm install hexo-renderer-pug hexo-renderer-stylus --save
```
# 升级建议
在 hexo 的根目录创建一个文件 _config.butterfly.yml，并把主题目录的 _config.yml 内容复制到 _config.butterfly.yml 去。( 注意: 复制的是主题的 _config.yml ，而不是 hexo 的 _config.yml)
