---
title: "News"
layout: textlay
excerpt: "Daniel Soudry's Lab at the Technion"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
   {{ article.date }} 
   {{ article.headline | markdownify}} 
{% endfor %}
