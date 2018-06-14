# 嵌套旋转矩形loading

> 原作：https://segmentfault.com/a/1190000014553745

效果：

![好晕](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/002-rectangular-rotating-loader-animation)

实现思路：

1. 创建3个宽度递减的嵌矩形
2. 在嵌套矩阵上添加不同色块，产生视觉效果
3. 使用帧动画 animate 来进行旋转
4. 通过每个矩形不同持续时间来造成嵌套旋转的效果

学习:
1. margin的百分比是通过父级的宽度定义的
2. position:absolute;这个是实际不是只有对应relative的,实际上也对应最近的absolute为参考物，旋转的装饰就是证明
