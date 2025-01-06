---
layout: page
title: Observational Signatures of Near-Maximal Spin
description: With Dr. Angelo Ricarte as part of the NSBP/SAO EHT Scholars Program I am working on a project identifying observational characteristics of near-maximal spin within EHT observations.
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: true
---
Supermassive black holes (SMBHs) often lie at the center of galaxies, and as they grow they modulate the evolution of their host galaxies via radiation and jet-driven feedback. Both of these processes evolve strongly with black hole spin, making it a key area of interest.

The upper limit on spin due to torque from outgoing radiation is the near-maximal value of 0.998 (as shown in Thorne 1974). However, even stronger limits have been proposed due to magnetic fields, including a commonly adopted maximum of 0.9375 (Gammie et al. 2004). With EHT we can now test these limits! Alongside my co-authors Angelo Ricarte, Ben Prather, and Hyerin Cho, I ran simulations at both spin values in search of observable differences in polarized morphology and feedback efficiency.

We ultimately found that both spin limits fit well with current EHT observations of Sgr A*. However, we found that with an edge-on view of the black hole, there's a noticeable distortion of the photon ring. In the future, as the EHT expands on land, with the ngEHT project, and in space with the BHEX mission, we hope that the near-maximal spin characteristics may become observationally accessible via the photon ring.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/image_stats.png" title="Polarimetric Stats" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The 4 plots above compare the polarimetric quantities observed for Sgr A* to those calculated for our 0.998 and 0.9375 spin simulations.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/photon_ring.png" title="Polarimetric Stats" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The image above shows the photon ring for the 0.9375 (blue) and 0.998 (red) case. We note a distortion of the photon ring in the near-maximal case.
</div>

Jet power efficiency indicates how much energy is being extracted via the jet relative to the accretion energy. These jets are incredibly powerful, and due to extraction of spin energy they may even reach over 100% efficiency. The efficiency increases noticeably for the near-maximal spin model. We find that our jet efficiency is higher in the near-maximal case than expected from previous studies. 

With the jet extracting more energy than expected, this has significant implications for the spin evolution of the black hole, as the black hole is effectively spun down. We use the spin-up parameter to characterize how fast the spin should be changing due to this energy extraction. We found that the spin-up parameter was more extreme than expect in the near-maximal case, indicating that the near-maximal spin black holes should be spun down over shorter times than previously predicted.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/power_efficiency.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spinup_parameter.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left we have a plot of jet power efficiency as a function of spin, and on the right we have a plot of the spin-up parameter as a function of spin.
</div>

<!--
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
-->
