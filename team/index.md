---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# Team
{:.center}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}