---
title: "All Posts"
permalink: /posts/
---

{% for post in site.posts %}
<div class='post'>
	<div class='metadata'>{{ post.title }} ({{ post.date }})</div>
	{{ post.content }}
</div>
{% endfor %}

