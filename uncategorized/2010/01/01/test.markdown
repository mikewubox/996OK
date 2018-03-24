---
title: Hello World
date: 2010-01-01 00:00:00
permalink: test
categories:
tags: [hexo,music,video]
description:
image: https://yixiuer.oss-cn-shanghai.aliyuncs.com/Picture/hello-world.jpg
---
<p class="description">for testing something new only</p>

<!-- more -->

## playlist

{% aplayerlist %}
{
    "autoplay": false,
    "showlrc": 3,
    "mutex": true,
    "music": [
        {
            "title": "Paradise",
            "author": "Coldplay",
            "url": "https://yixiuer.oss-cn-shanghai.aliyuncs.com/music/Coldplay%20-%20Paradise%20%281%29.mp3",
            "pic": "https://yixiuer.oss-cn-shanghai.aliyuncs.com/music-cover/coldplay-paradise.jpg",
            "lrc": "https://reuixiy.github.io/uploads/lyrics/coldplay-paradise.lrc"
        },
        {
            "title": "Fix You",
            "author": "Coldplay",
            "url": "https://yixiuer.oss-cn-shanghai.aliyuncs.com/music/Coldplay%20-%20Fix%20You.mp3",
            "pic": "https://yixiuer.oss-cn-shanghai.aliyuncs.com/music-cover/coldplay-fix-you.png",
            "lrc": "https://reuixiy.github.io/uploads/lyrics/coldplay-fix-you.lrc"
        }
    ]
}
{% endaplayerlist %}

## music

{% aplayer "Live Forever" "Oasis" "https://yixiuer.oss-cn-shanghai.aliyuncs.com/music/Oasis%20-%20Live%20Forever.mp3" "https://yixiuer.oss-cn-shanghai.aliyuncs.com/music-cover/oasis-live-forever.jpg" "lrc:https://yixiuer.oss-cn-shanghai.aliyuncs.com/lyrics/oasis-live-forever.lrc" %}

## video

{% dplayer "url=https://yixiuer.oss-cn-shanghai.aliyuncs.com/Video/404bg.mp4" %}

## emoji

:joy:

```
\:joy\:
```

## image

有标题（title）的图片～

![hexo-next-optimization-title.jpg](https://yixiuer.oss-cn-shanghai.aliyuncs.com/Picture/hexo-next-optimization-title.jpg "打造个性超赞博客Hexo+NexT+GithubPages的超深度优化")

```
![photo_alt](photo_url "photo_title")
```

https://github.com/iissnan/hexo-theme-next/pull/279

## gallery

Front-matter：

```
photos:
- photo_url_1
- photo_url_2
- photo_url_3
- photo_url_4
- photo_url_5
- photo_url_6
```

效果：

![gallery.jpg](https://yixiuer.oss-cn-shanghai.aliyuncs.com/Picture/gallery.jpg)

## group-pictures

Front-matter：

```
type: picture
```

Usage：

```
{% gp 4-3 %}
![photo_alt_1](photo_url_1)
![photo_alt_2](photo_url_2)
![photo_alt_3](photo_url_3)
![photo_alt_4](photo_url_4)
{% endgp %}
```

效果：

![group-pictures.jpg](https://yixiuer.oss-cn-shanghai.aliyuncs.com/Picture/group-pictures.jpg)

https://github.com/iissnan/hexo-theme-next/blob/master/scripts/tags/group-pictures.js

## link

Front-matter：

```
link: url
```

效果：

![link.jpg](https://yixiuer.oss-cn-shanghai.aliyuncs.com/Picture/link.jpg)

## quote？

阅读主题的源代码发现的：`~/blog/themes/next/layout/_macro/post.swig`，有没有不确定，用法不确定……

Front-matter：

```
type: quote
```

效果：

![quote.jpg](https://yixiuer.oss-cn-shanghai.aliyuncs.com/Picture/quote.jpg)

## 推荐文章

https://github.com/huiwang/hexo-recommended-posts

https://github.com/tea3/hexo-related-popular-posts

<hr />
