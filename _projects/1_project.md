---
layout: page
title: Tidal Reconstruction
description: Cosmic Tidal Reconstruction In Redshift Space
img: assets/img/Cor2D_5T.jpg
importance: 1
category: work
---

Tidal reconstruction exploits the small-scale anisotropic distortions of mass distributions to retrieve the large-scale structure of the universe, which has the potential to conduct multi-tracer analysis with future sky surveys. However, the redshift space distortion (RSD) is likely to affect the reconstruction results by bringing extra distortions to the small-scale structure. In this work we explore the performance of the tidal reconstruciton in the redshift space using halo fields. We bring up a model to explain the full-shear tidal reconstructed results.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Slice_5T_XZ.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Slice_2T_XZ.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

 The left panel shows the 2-D Slice of the reconstructed density fields on x-z plane using full-shear term tidal reconstruction. While the right panel shows the one using transverse-shear term tidal reconstruction. In redshift space, the full-shear tidal reconstruction result is blurred by the small-scale distortion of mass distribution, while the transverse-shear term tidal reconstruction result remains almost the same as that in the real space. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/R2DBin_PhotoZ_5T.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The effects of the RSD effect on tidal reconstruction is similar to a small photo-Z error as seen in the above figure.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TN2DBin_RSD_5T.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Additionally, we find that the propagator of the tidal reconstruction result has a quadratic form
$$
    T(k) = b_0(1 - f\mu^2).
$$
This result will help us to extract the information of large-scale structure of the reconstructed density field in future sky surveys.