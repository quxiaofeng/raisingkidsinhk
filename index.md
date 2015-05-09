---
layout: home
permalink: /
image:
  feature: homepage-baby-1024x500.jpg
---

<div class="tiles">
{% for post in site.articles.posts %}
    {% include posts-list.html %}
{% endfor %}
</div><!-- /.tiles -->
