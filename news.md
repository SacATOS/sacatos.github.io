---
layout: page
title: ATOS Labs in the News
tagline: Autonomous Transportation Open Standards Lab
permalink: /news
---

{% assign sorted = (site.data.news | sort: 'date') | reverse %}

{% for article in sorted %}

# {{ article.date }} - [{{ article.title }}]({{ article.url }})

{% endfor %}
