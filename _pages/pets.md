---
title: Disneyland Resort
layout: collection
permalink: /dr/
collection: dr
entries_layout: grid
classes: wide
---

Sample document listing for the collection `_dr`.

{% for post in site.dr %}
  {% unless post.hidden %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}