---
layout: default
---
<h1>{{ site.title }}</h1>

<h2>My thoughts in writing</h2>
{% if site.posts.size > 0 %}
<ul class="posts">
{% for post in site.posts %}
  <li><time>{{ post.date | date: "%b %-d, %Y" }}</time><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
<p class="empty">Nothing here yet.</p>
{% endif %}
