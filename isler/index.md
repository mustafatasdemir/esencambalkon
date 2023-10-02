---
layout: isler
title: "Örnek İşler"
date: 2014-06-02T09:44:20-04:00
modified: 2014-08-27T14:56:44-04:00
excerpt: ""
image:
  feature:
  teaser:
  thumb:
share: false
ads: false
---

{% for image in site.static_files %}
    {% if image.path contains 'images/isler' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}