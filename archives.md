﻿---
layout: default
title: "韦氏传媒 | 存档"
---

<ul class="list-unstyled">
     {% for post in site.posts limit:100 %} 
	 {% unless post.next %} 
    <h3>{{ post.date | date: '%Y' }}</h3> 
	{% else %} {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %} {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %} 
	{% if year != nyear %} 
    <h4>{{ post.date | date: '%Y' }}</h4> {% endif %} 
	{% endunless %} 
    <li>
      <h4> 
        <a href="{{ post.url }}">{{ post.title }}</a>
        <div class="post-date"> <span class="glyphicon glyphicon-time"></span> {{ post.date | date_to_string }} </div>
      </h4>
    </li> 
	{% endfor %} 
</ul> 
  
  
  

