---
title: 'Tags'
layout: default
feature_image: "https://picsum.photos/1300/400?image=989"
feature_text: |
  ## Tags
---
<main class="main container">
<article class="article  article--page  content  typeset">

{% for t in site.tag %}
<a href="{{ t.url }}" class="button hvr-curl-top-left">{{ t.tag }}</a>
{% endfor %}

</article>
</main>
