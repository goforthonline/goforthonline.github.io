---
title: "All Updates"
permalink: /posts/
---

{% for post in site.posts %}
<div class='post'>
	<div class='metadata'><h3><a href='{{ post.url }}'>{{ post.title }}</></h3> <b>{{ post.date }}</b></div>
	{{ post.content }}
</div>
{% endfor %}

