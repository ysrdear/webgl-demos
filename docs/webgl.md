<!--
 * @Author: your name
 * @Date: 2020-09-21 20:08:59
 * @LastEditTime: 2020-09-21 21:19:50
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \webgl-demos\docs\webgl.md
-->

### 初始化

```
var canvas = document.getElementById('canvas');

var gl = canvas.getContext('experimental-webgl');

```

### 设置画布背景

```
gl.clearColor(0.0, 1.0, 0.0,1.0);   //rgba

gl.clear(gl.COLOR_BUFFER_BIT);

```

### 顶点着色器

描述顶点的特性如位置颜色等等

### 片元着色器

对逐个片元进行颜色处理过程的程序

`片元可以理解为像素，图像的每一个单元`

着色器程序，它类似于`C`语言，有一个`main`入口函数，是强类型的语言，变量的赋值必须类型一致，浮点说必须加小数点等等，叫做`GLSL ES`

### attribute

### uniform

### 七种基础图形

1. gl.POINTS
2. gl.LINES
3. gl.LINE.STRIP
4. gl.LINE.LOOP
5. gl.TRIANGLES
6. gl.TRIANGLE_STRIP
7. gl.TRIANGLE_LOOP

###

`gl.TRIANGLE_STRIP` 传值的顺序：奇数个为逆时针，偶数个为顺时针
