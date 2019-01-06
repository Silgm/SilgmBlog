---
title: Hello World
date: 2019-01-02 21:12:36
tags: [Hexo测试]
category: 
    - [Hexo] 
---


博客初次建立，可喜可贺😂
还有...
新年快乐


## 以下是测试部分
 
### 图片显示测试
{% asset_img test.jpg test %}
### 内置asset folder超链接
{% asset_link test.jpg test图片超链接 %}

### 使用markdown语法显示图片
![](test.jpg)
 
### tab形式代码块, 不带高亮
    #include <stdio.h>
    int main(int argc, char *argv[])
    {
        printf("Hello, World");
        return 0;
    }

### 内置方式代码块, 带高亮
```C
#include <stdio.h>
int main(int argc, char *argv[])
{
    printf("Hello, World");
    return 0;
}
```
