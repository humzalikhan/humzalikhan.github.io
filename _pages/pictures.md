---
layout: archive
title:
permalink: /pictures/
author_profile: true
redirect_from:
- /picture
- /pictures
- /photos
- /photo
---

{% include base_path %}


{% for post in site.photos %}
  {% include archive-single.html %}
{% endfor %}
