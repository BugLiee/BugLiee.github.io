常用语法

引用文本使用大于号(>)

1. 实现缩进
两种方案

手动输入空格 （&nbsp；）。注意！此时的分号为英文分号，但是不推荐使用此方法，太麻烦！

使用全角空格(切换快捷键shift+空格)。即：在全角输入状态下直接使用空格键就ok了

2. 实现换行
两种方案

两个回车即可

使用< br >

3. 字体大小、颜色、类型、加粗、倾斜<br>
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=red>我是红色</font>
<font color=#008000>我是绿色</font>
<font color=Blue>我是蓝色</font>
<font size=5>我是尺寸</font>
<font face="黑体" color=green size=5>我是黑体，绿色，尺寸为5</font>


** 内容 ** 　(左二* 右二*  与内容之间没有空格)   加粗

*内容* 　　 (左一* 右一*  与内容之间没有空格)   斜体

4. 代码块
(```)

int a = 0 ;

System.out.println(“Hello”) ;

(```)

注意！为了防止转译，前后三个反引号处加了小括号，实际是没有的。

5. 超链接
[超链接名] (超链接地址 “超链接title”)

[百度] (http://baidu.com) （注意！[]与()之间没有空格）

6. 分割线
三个或者三个以上的 - 或者 * 都可以。
7. 标题
通过在文字前面添加#即可


# 这是一级标题

## 这是二级标题

### 这是三级标题

---
layout: post
title: Kotlin MVVM酷欧天气完整解析
categories: Kotlin
description: 以酷欧天气为基石分析Kotlin的MVVM实现
keywords: Kotlin, MVVM
---
