---
layout: page
title: research
permalink: /research/
description: My current research in gravitational physics.
nav: true
nav_order: 3
---

## Black Hole Perturbation Theory

My current research focuses on black hole perturbation theory. If we take a black hole, add some small perturbation, what happens? Such a simple question leads to so many open questions and difficult problems, part of the reason I love this area of gravitational physics. In terms of applications, we can use black hole perurbation theory to model the final part of gravitational wave signals from binary black hole mergers, called ringdown. 
The ringdown portion of the gravitational wave signal from a black hole binary is a unique probe for the strong-field regime of gravity. In the linear regime, ringdown can be modeled as a sum of damped sinusoids. The resulting signal is then normally expressed as $$\sum_{\ell m n} A_{\ell m n}e^{-i \omega_{\ell m n} t}$$ where $\omega_{\ell m n}$ is complex. The real part encodes the oscillation frequency of the QNM, while the imaginary part encodes the decay rate. The actual values of the QNMs are very specific, determined directly from the spin $\chi$ and mass $M$ of the remnant black hole from the BBH merger. This allows for so called "black hole spectroscopy" where one can determine the mass and spin of the remnant from its QNM spectrum. Because the QNMs are so specific, deviations from these GR QNMs can indications of deviations from GR. Looking for deviations from GR in rindown can be supplemented by the calculation of QNMs in beyond GR theories, which is one of the focuses of my work.  

Much of my work focuses on the Modified Teukolsky formalism, a methedology for computing beyond-GR quasinormal modes. It cleverly leverages techniques from degenerate perturbation theory we commonly see in quantum mechanics. For this methedology applied to a parametrized deviation from a Kerr black hole, see my work {% cite wuComputingSpectralShifts2026 %}. Due to computational limitations, this work was limited to computing QNMs linearized in the spin parameter $a$, but we hope to soon extend this to general spin which would encompass more astrophysically relevant black holes. 

---

<!-- ## Figures

You can add images like this:

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/your_figure.jpg" title="Figure caption" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

Or side by side:

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/figure1.jpg" title="Left figure" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/figure2.jpg" title="Right figure" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
-->

## References

{% bibliography --cited %}
