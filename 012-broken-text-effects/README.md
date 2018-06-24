# 文字切割效果

> 原作：https://segmentfault.com/a/1190000014719591

效果:

![切割](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/012-broken-text-effects.gif)


实现思路：

1. 首先创建一个元素，使用`data-*` 与元素内容一样
2. 通过伪类元素的`attr()`来获取`data`中的文字，然后伪类重叠在元素上
3. 通过`clip-path:polygon()`来切割两个伪类添加动画效果

学习到：
1. `clip-path:polygon()`里面的数据为坐标:按照顺时针赋值坐标点








