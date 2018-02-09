### 什么是flex布局
- 布局的传统解决方案，基于盒状模型，依赖 display 属性 + position属性 + float属性。它对于那些特殊布局非常不方便，比如，垂直居中就不容易实现。
- 2009年，W3C 提出了一种新的方案----Flex 布局，可以简便、完整、响应式地实现各种页面布局。目前，它已经得到了所有浏览器的支持，这意味着，现在就能很安全地使用这项功能。
- 语法特别简单，可以轻松实现任何布局哦~~特别是在移动端h5对flex的支持很好的情况下，h5可以很方便编写

### 浏览器支持情况
![20](https://raw.githubusercontent.com/wiki/sodyxiezhen/practice3_less/20.png)

### 文档参考资料
[语法篇](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)<br />
[实例篇](http://www.ruanyifeng.com/blog/2015/07/flex-examples.html)<br />

### 基本语法
0. 父容器指定flex，包裹子项目就行啦
![21](https://raw.githubusercontent.com/wiki/sodyxiezhen/practice3_less/21.png)
1. flex-direction属性，指定子元素的排列方式，默认是水平排列
2. flex-wrap属性，指定子元素的换行方式，默认是不换行
3. justify-content，指定子元素在水平方向的对齐方式，指定center可轻松实现水平对齐
4. align-items,指定子元素在垂直方向的对齐方式，指定center可轻松实现垂直对齐
![22](https://raw.githubusercontent.com/wiki/sodyxiezhen/practice3_less/22.png)

### 今日练习
使用学习的四个元素，完成垂直对齐demo