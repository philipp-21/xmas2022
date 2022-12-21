---
layout: default.liquid
title: Frohe Weihnachten!
---
# Frohe Weihnachten!

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
