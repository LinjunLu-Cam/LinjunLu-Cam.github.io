---
layout: archive
title: "Life Photos"
permalink: /life-photos/
author_profile: true
---

Welcome to my life photo gallery!

<!-- You can include images manually like this: -->
<img src="/photos/IMG_3851.jpeg" alt="Life Photo 1" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_4021.JPG" alt="Life Photo 13" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_4816.jpeg" alt="Life Photo 2" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_4856.jpeg" alt="Life Photo 3" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_5270.jpeg" alt="Life Photo 4" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_5579.jpeg" alt="Life Photo 5" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_5977.jpeg" alt="Life Photo 6" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_6044.jpeg" alt="Life Photo 7" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_6112.jpeg" alt="Life Photo 8" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_6220.jpeg" alt="Life Photo 9" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_6588.jpeg" alt="Life Photo 10" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_6741.JPG" alt="Life Photo 14" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_7042.jpeg" alt="Life Photo 11" style="max-width: 500px; margin: 30px;" />
<img src="/photos/IMG_7107.jpeg" alt="Life Photo 12" style="max-width: 500px; margin: 30px;" />

{% comment %}
If you later add a life collection (_life), this loop will render those posts:
{% endcomment %}
{% raw %}{% for post in site.life reversed %}
  {% include archive-single.html %}
{% endfor %}{% endraw %}
