> 下列题目均为不定项选择题！！！

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

6.关于css优先级(Specificity)下列描述有误的是:

- A.浏览器通过优先级来判断哪一些属性值与一个元素最为相关，从而在该元素上应用这些属性值。优先级基于 由各种选择器组成的匹配规则
- B.优先级由低到高依次为: 元素(类型)选择器 < 类选择器,属性选择器,伪类选择器 < ID选择器
- C.当在一个样式声明上使用 !important 规则时，该样式声明会覆盖CSS中任何其他的声明。
- D.以上均为正确答案

8.下列描述正确的是

- A.css属性font-style用于设置字体的粗细
- B.css只能通过<link>引入
- C.`visibility: hidden;`的效果和`display:none`的效果完全相同
- D.`z-index`对所有元素都有效
- E.在不涉及样式情况下,页面元素的优先显示与标签选用无关。