---
title: "Posts"
layout: archive
author_profile: false
permalink: /posts/
---
{% assign sorted_posts = site.posts | reverse %}

{% for post in sorted_posts %}
  {% include archive-single.html %}
{% endfor %}
