---
layout: page
title: research & projects
---

<h2 class="page-sub-heading">publications</h2>
{% for post in site.categories.publications %}
  <div class="post-block">
    <!-- <p class="sub-heading">{{ post.date | date: "%b %-d, %Y" }}</p> -->
    <h4 class="" style="border: none; margin-bottom: -5px"><a href="{{ post.url | prepend: site.baseurl }}">{{post.title}}</a></h4>
    <div class="post-content"><p><i>{{ post.content }}</i></p></div>
    <div><p><span><a href="{{post.repoUrl}}"><i class="fa fa-solid fa-code fa-border"></i></a></span>&nbsp;<span><a href="{{post.paperUrl}}"><i class="fa fa-solid fa-file-pdf fa-border"></i></a></span></p></div>
  </div>
{% endfor %}

<h2 class="page-sub-heading">projects</h2>
{% for post in site.categories.projects %}
  <div class="post-block">
    <!-- <p class="sub-heading">{{ post.date | date: "%b %-d, %Y" }}</p> -->
    <h4 class="" style="border: none; margin-bottom: -5px"><a href="{{ post.url | prepend: site.baseurl }}">{{post.title}}</a></h4>
    <div class="post-content"><p>{{ post.content }}</p></div>
    <div><p><span><a href="{{post.repoUrl}}"><i class="fa fa-solid fa-code fa-border"></i></a></span>&nbsp;<span><a href="{{post.paperUrl}}"><i class="fa fa-solid fa-file-pdf fa-border"></i></a></span></p></div>
  </div>
{% endfor %}
