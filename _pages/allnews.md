---
title: "News"
layout: textlay
excerpt: “Rao Research Group at UIUC”
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
