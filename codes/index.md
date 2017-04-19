---
layout: page
title: Happy coding
---

Examples of my codes/programs will be posted.

## Python
{% for post in site.categories.code_python %}
  * {{ post.date | date_to_string}} » [{{ post.title }}]({{ post.url }} "{{ post.title }}")
{% endfor %}

## Unity game engine (with C#)
Some games ...

## JavaScript
{% for post in site.categories.code_js %}
  * {{ post.date | date_to_string}} » [{{ post.title }}]({{ post.url }} "{{ post.title }}")
{% endfor %}

## Blender renders
Examples of rendered images made in Blender ...

## Others
In addition to the examples above, I have extensive experience in data analysis and programming with [Matlab](https://www.mathworks.com/products/matlab.html), [MathCAD](http://www.ptc.com/engineering-math-software/mathcad), [Mathematica](https://www.wolfram.com/mathematica/), and [Origin](http://www.originlab.com/). I also use [Lumerical](https://www.lumerical.com/tcad-products/fdtd/) and [CST Microwave Studio](https://www.cst.com/products/cstmws) for 3D-electromagnetic simulation. Regarding hardware control, [LabVIEW](http://www.ni.com/labview/) is my main tool for designing and performing instrumental control system.
