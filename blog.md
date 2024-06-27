---
layout: post-index
title: Blog
excerpt: Under construction
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---
# Blog posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
