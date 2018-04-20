---
layout: page
title: About
description: 愿你出走半生，归来仍是少年
keywords: Bing ge, Beyong
comments: true
menu: 关于
permalink: /about/
---

Python程序员。

业精于勤荒于嬉。

「朴树」「李志」忠实粉丝。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
