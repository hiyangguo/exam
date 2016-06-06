> 下列题目中的所有选择题均为不定项选择题！！！

1.现有代码如下:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <style>
        * {padding: 0;margin: 0;}
        button {float: left;}
    </style>
</head>
<body>
    <button>按钮A</button>&nbsp;
    <button>按钮B</button>&nbsp;
    <button>按钮C</button>&nbsp;
    <button>按钮D</button>&nbsp;
    <span>Hypers</span>
</body>
</html>
```

该段代码的表现形式是下列那种情况?

- A.![图片](http://7xpn4q.com1.z0.glb.clouddn.com/1-A.png)
- B.![图片](http://7xpn4q.com1.z0.glb.clouddn.com/1-B.png)
- C.![图片](http://7xpn4q.com1.z0.glb.clouddn.com/1-C.png)
- D.![图片](http://7xpn4q.com1.z0.glb.clouddn.com/1-D.png)

[答案](http://runjs.cn/code/g3zwsjky)

2.对元素设置`style="position: relative;left: 100px"`具有以下哪种效果?

- A.元素向左移动100px，原有空间不再保留
- B.元素向左移动100px，原有空间留下一片空白
- C.元素相对父级元素向左移动10px，其原有空间不再保留
- D.元素不移动
- E.以上答案均不正确

[答案](http://runjs.cn/code/lmalvdsr)

3.现有如下css代码

```css
.triangle {
    border-style: dashed solid dashed dashed;
    border-color: transparent #1b9451 transparent transparent;
    border-width: 20px;
}
```

其表现结果应为图中的哪个三角形?

![预览图](http://7xpn4q.com1.z0.glb.clouddn.com/3.png)

- A.三角形A
- B.三角形B
- C.三角形C
- D.三角形D

[答案](http://runjs.cn/code/rteybhtt)

4.下列css选择器中，支持IE8（属于css2.1规范）的是：

- A. :first-child,:last-child,:hover,:after,:before
- B. :link,article[id|="hypers"],:lang(),div + div
- C. :active,:focus,:nth-child(3),[attr~="val"]
- D. #foo,li span:first-child,div > a,header[class^="hypers"]
- E. 没有正确答案

[答案](https://github.com/hiyangguo/exam/issues/1)

5.以下css属性中会被子元素继承的是:

- A.color,cursor,font-weight,font-family
- B.line-height,list-style-image,text-align,white-space
- C.word-spacing,visibility,list-style-type,color
- D.font-style,text-indent,white-space,cursor
- E.以上答案都正确

[答案](https://github.com/hiyangguo/exam/issues/2)

6.关于css优先级(Specificity)下列描述正确的是:

- A.浏览器通过优先级来判断哪一些属性值与一个元素最为相关，从而在该元素上应用这些属性值。优先级基于由各种选择器组成的匹配规则
- B.优先级由低到高依次为: 元素(类型)选择器 < 类选择器,属性选择器,伪类选择器 < ID选择器
- C.当在一个样式声明上使用 !important 规则时，该样式声明会覆盖CSS中任何其他的声明。
- D.优先级就是一个 应用于指定的CSS声明的 权重，它由匹配的选择器中的 每一种选择器类型的 数值 决定。

[答案](https://github.com/hiyangguo/exam/issues/3)

7.下列描述正确的是

- A.css属性font-style用于设置字体的粗细
- B.css只能通过<link>引入
- C.`visibility: hidden;`的效果和`display:none`的效果完全相同
- D.`z-index`对所有元素都有效
- E.在不涉及样式情况下,页面元素的优先显示与标签选用无关。

[答案](https://github.com/hiyangguo/exam/issues/4)

8.伪类和伪元素是什么？它们有什么区别?(此题可以深入的问一下关于伪类，伪元素的实际应用。比如clearfix,iconfont等)



9.请列举一下你所了解的css/less/sass框架(库)。PS:名称即可



10.用`less`或`Sass`语法实现一个按钮样式**mixin**。（选作）

编译后的代码参考如下
```css
.hypers-btn-default{
   	font-size: 14px;
	padding: 7px 18px;
    border-radius:5px;
}
.hypers-btn-primary{
   font-size: 14px;
   padding: 7px 18px;
   border-radius:5px;

   background: #1b9451;
   border-color: #1b9451;
   color: #fff;
}
```

11.关于`position`属性，下列描述错误的是:

- A.`postion`属性定义了一个元素在页面布局中的位置以及对周围元素的影响。该属性共有5个值，分别为:`absolute`、`relative`、`fixed`、`static`和`inherit`
- B.`relative`为`position`属性的默认值
- C.`absolute `元素将会脱离正常的文档流,并且会相对于父级`relative`元素定位
- D.`relatove`元素遵循正常的文档流,且支持 top,bottom,left,right 等属性
- E.`fixed` 元素定位与它的父元素无任何关系，它永远是相对最外层的 window，因为屏幕的滚动而消失
- F.`z-index`属性只对所有元素有效。

[答案](https://github.com/hiyangguo/exam/issues/5)

12.关于`BFC`(Block Formatting Context)的描述正确的是:

- A.`BFC`区域具有块与块之间相互独立，内部元素互不影响的特点
- B.`BFC`区域内部元素会在垂直方向按顺序排列,垂直顺序排列的元素的距离取决于margin的大小,相邻的两个元素的`margin`不会重叠。
- C.`BFC`的元素不会和`float`的元素重叠
- D.`float`属性为非`none`时（如`left`,`right`）,`position`属性为`fixed`或者`absolute`时

[答案](https://github.com/hiyangguo/exam/issues/6)


13.一部分问答参考:
1) 简单说说你所知道的前端自动化构建工具
2) 你如何看待前端模块化开发
3) 什么是cssHack？说说你知道的cssHack
4) 使用rgba()和opacity的透明效果有什么不同？
5) 谈谈使用sass/less这些动态样式语言的利弊
6) 什么是css reset 谈谈使用css reset的好处




