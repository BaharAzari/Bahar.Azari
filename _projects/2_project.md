---
layout: page
title: CCL
description: Circular-Symmetric Correlation Layer.
img: assets/img/CyImage.jpg
importance: 1
category: work
---

Despite the vast success of standard planar convolutional neural networks, they are not the most efficient choice for analyzing signals that lie on an arbitrarily curved manifold, such as a cylinder. The problem arises when one performs a planar projection of these signals and inevitably causes them to be distorted or broken where there is valuable information. We propose a Circular-symmetric Correlation Layer (CCL) based on the formalism of roto-translation equivariant correlation on the continuous group $S^1 \times \mathbb{R}$, and implement it efficiently using the well-known Fast Fourier Transform (FFT) algorithm. We showcase the performance analysis of a general network equipped with CCL on various recognition and classification tasks and datasets. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/changedetec.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Probabilistic graphical model of equivariant deep state space model.
</div>

