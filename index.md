---
layout: page
title: Primate Populations
tagline: ANTH 350-101, Winter 2015
---
{% include JB/setup %}


<!--<div style="text-align:center">
<figure>
  <a title="Cartoon monkey" href="http://commons.wikimedia.org/wiki/File%3AEditorial_cartoon_depicting_Charles_Darwin_as_an_ape_(1871).jpg"><img width="256" alt="Cartoon monkey" src="//upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Editorial_cartoon_depicting_Charles_Darwin_as_an_ape_%281871%29.jpg/256px-Editorial_cartoon_depicting_Charles_Darwin_as_an_ape_%281871%29.jpg"/></a>
</figure>
</div>-->

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

