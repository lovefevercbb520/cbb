---
title: markdown语法
date: 2018-10-25 09:44:44
tags:
---
# 标题
# 一级标题
## 二级标题
.....
###### 六级标题

# 超链接
[点我](http://www.baidu.com)跳转到百度

[连接名字](链接地址)
# 图片

![图片名字](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1540442768781&di=fed76e3427a4fc19c16114ba1b3906dc&imgtype=jpg&src=http%3A%2F%2Fimg1.imgtn.bdimg.com%2Fit%2Fu%3D2051834251%2C4262878379%26fm%3D214%26gp%3D0.jpg)

# 图片链接
[![图片名称](图片地址)](超链接)]


# 文本修饰

*文本倾斜*
**文本加粗**
***加粗倾斜效果***
~~删除线~~


# 分割线
三个或者三个以上的-或者*
---
***

# 列表

## 有序列表
1.c
2.cb
3.cbb

## 无序列表
以一个- + *开头的
- 列表1
- 列表2
- 列表3


# 表格

姓名|排行|特长
-|-|-
刘德华|老大|电影
周杰伦|2哥|唱歌


# 代码块

```javascript
while (alive){
    code();eat();sleep();
}
```

```css
body{
    color:red;
    font-size:15px;
}
```

```bash
# 初始化博客项目
hexo init biog
# 切换到博客路径
cd biog
# 安装依赖包
npm install
# 启动hexo服务
hexo s
```