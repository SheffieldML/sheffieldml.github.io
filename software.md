---
layout: page
title: Software
tagline: software from the group
---

### History

[Here](http://inverseprobability.com/2013/11/25/gpy-moving-from-matlab-to-python/) is a blog post about the history of our Gaussian process software.

### Repositories

This is now the home for our four GP software repositories, GPy, GPmat, GPc and gptk in Python, Matlab, C and R.

{% for repository in site.github.public_repositories %}
{% if repository.has_pages %}
{% if repository.name contains 'github.io' %}
{% else %}
* [**{{ repository.name }}**](./{{ repository.name }}/) {{ repository.description }} ({{ repository.watchers_count }} watchers)
{% endif %}
{% endif %}
{% endfor %}

Some of our software is also available on other pages such as [Neil's software page](http://inverseprobability.com/software.html) where you can find the original versions of our MATLAB toolbox (which were subdivided: kern, ivm, gp, etc.) and the page of the [Open Data Science Initiative](http://opendsi.cc/software.html).


