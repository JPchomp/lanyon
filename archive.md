---
layout: page
title: Archive
---

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &mdash; [ {{ post.title }} ]('lanyon/' + {{ post.url }})
{% endfor %}
