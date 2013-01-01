---
layout: page
title: fuxiao
tagline: 
---
{% include JB/setup %}

新的一年,新的开始！

本博客由 [jekyll](https://github.com/mojombo/jekyll) 搭建.


### 最近发布的文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



