---
layout: archive
title: "Life Photos"
permalink: /life_photos/
author_profile: true
---

Welcome to my life photo gallery!

<!-- You can include images manually like this: -->
<img src="/life_photos/life1.jpg" alt="Life Photo 1" style="max-width: 300px; margin: 10px;" />
<img src="/life_photos/life2.jpg" alt="Life Photo 2" style="max-width: 300px; margin: 10px;" />

<!-- Or, if you're using posts in a collection like _life/, you can loop them here -->
{% for post in site.life reversed %}
  {% include archive-single.html %}
{% endfor %}
