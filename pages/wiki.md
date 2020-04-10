---
layout: page
title: Keywords
description: 人越学越觉得自己无知
keywords: 标签, Keywords
comments: false
menu: 标签归档
permalink: /keywords/
---

> 记多少命令和快捷键会让脑袋爆炸呢？

<ul class="listing">
{% for keyword in site.keywords %}
{% if keyword.title != "Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ keyword.url }}">{{ keyword.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
