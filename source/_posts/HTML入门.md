---
title: HTML基础
date: 2022-09-24 22:50:52
categories:
- 前端
tags:
- HTML
- 入门
---

## 什么是 HTML
> 超文本标记语言（Hypertext Markup Language），一种用于定义**内容结构**的标记语言，由一系列元素组成

## HTML 元素

```html
<p class="editor-note">Hello World!</p>
```
其中包含：
* 开始标签
* 结束标签
* 内容
* 属性（attribute）：属性名、等号、属性值

以上就是一个完整的元素，当然，这些不一定都要包含，比如 `image` 标签一般没有内容，`image` 也称为空标签。
元素嵌套：一个元素放在另一个元素之中

## 文档详解
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <img src="images/firefox-icon.png" alt="My test image">
  </body>
</html>
```
其中，包含：
* `<!DOCTYPE html>` 文档类型，现在仅用于保证文档正常读取
* `html` 元素：包含整个页面内容
* `head` 元素: 头部，定义一些用户不可见的内容，比如样式、字符集
* `body` 元素: 显示给用户查看的内容

## 一些元素
1. image 标签：
```
<img src="images/firefox-icon.png" alt="My test image">
```
2. 标题：`<h1>` - `<h6>`，不要跨级，不要使用标题元素来加大加粗字体，保持结构清晰
3. `<p>` 段落
4. `<a>` 链接
```
<a href="https://www.baidu.com">百度首页</a>
```
5. 列表：分无序列表（Unordered List）和有序列表（Ordered List），分别用 `<ul>` 和 `<ol>` 元素。列表每个项目都可以用元素 `<li>` 包围。有序（无序）列表和 markdown 语法显示差不多