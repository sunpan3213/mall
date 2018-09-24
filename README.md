# Mall


## 实现以下需求：
1，实现了多级商品的展示；

2，右侧首字母快速选择滑动；

3，左边一级分类联动二三级商品；

4，在尽量减少布局嵌套的情况下实现多种视图。

## 技术点：
1，图片加载用的Glide框架

2，自定义右侧首字母快速选择控件

3，recyclerview展示列表。当滚动时，禁止加载图片；停止滚动时，再进行加载图片

4，MVP+RxJava+Retrofit实现网络请求和整体框架（考虑到本项目就一个界面，就用了MVC加模拟数据解决）。在开发的过程中使用过第三方的商城类api，发现数据结构不能满足，就抛弃这种做法

# 关联   源码及App
[源码地址](https://github.com/sunpan3213/Mall/)

[App地址](https://github.com/sunpan3213/Mall/tree/master/apk)
