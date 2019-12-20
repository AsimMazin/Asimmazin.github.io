---
layout: archive
permalink: /projects/
title: "Projects "
author_profile: true
header:
    image: "/images/frontimage.jpg"

{{ content }}

<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}


