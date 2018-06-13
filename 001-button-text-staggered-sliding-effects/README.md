# 文字上下交错效果

> 原文：https://segmentfault.com/a/1190000014534572

效果：


学习思路
1. 创建按钮,为按钮添加效果
2. 使用伪类创建出相同的元素
3. 相同的元素可以通过content:attr()来获取
4. 通过transition来行程控制动画的时间
5. :hover伪类来确认状态形成视差


未接触的知识:
- content中的attr()
[MDN](https://developer.mozilla.org/zh-CN/docs/Web/CSS/content)
>attr(X)
将元素的X属性以字符串形式返回。如果该元素没有 X 属性，则返回一个空字符串。区分大小写的属性返回值依赖文挡的语言设定。



遇到的问题：
- 使用使用translateY(-100%)不起作用
 [stackoverflow类似问题](https://stackoverflow.com/questions/14883250/css-transform-doesnt-work-on-inline-elements)
> an element whose layout is governed by the CSS box model which is either a block-level or atomic inline-level element, or whose ‘display’ property computes to ‘table-row’, ‘table-row-group’, ‘table-header-group’, ‘table-footer-group’, ‘table-cell’, or ‘table-caption’ [CSS21]

w3规范中：可变元素需要是block或者inline-block，或者是上述所标识的