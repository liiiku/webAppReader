# webAppReader
移动端webApp阅读器

效果展示：

![Alt text](https://github.com/liiiku/webAppReader/blob/master/imgs/1.png)
![Alt text](https://github.com/liiiku/webAppReader/blob/master/imgs/2.png)
![Alt text](https://github.com/liiiku/webAppReader/blob/master/imgs/3.png)

项目描述：

开发一个移动端webApp阅读器，项目源码可在github上查看（项目名：webAppReader），效果可扫二维码在手机上查看，由于专门做的移动效果，所以在pc端最好通过开发者工具查看
1、轻触屏幕中心换出顶部和底部菜单，底部菜单中，字号和背景的图标采用css3的圆角实现；字体、目录、白天夜间的切换三者的图标采用base64格式的图片
2、由于需要记住用户的改变操作，采用html5的浏览器技术localstroage实现记录
3、整个项目的dom操作，采用和jquery类似地用于移动端的js库zepto.js
4、项目中的异步操作除了用传统的callback实现外，尝试用es6的promise改写实现
5、采用json模拟后台数据，通过ajax请求后渲染到页面上
