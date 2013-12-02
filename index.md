---
layout: page
title: Seita
tagline: where belongs to Seita.
avatar: ../img/home.png
published: true
---

{% include JB/setup %}

这里是 Seita 的个人网站，使用 [Jekyll Bootstrap](http://jekyllbootstrap.com) 搭建。
 

我不擅长在网络上写大量文字，但记录可以使人安静下来，大道至简，灵感可见一般。

目前网站寄存在 [Github Pages](https://pages.github.com) 因此手上的 VPS 闲置了下来，可以免费提供给有需要的人: [详细](/vps.html)。


#### 最近发布的文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

#### 20 岁前的目标

<ul>
	<li>体验人生第一次互相喜欢的感觉 (*可选)</li>
	<li>做出一个让自己满意的 Web 作品</li>
	<li>赚人生中第一个 10k 元</li>
	<li>和好朋友再去高中踢一场 90 分钟的足球，全副装备</li>
	<li>去九里堤再吃一次水煮肉片</li>
	<li>做一个公益项目 (*可选)</li>
	<li>买一台 MBP 或者 两台</li>
	<li>看完手上的《海边的卡夫卡》和 《名侦探的守则》</li>
	<li>准备21岁前的目标</li>

</ul>



