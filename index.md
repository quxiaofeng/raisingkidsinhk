---
layout: archive
permalink: /
image:
  feature: wood-texture-1600x800.jpg
---

<div class="tiles">
{% for post in site.categories.articles %}
    {% include posts-list.html %}
{% endfor %}
</div><!-- /.tiles -->
