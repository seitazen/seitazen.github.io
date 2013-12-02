---
title: 用 Markdown 写作
layout: post
tags: markdown
categories: frontend
published: true
---

不会用 Markdown 的人会把它写得乱七八糟，比如说我。
掌握好常用的，也许就不会写得那么乱。

**超链接**

    [text](url)
**图片**
  
    ![text](img src)

**关于标题**

h1 和 h2 标题可以以下方式表示： 
    
    This is an h1 title
    ==================
    This is an h2 title
    ------------------
    
不过对于 h1 ~ h6 来说，有一种是通用的，相应数量的 # 号，对应着 h1 ~ h6：

    # An h1 title
    ## An h2 title 
    ### An h3 title
   
标题后面可以加上相应数量的 # 号，但这不是必须的。

**关于引用**

引用可以使用 大于符号 ( > ) 表示,注意是半角，而不是中文中的大于符号。栗子：

	>This is a blockquote
    >But don't be stupid
    >It's useful as well
    
**关于代码**

代码显示方式有很多，可以 Tab 一下，或者敲 4 个空格。如果想高亮使用的语言，那就分别用三个 反引号 (`) 包裹起来，并在第一组反引号后加上语言名称：

	```java
    public void Seita{
        System.out.println("My java lang is poor, So I can just use the IO command");
    }
    ```
**关于列表**

分为有序列表和无序列表。
有序列表每行前是数字+英文句点的形式，但数字是随机的，并不影响显示效果；
无序列表每行前是 (*) 或 (+) 或 (-)，皆可。

	1. 第一行
    2. 第二个
    3. 火车尾
    
    * 没有顺序的一
    * 没有顺序的二
    * 没有顺序的三
    
**关于字体**

主要是 加粗 和 斜体。
加粗可以是将文字包裹在两组 ```**``` 内，当然第二组也不是必须的。
斜体可以是将蚊子包裹在两组 ```__``` 内，注意是两个下划线一组。

完整 Markdown 教程推荐阅读 [Markdown 语法说明](http://wowubuntu.com/markdown/)
