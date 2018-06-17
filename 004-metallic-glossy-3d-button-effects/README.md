# 金属光泽的3d按钮

> 原作：https://segmentfault.com/a/1190000014599280

![金属质感反光按钮](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/004-metallic-glossy-3d-button-effects.gif)

实现思路：

1. 创建一个按钮
2. 创建2D效果,通过box-shadow与text-shadow来处理,背景则是由渐变来处理
2. 通过伪元素创建一个光泽效果
3. 通过`:hover`与`animation`来改变box-shadow与text-shadow;

学习：
1. 可以通过2em来形成半圆,em本身就是依照父级，这里border-radius按照高度来计算的em，和百分比一样大于一半后就会保持一半不会有变化了。 

2. css中的变量由`--`和变量名来连接变量,使用方式`var(--name)`;
3. 计算属性`calc`这个变量是可以调用属性进行简单的运算的

遇到的问题:
1. 变量非常好用,但是支持性不高




