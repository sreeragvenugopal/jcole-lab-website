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
{% include list.html data="members" component="portrait" filters="role: undergraduate student, group: " %}
{% include list.html data="members" component="portrait" filters="role: graduate student, group: " %}
{% include list.html data="members" component="portrait" filters="role: pra, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{:.center}

{% include section.html dark=true %}

## The Cole Lab is hiring!
{:.center}
Come join us as we grow the lab
{:.center}

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

  image1="images/funding/ADA.jpg"
  link1="https://diabetes.org/"
  tooltip1="American Diabetes Association"

  image2="images/funding/NIDDK.jpg"
  link2="https://www.niddk.nih.gov/"
  tooltip2="National Institute of Diabetes and Digestive and Kidney Diseases"

  image3="images/funding/lfcwhr_h_clr_rgb copy.jpg"
  link3="https://medschool.cuanschutz.edu/center-for-womens-health-research"
  tooltip3="Ludeman Family Center for Women's Health Research"
  
  image4="images/funding/TRSP.jpg"
  link3="https://medschool.cuanschutz.edu/program-to-advance-physician-scientists-translational-research/physician-scientist-initiatives/Early-faculty-TRSP"
  tooltip3="Translational Research Scholars Program"
  
  image5="images/funding/NIGMS_v2.jpg"
  link3="https://medschool.cuanschutz.edu/center-for-womens-health-research"
  tooltip2="National Institute of General Medical Sciences"

%}
