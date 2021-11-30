---
layout: page
title: "Home"
class: home
---

# Hi, I'm Ian Huang

<div class="columns" markdown="1">

<div class="intro" markdown="1">
I am a Ph.D. student studying communications engineering under Professor Shih-Yuan Chen at National Taiwan University as a part of the Advanced Antenna Lab. My research focuses on the integration and characterization of ESR control and readout circuitries for silicon spin-based qubits as well as the design of cryogenic circuits for quantum applications. I graduated from the University of Michigan with a bachelor’s degree in Mechanical Engineering in 2016.
</div>

<div class="me" markdown="1">
<picture>
  <a href="/images/ID_20210705.jpg">
    <img
      src= '/images/ID_20210705.jpg'
      alt='Ian Huang'>
  </a>
</picture>
  <br>
  <a href="{{ "/Ian Huang's Resume.pdf" | relative_url }}" class="button">
    <i class="fas fa-chevron-circle-right"></i>
    <b>Download CV</b>
  </a>

<!-- {:.no-list}
* <a href="mailto:{{ site.email }}">{{ site.email }}</a> -->
</div>

</div>
<!---
## Featured Projects

<div class="featured-projects">
  {% assign sorted_projects = site.data.projects | sort: 'highlight' %}
  {% for project in sorted_projects %}
    {% if project.highlight %}
      {% include project.html project=project %}
    {% endif %}
  {% endfor %}
</div>
<a href="{{ "/projects/" | relative_url }}" class="button">
  <i class="fas fa-chevron-circle-right"></i>
  Show More Projects
</a>

## Awards
{% assign awards = site.data.awards %}
{% for award in awards %}
  <div class="awards">
    {% include awards.html award = award %} 
  </div>
{% endfor %}
-->