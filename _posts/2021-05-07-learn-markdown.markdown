---
layout: post
title:  "learn Markdown!"
date:   2021-05-07 13:04:47 +0800
categories: jekyll update
---

# 关于Markdown

Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。

Markdown 语言在 2004 由约翰·格鲁伯（英语：John Gruber）创建。

Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。

Markdown 编写的文档后缀为 .md, .markdown。

# Markdown 语法学习

## Markdown 标题

Markdown 标题有两种格式。

1、使用 = 和 - 标记一级和二级标题
= 和 - 标记语法格式如下：

我展示的是一级标题
=================

我展示的是二级标题
-----------------

## Markdown 段落格式

Markdown 段落没有特殊的格式，直接编写文字就好，段落的换行是使用两个以上空格加上回车。

新的段落。

## Markdown 列表

Markdown 支持有序列表和无序列表。

无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容：

* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项

## Markdown 区块

Markdown 区块引用是在段落开头使用 > 符号 ，然后后面紧跟一个空格符号：

> 区块引用
> 菜鸟教程
> 学的不仅是技术更是梦想

## Markdown 代码

如果是段落上的一个函数或片段的代码可以用反引号把它包起来（`），例如：

`printf()` 函数

代码区块
代码区块使用 4 个空格或者一个制表符（Tab 键）。

你也可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）：

```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```

## kdown 链接

链接使用方法如下：

[链接名称](链接地址)

或者

<链接地址>
例如：

这是一个链接 [百度](https://baidu.com)

## Markdown 图片

Markdown 图片语法格式如下：

![alt 属性文本](图片地址)

![alt 属性文本](图片地址 "可选标题")
开头一个感叹号 !
接着一个方括号，里面放上图片的替代文字
接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。
使用实例：

![RUNOOB 图标](https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png)

## Markdown 表格

Markdown 制作表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。

语法格式如下：

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |