---
layout: page
title: Transfer learning with DeepONet
description: Brief project overview
img: assets/img/research/curiosity.jpg
importance: 3
category: work
---

The key idea behind transfer learning is learning machines that leverage knowledge gained from one task to improve accuracy and generalization in another different but related task.

Physics-based systems often require the accurate solution of PDEs that are related but differ in a certain aspect, i.e., there exists a conditional distribution mismatch.

In our latest work, we propose a novel framework which exploits information from pre-trained (source) deep neural operators (DeepONets), for fast and accurate task-specific partial differential equation (PDE) learning (target).

The key ingredient of this approach is the extraction of domain-invariant features, the embedding of conditional distributions on a reproducing kernel Hilbert space (RKHS) and the self-adaptive learning of penalizing parameters which allows adaptation between source and target domains. 

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/research/chemcam.jpg" title="Transfer learning framework" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Proposed transfer learning framework with deep operator networks. 
</div>


:paperclip: **ArXiv**: [arXiv:2204.09810v1](https://arxiv.org/abs/2204.09810)  
:raised_hands: **Co-authors**: Somdatta Goswami, Michael D. Shields and George Em Karniadakis 
:microscope: **Funding**: This project has been supported by the [U.S. Department of Energy (DOE)](https://www.energy.gov/)  

