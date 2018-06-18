# 钻石闪耀效果

> 原作：https://segmentfault.com/a/1190000014652116

效果:
![真的太有趣了]()


实现思路：

1. 首先创建一个容器，容器内包裹着四个元素
2. 钻石闪耀的效果是通过元素的border来实现的
3. 通过grid布局形成田字布局然后旋转45度把第一个上面的一半配色改成透明
4. 通过keyframes来产生动画是边框的颜色不停的变换


学习到的：
1. :root 这个 CSS 伪类匹配文档树的根元素。对于 HTML 来说，:root 表示 <html> 元素，除了优先级更高之外，与 html 选择器相同。和变量一起使用绝配

2. 认识到了grid布局,`grid-template-columns`这个属性必须是网格布局的才能使用 [grid-template-columns MDN](https://developer.mozilla.org/zh-CN/docs/Web/CSS/grid-template-columns)




