---
layout: archive
title: "coding"
permalink: /coding/
author_profile: true
redirect_from:
  - /about
---

In truth coding was a skill I picked up late in my academic career (a mistake). In graduate school I found out just how enjoyable coding was. For me, being able to code was like simultaneously being an experimentalist and theorist. To code physics you had to understand mathematics like a theorist. Once you had your code finished you could run as many experiments as you liked (all you needed was a computer).

I primarily code in Python. I also teach a class in Python. Lately, I have been coding more in Julia (I am still learning). My first coding language was Fortran and I am still enjoy Fortran as my go to low level language. I have also done work in Matlab, C languages, and mathematica.

Here are some coding I have done recently (somewhat suitable for public display).



{% include base_path %}
{% for post in site.scientific_computing %}
  {% include archive-single.html %}
{% endfor %}
