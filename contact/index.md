---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

Our company is located at 505 N McClurg Ct., Chicago IL 60611

{%
  include link.html
  type="email"
  icon=""
  text="info@sensewhyinc.com"
  tooltip=""
  link="info@sensewhyinc.com"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(555) 867-5309"
  tooltip=""
  link="+1-555-867-5309"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/505+N+McClurg+Ct,+Chicago,+IL+60611/@41.8915286,-87.6218113,17z/data=!3m1!4b1!4m6!3m5!1s0x880e2b55bea4de4b:0x2814ebcb9d62ecb5!8m2!3d41.8915247!4d-87.6173266!16s%2Fg%2F11b8v5cklz"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

505 N McClurg Ct., Chicago IL 60611  
USA
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="The Center for Wit and Sagacity"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Department of Metaphor"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
