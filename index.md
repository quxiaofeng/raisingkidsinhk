---
layout: home
permalink: /
image:
  feature: wood-texture-1600x800.jpg
---

<div class="tiles">
{% for post in site.articles.posts %}
    {% include posts-list.html %}
{% endfor %}
</div><!-- /.tiles -->
