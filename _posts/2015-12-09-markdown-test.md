---
layout: post
category : blog
tagline: "Supporting tagline"
tags : [intro, markdown]
---
{% include JB/setup %}

markdown test
---

# 文本格式

1. **加粗**
2. *斜体*
3. ***斜体加粗***
4. 有序列表  

---
* 无序列表
* 列表2

>引用quote

行内代码格式`Ctrl + V`，是粘贴快捷键。


# 代码
```c
#include <stdio.h>
void main(void)
{
	printf("Hello World");
}
```


# 表格

|编号 | 内容 | 备注|
|----: | :---- | ----|
|1| 我的电脑 | 设备管理|
|2| 网上邻居 | 网络连接属性|

# 图片

![图片](http://jekyllcn.com/img/footer-logo.png)

# 链接

[链接点这里](http://www.baidu.com)
