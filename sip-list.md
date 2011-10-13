---
layout: default
title: Completed SIP list
---


### Draft SIPs ###
<ul class="post-list">
  {% for post in site.categories.draft %}
    <li><a href="/sips/{{ post.url }}">{{ post.title }}</a> <span class="date">( {{ post.date | date: "%b %Y" }} )</span></li>
  {% endfor %}      
</ul>

### Completed SIPs ###
<ul class="post-list">
  {% for post in site.categories.completed %}
    <li><a href="/sips/{{ post.url }}">{{ post.title }}</a> <span class="date">( {{ post.date | date: "%b %Y" }} )</span></li>
  {% endfor %}      
</ul>

### Rejected SIPs ###
<ul class="post-list">
  {% for post in site.categories.rejected %}
    <li><a href="/sips/{{ post.url }}">{{ post.title }}</a> <span class="date">( {{ post.date | date: "%b %Y" }} )</span></li>
  {% endfor %}      
</ul>
