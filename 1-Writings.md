---
layout: page
title: Writings
permalink: /writings/
---
{% for post in site.posts %}
  <div class="container" style="margin-top: 5%; margin-bottom:5%;">
    <div style="margin-left:0%;">
    <p><small style="color:grey"><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . <a href="/categories/{{post.categories}}">{{ post.categories }} </a></small></p>
    <h2><i class= "fa fa-link"></i>   <a href="{{ post.url }}" style="color:black;">{{ post.title }}</a> </h2>
</div>
</div>
{% endfor %}
