---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

# {% include icon.html icon="fa-solid fa-users" %}Alum

{% include section.html %}

{% include list.html data="members" component="portrait" filters="group: alum" %}


<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

<!-- {% include section.html background="images/background.jpg" dark=true %} 

<!-- {% include section.html %}  


{% capture content %} 

{% endcapture %} 

{% include grid.html style="square" content=content %}
