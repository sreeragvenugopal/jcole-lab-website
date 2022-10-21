---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

##The Cole Lab is hiring!

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/funding/ADA.jpg"
  link1="https://diabetes.org/"
  tooltip1="American Diabetes Association"

  image2="images/funding/NIDDK.jpg"
  link2="https://www.niddk.nih.gov/"
  tooltip2="National Institute of Diabetes and Digestive and Kidney Diseases"

%}
