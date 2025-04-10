---
layout: archive
title: "Life Photos"
permalink: /life-photos/
author_profile: true
---

Welcome to my life photo gallery!

<!-- You can include images manually like this: -->
<img src="/_life_photos/life1.png" alt="Life Photo 1" style="max-width: 800px; margin: 30px;" />
<img src="/_life_photos/life2.png" alt="Life Photo 2" style="max-width: 800px; margin: 30px;" />

<!-- Or, if you're using posts in a collection like _life/, you can loop them here -->
{% for post in site.life reversed %}
  {% include archive-single.html %}
{% endfor %}
