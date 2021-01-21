---
layout: page
title: 자료실
permalink: /opinion/
---

<br>
### 자료실

<br>

{% for post in site.categories.column %}
##### [{{ post.title }}]({{ post.url | relative_url }})
<time datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">
{% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
{{ post.date | date: date_format }}
{% assign author = site[post.author] %}
{% if author %}
|&nbsp;{{ author.name }}({{ author.organization }})
{% endif %}
</time>
-------------
{% endfor %}

<br>
