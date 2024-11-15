---
---
# About Us

The Intelligent Autonomy Lab is led by Prof. Ian Abraham. Our research focus is at the intersection of robotics, optimal control, and learning, developing algorithmic methods that enable robots to explore, learn, and experiment to become provably self-sufficient autonomous agents.

<!-- {% include section.html %}

<!-- ## Demo


<div id="cube" style="--aspect-ratio:16/9;">
  <script type="module" src="demos/simple.js"></script>
</div> -->



{% include section.html %}

## Highlights

{% capture text %}

Robotic systems have the potential to enhance our way of life and solve some of the world's most difficult problems---but in doing so they encounter situations unanticipated by the robot designer and software developer. Our research investigates this gap by framing artificial curiosity and experimentation as real-time computational problems solvable through online optimization. 

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
