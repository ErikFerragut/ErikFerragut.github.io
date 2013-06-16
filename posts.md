---
layout: default
headline: Recent posts and comments.
---
  
<div class="span9">
<h4>News and Posts</h4>
<dl class='dl-horizontal'>
  {% for post in site.posts %}
  <dt>{{ post.date | date_to_long_string }}</dt>
  <dd><a href="{{ post.url }}">{{ post.title }}</a></dd>
  {% endfor %}
</dl>
</div>

