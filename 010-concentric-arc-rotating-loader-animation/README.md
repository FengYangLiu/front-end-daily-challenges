# 同心圆效果

> 原作：https://segmentfault.com/a/1190000014682999

效果:

![同心圆](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/010-concentric-arc-rotating-loader-animation.gif)


实现思路：

1. 首先创建一个元素，然后利用after 和 before 这三个的border绘制出3个圆
2. 通过装饰然后使用动画进行旋转,利用`animation-duration` 按比例延时,给人一种倒回的感觉


学习到的
1. `animation-direction:alternate;` 动画应该轮流反向播放。






