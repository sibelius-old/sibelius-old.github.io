---
title: Gallery
layout: default
feature_text: <h2>Gallery</h2>
feature_image: "https://picsum.photos/1300/400?image=989"
---
<main class="main container">
<div class="content">
{% assign all = site.html_pages | where: 'layout', 'gallery' %}

{% for a in all %}
<h5>[{{ a.title }}]({{ a.url }})</h5>
{% endif %}
</div>
</main>
