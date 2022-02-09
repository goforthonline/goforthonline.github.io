---
title: Index
---

# Go Forth Online Blog

This is the development and update blog for my (Kami's) web game, Go Forth Online.

{% for post in site.posts %}
<div class='post'>
	{{ post.content }}
</div>
{% endfor %}
