---
layout: page
title: research & projects
---

{% for post in site.categories.projects %}
  <div class="post-block">
    <p class="sub-heading">{{ post.date | date: "%b %-d, %Y" }}</p>
    <h2 class=""><a href="{{ post.url | prepend: site.baseurl }}">{{post.title}}</a></h2>
    <div class="post-content"><p>{{ post.content }}</p></div>
    <div><p><span>CODE</span>&nbsp;<span>REPORT</span></p></div>
  </div>
{% endfor %}
