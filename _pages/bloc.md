---
title: "Blog i Novetats"
layout: archive
permalink: /blog/
author_profile: true
---

Aquí trobareu articles sobre tecnologia, apunts de classe i novetats sobre els meus projectes.

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}