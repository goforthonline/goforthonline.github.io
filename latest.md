---
title: Latest
permalink: /latest/
---

{% assign post = site.posts.first %}

<div class='post'>
	<div class='metadata'><h3><a href='{{ post.url }}'>{{ post.title }}</a></h3> <b>{{ post.date }}</b></div>
	{{ post.content }}
</div>
