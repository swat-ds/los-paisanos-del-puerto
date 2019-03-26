---
layout: front
permalink: /
title: home
image_banner: images/banner.jpg
---

***Listen*** __to the interviews and click on their titles for the transcriptions(coming soon!)__

<div class="tiles">

{% for post in site.posts reversed %}
{% if post.image_teaser %}
{% include post-grid.html %}
{% endif %}
{% endfor %}

</div>
<hr/>