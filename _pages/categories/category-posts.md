---
title: "Posts"
layout: archive
permalink: /categories/posts
author_profile: true
sidebar-posts: true
---

{% assign posts = site.categories.posts | sort:"date" %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
