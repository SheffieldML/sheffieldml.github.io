---
layout: page
title: Software
tagline: software from the group
---

{% for repository in site.github.public_repositories %}
{% if repository.has_pages %}
{% if repository.name contains 'github.io' %}
{% else %}
* [{{ repository.description }}](./{{ repository.name }}/) ({{ repository.watchers_count }} watchers)
{% endif %}
{% endif %}
{% endfor %}



### History

[Here](http://inverseprobability.com/2013/11/25/gpy-moving-from-matlab-to-python/)
is a blog post about the history of our Gaussian process software.

