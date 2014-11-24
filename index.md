---
layout: page
title: Primate Populations
tagline: ANTH 350-101, Winter 2015
---
{% include JB/setup %}

# Welcome

Hello and welcome to the website for my Primate Populations weekend college at Eastern Oregon University. This website is currently under development...more changes coming soon.


<br>
<br>
<br>

### Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

