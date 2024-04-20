---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# Team
{:.center}

{%
  include button.html
  type="link"
  icon=""
  text="Team Social"
  link="team/#team-photo"
%}


{% include section.html %}

<!-- Director -->
{% include list.html data="members" component="portrait" filters="role: director" %}
{% include section.html %}

<!-- Research Scientist -->
{% include list.html data="members" component="portrait" filters="role: research-scientist" %}

<!-- PostDocs -->
{% include list.html data="members" component="portrait" filters="role: postdoc" %}

<!-- Clinical Research Coordinator -->
{% include list.html data="members" component="portrait" filters="role: clinical-reseaerch-coordinator" %}

<!-- Software Engineers -->
{% include list.html data="members" component="portrait" filters="role: software-engineer" %}

<!-- PhD Students -->
{% include list.html data="members" component="portrait" filters="role: phd-" %}

<!-- MS Students -->
{% include list.html data="members" component="portrait" filters="role: masters-" %}

<!-- Undergrad students -->
{% include list.html data="members" component="portrait" filters="role: undergrad-" %}
{% include section.html %}

<!-- Alumni -->
## Alumni
{:.center}

{% include portrait.html name="Chaitra Hedge (Ph.D., Gatech ECE, 2023)<br>- Amazon" image="images/members/phd-students/alumni/chaitra-hedge.jpeg" %}

{% include portrait.html name="N. Jabin Gong (BS, Gatech CS, 2023)<br>- School of Medicine, Stony Brook" image="images/members/undergrads/alumni/jabin_pic.png" %}
<!-- {% include portrait.html name="N. Jabin gong (BS, Gatech CS, 2023)" lookup="jabin-gong" image="images/members/jabin_pic.png" style="small" %} -->

{% include section.html %}

<!-- Social Photo -->
## Team Photo
{:.center}

{% capture content %}
![image]({{ "/images/socials/dinner-2024.04.19-1.jpg" | relative_url }})

![image]({{ "/images/socials/dinner-2024.04.19-2.jpg" | relative_url }})

<!-- ![image]({{ "/images/socials/bme_star_ai_2024/arya_lauhitya.jpeg" | relative_url }}) -->
![image]({{ "/images/socials/bme_star_ai_2024/arya_lauhitya-blur.png" | relative_url }})

<!-- ![image]({{ "/images/socials/bme_star_ai_2024/ketan_shoibolina.jpg" | relative_url }}) -->
![image]({{ "/images/socials/bme_star_ai_2024/ketan_shoibolina-blur.png" | relative_url }})

<!-- ![image]({{ "/images/socials/bme_star_ai_2024/scarlett.png" | relative_url }}) -->
![image]({{ "/images/socials/bme_star_ai_2024/scarlett-blur.png" | relative_url }})

![image]({{ "/images/socials/provost_award/zikang-provost-with-thomas.png" | relative_url }})

![image]({{ "/images/socials/provost_award/zikang-provost-award.JPG" | relative_url }})

![image]({{ "/images/awards/Zekang-iswc-2023.JPG" | relative_url }})

![image]({{ "/images/socials/dinner-2023.12.06.jpeg" | relative_url }})

![image]({{ "/images/socials/BMI_party-2023.12.07/decoration-wall.jpg" | relative_url }})

![image]({{ "/images/socials/CEP-2023.12.08/lunch.png" | relative_url }})

![image]({{ "/images/socials/BMI_party-2023.12.07/soheil-sepideh.jpg" | relative_url }})

![image]({{ "/images/socials/CEP-2023.12.08/cep-board.png" | relative_url }})

![image]({{ "/images/socials/BMI_party-2023.12.07/tv.jpg" | relative_url }})
{% endcapture %}
{% include grid.html content=content %}
