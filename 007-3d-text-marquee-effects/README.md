# 3d文字跑马灯效果

> 原作：https://segmentfault.com/a/1190000014663038

效果:

![炫酷](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/007-3d-text-marquee-effects.gif)


实现思路：

1. 首先创建一个容器,放置两个横向排列的,文字相同的元素
2. 通过颜色来使两个容器颜色有层次感`first-child`和`last-child`可以通过这两个来处理
3. 利用transform中的`perspective`、`rotateY`、`perspective`来产生3D效果
4. 通过`keyframes`、`animation`改变字体的运动，通过`animation-delay`来达到字体链接的效果

学习到的
1. 跑马灯需要层次感与文字进场的效果结合才能做出3d效果
2. 了解transform的`perspective`视距的使用






