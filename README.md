﻿# SE-EX1-WordGraph
Show a sentence as a graph and do some operations on it.

### Function 1 : 生成并展示有向图

* 选择文件载入
* 遍历文本建立有向图
* 调用Graphviz生成图片并展示在图片显示区域
* 可以将图片保存到本地其他位置 
---

### Function2 : 查询桥接词

* 输入两个单词，查询原文中两个单词相连的所有中间单词
* 同时图上高亮出这样的三元组结构
---

### Function3 : 根据桥接词生成新文本

* 输入文本，在相邻单词间随机插入桥接词并输出新文本
---

### Function4 : 计算两个单词最短路径

* 选择两个单词
* 计算两个单词在原文中的最短路径
* 若有多条则以不同颜色高亮，也可以选择只高亮某一条
---

### Function5 : 随机游走

##### 风格1 : 自动游走

* 点击开始随机游走后开始自动游走，每1秒走一步
* 经过的路径会在图上动态显示
* 点击停止则会停止随机游走
* 经过重复的边后会自动停止

##### 风格2 : 手动游走

* 点击开始随机游走后，点一次走一步
* 经过的路径会在图上动态显示
* 经过重复的边后会自动停止
---
