---
title: Geogebra 学习笔记 (1)
author: jiap
date: 2021-04-21 02:43:44
categories: [Skills, Geogebra]
tags: [Geogebra, Mathematics, Physics]
math: True
---

本文为 Geogebra 学习笔记，主要涉及：(1) 入门介绍；(2) 静态作图的使用技巧；(3) 动点动态图制作；(4) 滑动条的使用；(5) 进阶应用。

> 本文使用的是 Geogebra Class 5.0，系统为 macOSX Big Sur。

## 0. Geogebra 页面

打开 Geogebra 软件 (下文简称 ggb)，主页面如图 1 所示。

<img src='/assets/img/2021-04-21-skill-geogebra-learning-1/layout.png' style='zoom:40%; margin: 0 0; display: block;'/>

1. 语言设置：在选项 - 语言 中选择中文；  
2. 页面布局设置：在视图-布局 中选择合适的页面布局，或 选中某区域直接进行拖拽到合适位置。  

### 0.1 功能区

将光标悬停在功能区，会有功能提示。当右键时，会出现多功能，例如右击 【圆】，会出现几种画圆、圆弧的方法，如下图所示。

<img src='/assets/img/2021-04-21-skill-geogebra-learning-1/unfold.png' style='zoom:40%; margin: 0 0; display: block;'/>

### 0.2 代数区

当在功能区中选 点，在绘图区生成一个点，生成点的坐标会在代数区显示，如图所示。

<img src='/assets/img/2021-04-21-skill-geogebra-learning-1/algebra_area.png' style='zoom:40%; margin: 0 0; display: block;'/>

1. 点击 功能区 第一个按钮，找到 移动，再在绘图区找到点，可直接移动；  
2. 如果直线和线段重合，无法选中某对象时，可在代数区
里选对应的点；  
3. 在绘图区右键该点，可设置该点的属性，包括颜色，形状等。

### 0.3 绘图区

绘图区有若干功能：显示/隐藏坐标轴，显示/隐藏网格，默认试图和吸附模式。

用 ggb 绘制的图形均在绘图区展示。

> 在 Geogebra Class 6.0 中，绘图区可显示直角坐标轴、极坐标轴。

## 1. Geogebra 制作原则

ggb 的制作原则：**先做什么，后做什么**。

以作固定点的垂线为例：

1. 选择点工具，绘制一个点 $A$；  
2. 选择直线工具，在绘图区绘制一条直线 $f$；  
3. 选择垂线工具，会有提示“选定点与要垂直的线”，选  $A$ 以及 $f$，此时就完成了垂线的绘制。 

<img src='/assets/img/2021-04-21-skill-geogebra-learning-1/perpendicular.png' style='zoom:40%; margin: 0 0; display: block;'/>

## 2. Geogebra 小工具制作

在 ggb 中可以制作一些小工具，方便使用，以制作三角形的内接圆为例：

1. 选择多边形工具，制作一个三角形 $ABC$；  
2. 由于内接圆为角平分线交点，在 垂线 工具下拉菜单中选择角平分线功能，会有提示“选择三个点或者两条线”；  

> 注：这里点选 $A$、$B$、$C$ 三个点；若点选 $AB$、$BC$ 两条直线的话，会出现两条直线。

3. 绘制两条角平分线后，点选 描点 工具，在下拉菜单中找到 交点 功能，标记角平分线的交点 $D$。  
4. 点选 垂线 工具，过 $D$ 作 $AB$ 垂线，再选择 交点 工具，标记为 $E$。  
5. 点选 圆 工具，选择 “圆心与一点”，选择 $D$ 和 $E$，这样内切圆就绘制完成了。

<img src='/assets/img/2021-04-21-skill-geogebra-learning-1/methods.png' style='zoom:40%; margin: 0 0; display: block;'/>

选择 Geogebra 的 工具 - 新建工具，对话框分成三部分，需要设置的为：输出对象 和 输入对象，在输出对象中选择 同心圆 e，在输入对象中选择三点$A$、$B$、$C$，再确定小工具名称即可 (可自定义)。

> 生成的文件为 `.ggt` 格式。

<img src='/assets/img/2021-04-21-skill-geogebra-learning-1/tool.png' style='zoom:40%; margin: 0 0; display: block;'/>

---
1. [最实用的GGB（geogebra）入门课程](https://www.bilibili.com/video/BV11Z4y1W77e)