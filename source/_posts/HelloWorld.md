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
 
### 1.图片显示测试
{% asset_img test.jpg test %}
### 2.内置asset folder超链接
{% asset_link test.jpg test图片超链接 %}

### 3.使用markdown语法显示图片
![](test.jpg)
 
### 4.tab形式代码块, 不带高亮
    #include <stdio.h>
    int main(int argc, char *argv[])
    {
        printf("Hello, World");
        return 0;
    }

### 5.内置方式代码块, 带高亮
```C
#include <stdio.h>
int main(int argc, char *argv[])
{
    printf("Hello, World");
    return 0;
}
```

### 6.外部url链接
<!-- Http必须加 -->
#### Google
<https://www.google.com>
#### Baidu
<https://www.baidu.com>

### 7.外链测试
#### 网易云
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="100%" height=100 src="//music.163.com/outchain/player?type=2&id=29490357&auto=1&height=66"></iframe>

#### Youtube
如www.youtube.com/watch?v=Rub-JsjMhWY&t=20s
`Rub-JsjMhWY`就是video_id
{% youtube Rub-JsjMhWY%}

#### Bilibili
<iframe src="//player.bilibili.com/player.html?aid=33385105&cid=58437850&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" marginheight="0" width="100%" height=600 allowfullscreen="true"> </iframe>

#### Soundcloud
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/600875265&color=%2376b1cb&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>

### 8.插件测试
aplayer插件测试
{% aplayer "test" "test" "test_music_loop.mp3"%}

html5内置播放器测试
{% html5video %} 
{% asset_path Sticker.mp4 %} 
{% endhtml5video %}

{% html5video '100%' '250px' 'video/mp4' %} 
{% asset_path Sticker.mp4 %} 
{% endhtml5video %}
