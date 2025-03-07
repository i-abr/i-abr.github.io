---
---
# About Us

The Intelligent Autonomy Lab is led by Prof. Ian Abraham. 

Robotic systems have the potential to enhance our way of life and solve some of the world's most difficult problems---but in doing so they encounter situations unanticipated by the robot designer and software developer. Robots need to be equipped with mechanisms that allow them to respond to the unknown reliably to guarantees their success.  

We are interested in discovering principles for robots to adapt and learn in real-time through negotiating and responding to their environment. Specifically, our research seeks to analyze and discover principled methods that enable robots to curiously explore, interact, and learn in novel scenarios with minimal data, compute, and with strong performance and reliability guarantees.

<!-- {% include section.html %}

<!-- ## Demo


<div id="cube" style="--aspect-ratio:16/9;">
  <script type="module" src="demos/simple.js"></script>
</div> -->



{% include section.html %}

## Highlights

{% capture text %}

Our research is at the intersection of robotics, optimal control, and learning, developing algorithms that enable robots to reliably learn, explore, and navigate complex environments.


{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/bunny_inspection_abstract_fig.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Our work spans a wide range of problems in optimal control, learning, exploration, manipulation, locomotion, and multi-agent coordination. We regularly provide demos and readily deployable open-source code.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/allegro_manip.gif"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lab members consist of a diverse group of undergraduate, graduate, and postdoctoral students working on several exciting research fronts. For inquiries about our research, joining the lab, our outreach please see our [contact page](contact). 



{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/summer_cookout_2022_0.jpg"
  link="team"
  title="Our Team"
  text=text
%}
