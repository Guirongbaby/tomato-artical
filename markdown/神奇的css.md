温馨前言：`我觉得CSS就像女生化妆品，像魔术师 的魔法棒，像小学生手里的蜡笔，HTML想设置什么颜色，都有CSS说了算！有时候不禁觉得世界很神奇，就像中国的老话：“一物降一物”， 那么对待寒冷的冬天，你是如何温暖自己的 呢？`

### 1. CSS的定义

#### 1.1 什么是CSS？
   CSS 指层叠样式表(Cascading Style Sheets)
   
   CSS主要用于设置HTML页面中的文本内容（字体、大小、对齐方式等）、图片的外形（宽、高、边框样式、边距等）以及版面的布局等外观显示样式
   
   
   --- 
   
   
#### 1.2 HTML 和 CSS 的关系

   
   HTML:页面结构
   
   CSS： 页面样式表现
   
   JavaScript：交互行为
   
   
![](https://user-gold-cdn.xitu.io/2019/12/8/16ee35ff2118936f?w=758&h=283&f=png&s=22591)
   
   ---
   
#### 1.3 行内样式 style 属性
   
   
```
 <span style="color: blue;"></span>
```
   
   ---
   
   
#### 1.4 内嵌样式（内联样式）
   
   在head标签中添加 style 标签
   
   
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <style>
  p {color:red;}
  </style>
</head>
<body>
<p>这是一个段落标签</p>
</body>
</html>

```

页面效果如下：

![](https://user-gold-cdn.xitu.io/2019/12/8/16ee367af1a88b3b?w=393&h=100&f=png&s=1772)   

   ---
   
### 2. CSS 语法

选择符 {

属性声明: 属性值; 

属性声明: 属性值;

}


![](https://user-gold-cdn.xitu.io/2019/12/8/16ee36e3b4f6c5d3?w=658&h=289&f=png&s=33364)

---


### 3.4 CSS简单的属性

* width：设置宽度，单位px像素

* height：高度

* color：前景色，也就是文字的颜色

* background-color：背景色

* font-size:字体的大小

---


### 3.5 CSS的注释

CSS的注释格式：` /* 注释内容  */`

可以同时注释多行语句比如：

```

/*
注释内容
多行注释
多行注释
*/
```


`好啦，今天的内容就到这里了，对于CSS，你是不是有了基本的认识了呢？`

`谢谢阅读`

下节内容：`CSS的选择器`


   

   