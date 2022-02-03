---
layout: page
title: EqDDM:
description: An SO(3) equivariant deep dynamical model (EqDDM) for motion prediction.
img: assets/img/pend.jpg
importance: 1
category: work
---

Learning representations through deep generative modeling is a powerful approach for dynamical modeling to discover the most simplified and compressed underlying description of the data, to then use it for other tasks such as prediction. Most learning tasks have intrinsic symmetries, i.e., the input transformations leave the output unchanged, or the output undergoes a similar transformation. The learning process is, however, usually uninformed of these symmetries. Therefore, the learned representations for individually transformed inputs may not be meaningfully related. In this paper, we propose an SO(3) equivariant deep dynamical model (EqDDM) for motion prediction that learns a structured representation of the input space in the sense that the embedding varies with symmetry transformations. EqDDM is equipped with equivariant networks to parameterize the state-space emission and transition models. We demonstrate the superior predictive performance of the proposed model on various motion data. More to come later ...

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pgm.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Probabilistic graphical model of equivariant deep state space model.
</div>

