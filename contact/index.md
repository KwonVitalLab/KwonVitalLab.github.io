---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# Contact
{:.center}


{%
  include button.html
  type="email"
  text="Email"
  tooltip="Mail to Director (Dr. Kwon)"
  link="hyeokhyen.kwon@emory.edu"
%}

<!-- Rm 4105, 4th Floor, Emory Woodruff Memorial Research Building (101 Woodruff Cir, Atlanta, GA 30322)
{:.center} -->

{%
  include button.html
  type="address"
  tooltip="Google Map"
  text="Rm 4105, 4th Floor, Emory Woodruff Memorial Research Building (101 Woodruff Cir, Atlanta, GA 30322)"
  link="https://www.google.com/maps/place/Emory+Woodruff+Memorial+Research+Building/@33.7931521,-84.3243962,17z/data=!3m2!4b1!5s0x88f506fa7cc1eaf9:0xdfd2cd440d909807!4m6!3m5!1s0x88f506fa0a36405b:0x17dc988a90d246a3!8m2!3d33.7931477!4d-84.3222075!16s%2Fg%2F1hc27g69j?authuser=0"
%}

<!-- Photo -->
<!-- {% include figure.html image="images/contact/BMI.png" width="50%" %} -->


{% capture content %}
![image]({{ "/images/contact/zoom-atlanta-skyline_bg_061.jpg" | relative_url }})

![image]({{ "/images/contact/zoom-bkgrnd5-brumley-bridge1.jpg" | relative_url }})

![image]({{ "/images/contact/zoom-bkgrnd6-school-of-medicine1.jpg" | relative_url }})

![image]({{ "/images/contact/13C10000-P14-013-1.jpg" | relative_url }})

![image]({{ "/images/contact/HSRB-bridge-Tech-Tower-wide.jpg" | relative_url }})

![image]({{ "/images/contact/georgiatech_uao_techtower-01.webp" | relative_url }})

{% endcapture %}
{% include grid.html content=content %}
