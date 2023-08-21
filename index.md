---
---

# i-abr's Website

The Intelligent Autonomy Lab is led by Ian Abraham. Our research interest is at the intersection of optimal control and learning theory, developing algorithmic methods that enable robots to explore, intentionally learn, and experiment to become provably self-sufficient autonomous agents.

<!-- Robotic systems have the potential to enhance our way of life and solve some of the worlds most difficult problems---but in doing so they encounter situations unanticipated by the robot designer and software developer. We are interested in bridging this gap by framing artificial curiosity and experimentation as real-time computational problems solvable through online optimization.  The Intelligent Autonomy Lab's research focuses on the analysis of structural dependencies in algorithmic design, the relationship between sensing capabilities and potential learning outcomes, and the computational and data requirements for robots to achieve complex tasks and behaviors. Our work spans a wide range of problems in optimal control,  sample-efficient learning, manipulation, locomotion, and multi-agent coordination.  -->


{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
