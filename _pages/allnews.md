---
title: "EAS Lab News"
layout: textlay
excerpt: "EAS Lab"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<div class="news-item">
    <span>{{ article.date }}</span><br>
    <span>{{ article.headline | markdownify }}</span>
</div>
{% endfor %}
