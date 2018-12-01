---
layout: default
title: "韦氏传媒 | 分类"
---

<ul class="list-unstyled">
{% for cat in site.categories %} 
  {% if cat[0] != 'blog' %} 
     <a name="{{ cat[0] }}" style="position: relative; top: -70px; display: block; height: 0; overflow: hidden;"></a>
     <h3>{{ cat[0] }} [{{ cat[1].size }}]</h3> 
     {% for post in cat[1] %} 
       <li>
         <h4>
           <a href="{{ post.url }}">{{ post.title }}</a>
           <div class="post-date"><span class="glyphicon glyphicon-time"></span> {{ post.date | date_to_string }} </div>
         </h4>
       </li>           
	   {% endfor %} 
   {% endif %} 
{% endfor %} 
</ul>
  
  


