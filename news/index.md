---
title: News
nav:
  order: 4
  tooltip: Lab news and announcements
---

# {% include icon.html icon="fa-regular fa-newspaper" %}News

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
