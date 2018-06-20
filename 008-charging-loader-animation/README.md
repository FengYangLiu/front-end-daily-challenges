# 充电loader

> 原作：https://segmentfault.com/a/1190000014669547

效果:

![充电~](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/008-charging-loader-animation.gif)


实现思路：

1. 创建一个电池容器
2. 创建电量适应background-image
3. 通过`keyframes` 来修改 `background-size`

学习到的
1. 稍微了解了steps属性,帧数 每个里面有几帧;
2. `currentColor` 这个属性是继承使用

遇到的问题：
1. steps不能和linear一起使用

参考：
1. [steps](https://developer.mozilla.org/en-US/docs/Web/CSS/single-transition-timing-function#Timing_functions)







