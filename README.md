# NirZhihuDaily2.0
根据 https://github.com/izzyleung/ZhihuDailyPurify/wiki/知乎日报-API-分析 提供的API制作的知乎日报iOS客户端

### 效果图如下

![effect1](https://github.com/zpz1237/NirZhihuDaily2.0/blob/master/effectDemo1.gif)

![effect2](https://github.com/zpz1237/NirZhihuDaily2.0/blob/master/effectDemo2.gif)

![effect3](https://github.com/zpz1237/NirZhihuDaily2.0/blob/master/effectDemo3.gif)


实现了知乎日报的大部分功能，未实现用户登录，个性化主题日报以及查看新闻评论及点赞等非主要功能

注释相当详细，十分便于理解

### 要求

* Xcode 7.1
* iOS 9.1

### 待修改的bug

* 首页上方循环播放图有小几率 `frame` 显示不正确
* 由于网络原因获取数据失败的话，会输出错误信息，不能显示网络数据，重新加载即可
* 文章内容下拉加载上一篇之后，在 View Hierachy 中会多出一层空白 `view`
* 删除冗余代码

### 待添加的功能

* 首页下拉刷新功能
* WebViewController内点击加载其他Web页面
* WebViewController内点击打开知乎客户端
