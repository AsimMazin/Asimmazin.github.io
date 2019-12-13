---
layout: archive
permalink: /projects/
title: "Projects "
author_profile: true
header:
    image: "/images/frontimage.jpg"

{% for post in site.posts %}
    <li><a href="{{post.url}}">{{post.title}}</a></li>
{% endfor %}


