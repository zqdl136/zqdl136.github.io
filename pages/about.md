---
layout: page
title: About
description: 打码改变世界
keywords: Zhuang Ma, 马壮
comments: true
menu: 关于
permalink: /about/
---

是个存放无用文字的个人博客。

有原创，有同人，活在布袋戏和很多其他坑里，爱豆是谢君豪先生。

爱自由，胜过一切！

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
</ul>



