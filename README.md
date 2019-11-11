# pianke
模拟片刻网布局

小记：想打开看看片刻网，发现片刻网关闭了，最初学习HTML和css的布局就是从「片刻」
开始的，他的布局结构清晰，而且便于想要学习前端页面的学者参考代码，理解起来也很容易。
自己写的并不好，但是还是把自己之前的代码拿出来供大家参考和交流学习，追忆「片刻」。



我会从布局结构为大家介绍

### 01header
导航栏

- 整体还是使用盒模型的布局方式
- 整体对 class为`nav_body`的布局`width: 100%;`使用定位`position: fixed; left: 0; top: 0px; z-index: 1000;`
- class为`navheight: 100px; width: 1200px; margin: 0 auto;`
- 对class为`nav`里的每个小内容使用`float`进行浮动
- 对「登录注册」按钮使用`transition: all 0.5s;`有hover动画效果
- 当鼠标滚轮下滑一定位置导航栏隐藏，上滑又会出现，使用`scrollTop`
————————————————


![header](https://github.com/AliceRachel/pianke/blob/master/upload/01header.png)


### 02content
内容第一部分

- 布局仍使用float浮动和定位的方式
- 鼠标悬上会有放大效果
- 滑动显示的文本样式可以参考使用
- 多行文本溢出用…省略号形式展示`text-overflow: ellipsis;`

![02content](https://github.com/AliceRachel/pianke/blob/master/upload/02content.png)

### 03content
内容第二部分

![03content](https://github.com/AliceRachel/pianke/blob/master/upload/03read.png)

### 04content
内容第三部分
![04content](https://github.com/AliceRachel/pianke/blob/master/upload/04ting.png)

### 05content
内容第四部分
![05content](https://github.com/AliceRachel/pianke/blob/master/upload/05hot.png)

### 06footer
页脚部分
![06footer](https://github.com/AliceRachel/pianke/blob/master/upload/06footer.png)

