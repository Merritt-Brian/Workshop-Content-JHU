---
layout: post
title:  "Theory"
date:   2021-03-31 15:26:36 -0400
categories: jekyll update
permalink: /modules/theory

---

{% assign link = site.data.navigation[1].sublinks[0] %}
{% for sublink in link.sublinks %}
[{{sublink.title}}]( {% link pages{{ sublink.url }}.md  %} )
{% endfor %}

