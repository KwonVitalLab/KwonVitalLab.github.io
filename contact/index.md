---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# Contact
{:.center}


{%
  include button.html
  type="email"
  text="Email (Emory)"
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
  link="https://www.emoryhealthcare.org/locations/offices/woodruff-memorial-research-building"
%}

{%
  include button.html
  type="email"
  text="Email (Gatech)"
  tooltip="Mail to Director (Dr. Kwon)"
  link="hyeokhyen.kwon@gatech.edu"
%}


{%
  include button.html
  type="address"
  tooltip="Google Map"
  text="Rm 1586a, 15th Floor, Coda at TechSquare - Georgia Tech (756 W Peachtree St NW, Atlanta, GA 30308)"
  link="https://coda.gatech.edu/"
%}

{% include section.html %}

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
