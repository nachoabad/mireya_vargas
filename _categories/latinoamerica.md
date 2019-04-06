---
layout: default
title: Latinoamérica
banner_1: Latinoamérica
banner_2:
---

{% include banner.html %}

{% assign filtered_posts = site.posts | where: 'latinoamerica', true %}

{% include post_list.html %}