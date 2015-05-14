---
layout: page
title: Software
tagline: Gaussian process software in python
---

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.pages_url }})
  {% for entry in repository %}
  {{ entry }}
  {% endfor %}}
{% endfor %}


### History

[Here](http://inverseprobability.com/2013/11/25/gpy-moving-from-matlab-to-python/)
is a blog post about the history of our Gaussian process software.

