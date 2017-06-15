# 本项目是一个可以浏览以及预定pizza的网站，基于网页开发。<br>
## 网站操作指南<br>
1. 页面滚动时，背景pizza图片跟随滚动。
2. 点击Menu按钮，页面跳转到Our Pizzas!
3. 点击Our Ingredients按钮，页面跳转到Ingredients。
4. 点击Locations按钮，页面跳转到Locations.
5. 点击Contact Us按钮，弹出提示弹窗。
6. 点击Pick a Pizza Now!按钮，页面跳转到Our Pizzas!
7. 向左滑动滑块，选择小号pizza，向中间滑动，选择中号pizza，向右滑动滑块，选择大号pizza。
## 优化概述<br>
1. 压缩图片
2. 把小型的js和css文件内联进html文档里。
3. 在main.js中，修改`updatePosition()`函数，把`phase`定义在`for`循环外面，避免了强制同步布局。
4. 修改index.html的Google字体加载方式，添加`async`改为异步加载。
