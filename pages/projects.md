---
layout: page
title: research & projects
---

{% for post in site.categories.projects %}
  <div class="post-block">
    <!-- <p class="sub-heading">{{ post.date | date: "%b %-d, %Y" }}</p> -->
    <h3 class=""><a href="{{ post.url | prepend: site.baseurl }}">{{post.title}}</a></h3>
    <div class="post-content"><p>{{ post.content }}</p></div>
    <div><p><span><a href="{{post.repoUrl}}"><i class="fa fa-solid fa-code fa-border"></i></a></span>&nbsp;<span><a href="{{post.paperUrl}}"><i class="fa fa-solid fa-file-pdf fa-border"></i></a></span></p></div>
  </div>
{% endfor %}
