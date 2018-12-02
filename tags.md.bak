---
layout: default
title: "韦氏传媒 | 标签"
---

{% include includes-tags.html %} 

{% comment %}
=======================
The purpose of this snippet is to list all your posts posted with a certain tag.
=======================
{% endcomment %}

{% for tag in tags %}

 <a name="{{ tag }}" style="position: relative; top: -60px; display: block; height: 0; overflow: hidden;"></a> 
 <h3 id="{{ tag | slugify }}">{{ tag }}</h3>
 <ul class="list-unstyled">
{% for post in site.posts %}
  {% if post.tags contains tag %}
  <li>
    <h4>
      <a href="{{ post.url }}"> {{ post.title }}</a>
      <div class="post-date"><span class="glyphicon glyphicon-time"></span> {{ post.date | date_to_string }} </div
    </h4>
  </li>
  {% endif %}
{% endfor %}
 </ul>
{% endfor %}
