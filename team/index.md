---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# Team
{:.center}

{% include section.html %}

<!-- Director -->
{% include list.html data="members" component="portrait" filters="role: director" %}

<!-- PhD Students -->
{% include section.html %}
{% include list.html data="members" component="portrait" filters="role: phd*" %}

<!-- MS Students -->
{% include list.html data="members" component="portrait" filters="role: masters*" %}

<!-- Undergrad students -->
{% include list.html data="members" component="portrait" filters="role: undergrad*" %}

<!-- Alumnis -->