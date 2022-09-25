---
title: Hexo使用
date: 2022-09-24 23:45:35
tags:
- Hexo
---

# 入门

建议看[官方文档](https://hexo.io/zh-cn/docs/)

# 问题解答

#### 标签和分类设置
Front-matter 中设置对应的 `tags` 和 `categories` ，例如：
```
categories:
- 前端
tags:
- HTML
- 入门
```

#### 字体大小问题
Hexo 自带主题中字体为 14px，可在 `themes/landscape/source/css/_variables.styl` 中修改 `font-size` 值

#### blockquote （markdown 中 > ）显示居中问题
可能要了解 CSS ，才能解决