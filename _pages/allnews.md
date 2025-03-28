---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }} {{ article.headline }}</b>

{{ article.body }}
{% endfor %}

</div>
