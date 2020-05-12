---
layout: page
title: About
permalink: /gallery/
galleries:
  - title: Link to homepage
    image: /images/gallery1/1.jpg
    url: /images/gallery1
  - title: Link to image gallery
    image: /images/gallery2/1.jpg
    url: /images/gallery2
---
{% if page.galleries %}{% include image-gallery-index.html %}{% endif %}
