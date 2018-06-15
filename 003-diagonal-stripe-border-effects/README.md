# 斜条纹动态效果（发廊的广告牌）

> 原作：https://segmentfault.com/a/1190000014576519

![发廊](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/003-diagonal-stripe-border-effects.gif)

实现思路：

1. 创建嵌套关系的盒子
2. 给父级一个渐变背景通过`linear-gradient`和`background-repeat`来铺满整个背景
2. 套在里面的内容框,通过父级盒子的padding与box-sizing共同作用
3. 通过`@keyframes`与`animation` 来使background-position移动

遇到的问题:
1. 修改过部分参数，动画的持续时间与尺寸、父级的宽度不能太短,否则不协调
2. 尝试用boder-image但是不行




