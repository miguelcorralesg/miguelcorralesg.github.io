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
  - name: Publications


---

Welcome to the RockAVO project :metal: :metal: :metal:

Here the reader will find everything related to direct petrophysical inversion from pre-stack seismic data (idea, published work, current and future work). 


# Project description

**RockAVO** lies on the Seismic Reservoir Characterization framework. The main objective of it is to retrieve the petrophysical properties of the subsurface, such as porosity, shale content, and water saturation, directly from pre-stack seismic data. 

## What is new about it? 

The novelty of this work is based on the following points: 
  - Direct inversion from pre-stack data to petrophysical properties. This means no cascade approach (from pre-stack to elastic properties, then to petrophysical properties) or joint approach. 
  - RockAVO performs two steps on modeling (Rock physics model and Zoeppritz) and just one step on inversion.
  - RockAVO can handle and benefit from the information of higher angles compared to any linearized operator.
  - It is a data-driven method that uses well-log information as apriori knowledge of the subsurface. 

# Status of the Project

Until the last edition of this post, we have proven the applicability of the method on Sytethic data using the Smeaheia reservoir model. The numerical results show that porosity is the best-inverted rock property, followed by water saturation and clay content. Moreover, the method is also applicable in reservoir monitoring to invert time-lapse, pre-stack seismic data for water saturation changes <d-cite key="eage:/content/papers/10.3997/2214-4609.202210178"></d-cite>.

Similarly, we have proposed a Bayesian framework (Bayesian RockAVO) <d-cite key="doi:10.1190/image2022-3745255.1"></d-cite> to capture the uncertainty of the petrophysical coefficients. For this part, we have used Generative Adversarial Networks to generate geologically consistent priors. Although the method shows promising results, the challenge remains in the overall computational cost and the need for an extensive dataset to avoid mode collapse in the training process.


# What is coming? 

Right now, the **RockAVO** method is being tested on field data. Results regarding this implementation are coming soon!

# Publications 

As part of this project, we have presented two conference papers.  You can have direct access to the following links. 

  - [`Data-Driven, Direct Rock-Physics Inversion of Pre-Stack Seismic Data`](https://www.earthdoc.org/content/papers/10.3997/2214-4609.202210178)
  - [`Bayesian RockAVO: Direct petrophysical inversion with hierarchical conditional GANs`](https://onepetro.org/SEGAM/proceedings/IMAGE22/1-IMAGE22/D011S117R003/512785)
