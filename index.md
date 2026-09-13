---
layout: default
---
<h1>{{ site.title }}</h1>
<p>{{ site.description }}</p>

<ul class="posts">
{% for post in site.posts %}
  <li><time>{{ post.date | date: "%b %-d, %Y" }}</time><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
