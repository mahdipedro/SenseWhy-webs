---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We are a friendly, forward-thinking collective, an approachable team with a can-do attitude. Our curiosity and breadth of experience mean we can turn our minds to new challenges, combining the need for functionality with a desire for aesthetic value.


{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: cto"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: engineer"
%}


 .

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: member1"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: founder"
%}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"


  image3="images/NSF.png"
  link3="https://www.nsf.gov/"
  tooltip3="Cool Initiative"

  image4="images/NIH.png"
  link4="https://www.nih.gov/"
  tooltip4="Cool Foundation"
%}
