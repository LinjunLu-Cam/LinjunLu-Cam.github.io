---
layout: archive
title: "Life Photos"
permalink: /life-photos/
author_profile: true
---

Welcome to my life photo gallery!

<!-- You can include images manually like this: -->
<img src="/photos/IMG_3851.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_4816.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_4856.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_5270.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_5579.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_5977.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_6044.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_6112.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_6220.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_6588.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_7042.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />
<img src="/photos/IMG_7107.jpeg" alt="Life Photo 1" style="max-width: 1000px; margin: 30px;" />

<!-- Or, if you're using posts in a collection like _life/, you can loop them here -->
{% for post in site.life reversed %}
  {% include archive-single.html %}
{% endfor %}
