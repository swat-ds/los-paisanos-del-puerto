---
layout: front
permalink: /
title: home
image_banner: images/banner.jpg
---
<div class="tiles">

{% for post in site.posts reversed %}
{% if post.image_teaser %}
{% include post-grid.html %}
{% endif %}
{% endfor %}

</div>
<hr/>