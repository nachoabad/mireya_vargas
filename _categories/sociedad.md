---
layout: default
title: Sociedad
banner_1: Sociedad
banner_2:
---

{% include banner.html %}

{% assign filtered_posts = site.posts | where: 'sociedad', true %}

{% include post_list.html %}