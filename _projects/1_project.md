---
layout: distill
title: RockAVO
description: Data-driven approach for direct petrophysical inversion from pre-stack seismic data.
img: assets/img/publication_preview/rockavo_1.gif
importance: 1
category: work
date: 2022-10-31

authors:
  - name: Miguel Corrales
    # url: "https://en.wikipedia.org/wiki/Albert_Einstein"
    affiliations:
      name: KAUST

bibliography: project_rockavo.bib

toc:
  - name: Project description
  - name: Status of the Project
  - name: What is coming?
  - name: Publication


---

The inversion of petrophysical parameters from seismic data represents a fundamental step in the reservoir characterization framework. However, the non-linearity of the rock-physics models that relate petrophysical properties to seismic pre-stack amplitudes makes such an inversion challenging. We propose a hybrid approach, where data-driven basis functions are learned from well-logs to directly link band-limited petrophysical reflectivities to pre-stack seismic data. Petrophysical parameters are subsequently obtained by means of regularized post-stack seismic inversion. By performing two modeling steps at training time and a single inversion step at inference time, our method aims to be more efficient and robust than conventional two-step inversion workflows. The proposed method is tested on a synthetic dataset from the Smeaheia reservoir model. Numerical results show that porosity is the best-inverted rock property, followed by water saturation and clay content. Moreover, the method is shown to be also applicable in the context of reservoir monitoring to invert time-lapse, pre-stack seismic data for water saturation changes.
