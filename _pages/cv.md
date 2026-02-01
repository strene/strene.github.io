---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Applied Mathematics, Norwegian University of Science and Technology (NTNU), 2018
  * Visiting student researcher at Stanford University, Energy Science & Engineering
* M.S. in Industrial Mathematics, Norwegian University of Science and Technology (NTNU), 2014
  * Exchange student at KTH Royal Institute of Technology

Work experience
======
* 2018-Present: Research Scientist
  * SINTEF Digital, Applied Computational Sciences Group
  * Duties include: Development of numerical simulation technology, linear and nonlinear solution strategies, discretizations, and grid generation
  * Focus: Geoenergy systems and porous media flow simulation

* 2022 (Fall term): Associate Professor (førsteamanuensis) - Part-time
  * Oslo Metropolitan University, Mathematical Modelling Group
  * Duties included: Teaching algorithms and data structures
  
Software Development
======
* Lead developer of [Fimbul](https://sintefmath.github.io/Fimbul.jl/dev/): Julia-based toolbox for geothermal simulation
* Core developer of [JutulDarcy](https://sintefmath.github.io/JutulDarcy.jl/stable/): Fully differentiable, high-performance porous-media flow simulator
* Core developer of [MATLAB Reservoir Simulation Toolbox (MRST)](https://www.sintef.no/projectweb/mrst/): Open-source toolbox for porous media flow simulation

Organization and Service
======
* Nordic representative, Young Investigators Committee, European Community on Computational Methods in Applied Sciences (ECCOMAS YIC)
* Organizing committee member, [Geilo Winter Schools in eSciences](http://geilowinterschool.no/)

Research Interests
======
* Numerical simulation of geoenergy systems
* Efficient linear and nonlinear solution strategies
* Discretizations and grid generation for porous media
* High-performance scientific computing
* Open and reproducible science

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  