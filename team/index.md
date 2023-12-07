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
{% include section.html %}

<!-- PostDocs -->
{% include list.html data="members" component="portrait" filters="role: postdoc" %}

<!-- Software Engineers -->
{% include list.html data="members" component="portrait" filters="role: software-engineer" %}

<!-- PhD Students -->
{% include list.html data="members" component="portrait" filters="role: phd-*" %}

<!-- MS Students -->
{% include list.html data="members" component="portrait" filters="role: masters-*" %}

<!-- Undergrad students -->
{% include list.html data="members" component="portrait" filters="role: undergrad-*" %}
{% include section.html %}

<!-- Alumni -->
## Alumni
{:.center}

{% include portrait.html name="Chaitra Hedge (Ph.D., Gatech ECE, 2023)<br>- Amazon" image="images/members/chaitra-hedge.jpeg" %}

{% include portrait.html name="N. Jabin Gong (BS, Gatech CS, 2023)<br>- School of Medicine, Stony Brook" image="images/members/jabin_pic.png" %}
<!-- {% include portrait.html name="N. Jabin gong (BS, Gatech CS, 2023)" lookup="jabin-gong" image="images/members/jabin_pic.png" style="small" %} -->

{% include section.html %}

<!-- Social Photo -->
{% capture content %}
![image]({{ "/images/socials/dinner-2023.12.06.jpeg" | relative_url }})
{% endcapture %}
{% include grid.html content=content %}
