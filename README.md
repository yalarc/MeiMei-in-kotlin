# MeiMei-in-kotlin
第一个kotlin 项目，在经过一个月语法学习后，用kotlin语言实践了一下
###试玩
https://www.pgyer.com/VxrO
![](MeiMei.png)

### 项目介绍
本软件是一个看图片的APP,图片均来自正规网络（如有侵权，请立马告诉本人，本人邮箱 yalarcs@gmail.com,定立刻删除），本app 仅做学习交流使用，勿做商用。

![](MeiMei.gif)

### 用到的知识点
  
- kotlin 语言
    - 数据类
    - 伴生对象
    - 单例
    - 扩展
    - 闭包
    - ...
- anko
- jsoup 爬取网页数据的库
- Material Design 风格
- Recyclerview 瀑布流
- CardView
- Glide 加载图片
- BaseQuickAdapter 以前自己搞的一个adapter,方便快速开发
- DrawerLayout
- NavigationView
- Toolbar
- 下拉刷新,上拉加载
- fragment懒加载

大概就是上面这些了

### 构建UI风格

我是采用的侧滑风格的app,中间的数据全部采用fragment来填充的,fragment只有在显示后才加载数据,不会浪费过多流量.

素材取自阿里矢量图标库

