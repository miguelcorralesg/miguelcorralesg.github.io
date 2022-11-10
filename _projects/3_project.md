---
layout: distill
title: Seismic PnP
description: Plug and Play method for post-stack seismic inversion
img: assets/img/PnP_logo.png
importance: 3
category: work
date: 2022-10-31
authors:
  - name: Miguel Corrales
    # url: "https://en.wikipedia.org/wiki/Albert_Einstein"
    affiliations:
      name: KAUST

bibliography: project_pnp_seismic.bib
toc:
  - name: Project description
  - name: Status and Results 
  - name: Publications

---

Welcome to the Seismic PnP project :v: :sunglasses:

This project was born during the [Machine Learning in Geoscience Course at KAUST by Prof. Matteo Ravasi](https://github.com/DIG-Kaust/MLgeoscience). It was developed together with my friend and colleague [Juan Romero](https://dig.kaust.edu.sa/people/detail/juan-romero-murcia). 


# Project description

The idea of this work is based on the concept of using Plug-and-Play (PnP) regularization, which suggests reinterpreting the effect of the regularizer as a denoising problem. Due to this denoising step, various statistical and deep denoisers become attractive. For this work, DnCNN (gaussian blind denoiser) and DRUNet (non-blind gaussian denoisers) are used to evaluate if we can show superior results compared to state-of-the-art regularization techniques on post-stack seismic inversion such as TV regularization. It is important to emphasize that we are not denoising the input data; the denoising is performed along the Primal-Dual algorithm <d-cite key="eage:/content/papers/10.3997/2214-4609.2022616015"></d-cite>. 


# Status and Results 

This new approach presented is able to outperfom the state-of-the art regularization techniques. More detailed information about the work could be found on the publication. 

{% include figure.html path="assets/img/project_seismic_pnp/results.png" title="Results PnP Seismic" class="PnP Seismic Project" %}

# Publications

More details about the project could be found on the following publication:
[PnP Seismic](https://www.earthdoc.org/content/papers/10.3997/2214-4609.2022616015). 