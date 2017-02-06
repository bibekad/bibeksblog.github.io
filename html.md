---
layout: categories
title: html
permalink: /categories/html/
---
{% for post in site.categories.html %}
<div style="margin-top: 5%; margin-bottom:5%;">
{{post.categories}}  {{ post.date | date: "%b %e, %Y" }}
<h2><a href="{{post.url}}"  style="color:black;"> {{post.title}}</a></h2>
</div>
{% endfor %}
