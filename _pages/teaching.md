---
layout: archive
title: "teaching"
permalink: /teaching/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Physics
### VPython
Here is a link to my [VPython codes for physics](https://www.glowscript.org/#/user/jmcewen314/folder/MyPrograms/). Just about all of this was developed in the rush to move online due to covid 19, hence, they are not polished. So far the codes are:
* projectile motion
* pendulum and double pendulum (students get a intro to chaos by examining the double pendulum)
* the mercury code is stolen from a lab write up on introducing general relativity

### mechanics I course
**notes**
{% for post in site.physics_I%}
    {% include archive-single.html %}
{% endfor %}


### waves I course
**notes**
{% for post in site.physics_III %}
    {% include archive-single.html %}
{% endfor %}


## Computer Science 101
Python resources
* [style guide](https://www.python.org/dev/peps/pep-0008/)
* [style guide for docstrings](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html)
* [profile in jupyter](https://jakevdp.github.io/PythonDataScienceHandbook/01.07-timing-and-profiling.html)


Here are some codes used in my introductory computer science course. These codes some of the topics the class covers near the end of the quarter. Generally, these topics are considered outside the scope of the class, but are good topics for students to be introduced to (but never tested on).

* [quicksort](https://github.com/JoeMcEwen/intro-computer-science-/blob/master/quicksort.ipynb)
