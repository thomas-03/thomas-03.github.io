---
layout: page
title: Exploring Modified Gravity
description: As part of my work with Dr. Charles F. Gammie, I am exploring modified theories of gravity within simulated images of super-massive black holes (SMBHs).
img: assets/img/Picture1.png
importance: 1
category: work
related_publications: false
---
This project is focused on exploring modified gravity theories within simulated images of SMBHs. Specifically, we look at the Einstein dilaton Gauss Bonnet (EdGB) and dynamical Chern Simons (dCS) theories, and their metrics are given to us by Dr. Nico Yunes' gravity theory group. We compare these theories to General Relativity (GR) using simulated images at 230GHz which mirror the Event Horizon Telescope observations.

My colleague Shreya Majumdar first implemented the alternative metrics within the General Relativistic Magnetohydrodynamics (GRMHD) code KHARMA. This allowed us to simulate the fluid around a SMBH within each of these theories of gravity, and both Shreya and my other colleague Vedant Dhruv then ran these simulations for a long period of time in order to ensure our initial conditions didn't influence our findings. 

From there, I use the GRMHD results within a General Relativistic Radiative Transfer (GRRT) code, IPOLE, in order to create images. To do this, I first implemented our alternative metrics within IPOLE and then created images both of the entire observed ring, and of the n=1 photon ring. Currently, I am still producing these images and once I have them all, I will be able to perform extensive analysis to note any unique observational characteristics of each theory of gravity.

{% comment %} 
To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
{% endcomment %}
