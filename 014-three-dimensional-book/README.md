# 立体图书

> 原作：https://segmentfault.com/a/1190000014751037

效果:

![立体图书](https://github.com/FengYangLiu/front-end-daily-challenges/blob/master/images/014-three-dimensional-book.gif)


实现思路：

1. 首先创建一个书本元素,一个span用来装饰字体
2. 通过书的两个伪类来打起立体书的骨架，使用`transform:skew()`
3. 立体书的层次感通过`box-shadow`与`fillter:brightness()`来营造
4. 添加动画效果


学习到：
1. 了解`transform:skew()` 用法这个是歪斜的函数
2. 学习`fillter:brightness()`这个是控制光线的，默认值为1,1以内会变暗，0变黑，1以上光线增强








