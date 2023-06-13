---
title: 安装Hexo
date: 2023-06-13 11:22:12
tags:
---
# 博客存放位置
{% note info simple %}
创建一个博客文件夹；建议命名为 xxx_Blog
{% endnote %}

# 进入文件夹所在终端
# hexo 安装
在终端中运行
```POWERSHELL
npm install hexo-cli -g
```

# hexo 初始化配置
```POWERSHELL
hexo -init
```

# 安装提交插件
```POWERSHELL
npm install hexo-deployer-git --save
```

# 本地查看效果
```POWERSHELL
hexo generate
```
```POWERSHELL
hexo server
```

