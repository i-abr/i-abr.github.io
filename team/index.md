---
title: Team
nav:
  order: 3
  tooltip: About our team
---


# {% include icon.html icon="fa-solid fa-users" %} PI
{% include list.html data="members" component="portrait" filters="role: pi" %}

# {% include icon.html icon="fa-solid fa-users" %} PhD Students 
<!-- {% include list.html data="members" component="portrait" filters="role: postdoc" %} -->
{% include list.html data="members" component="portrait" filters="role: phd" %}

# {% include icon.html icon="fa-solid fa-users" %} Undergraduate Students
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

# {% include icon.html icon="fa-solid fa-users" %} Alum

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: alum" %}


<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

<!-- {% include section.html background="images/background.jpg" dark=true %} 

<!-- {% include section.html %}  


{% capture content %} 

{% endcapture %} 

{% include grid.html style="square" content=content %}
