---
layout: categories
title: c-tutorial
permalink: /categories/c-tutorial/
---
{% for post in site.categories.c-tutorial %}
<div style="margin-top: 5%; margin-bottom:5%;">
{{post.categories}}  {{ post.date | date: "%b %e, %Y" }}
<h2><a href="{{post.url}}"  style="color:black;"> {{post.title}}</a></h2>
</div>
{% endfor %}
