---
layout: distill
title: EAGE Hackathon 2022
date: 2022-06-06 18:00:00
description: Explainable Artificial Intelligence (XAI)
authors:
  - name: Miguel Corrales
    # url: "https://en.wikipedia.org/wiki/Albert_Einstein"
    affiliations:
      name: KAUST
bibliography: post_KAUST-NVIDIA-Hackathon.bib

toc:
  - name: EAGE Hackathon 2022
  - name: The SnorIAX Team
  - name: Our approach and results
  - name: Insights and comments 
  - name: Interview 

---

Hello everybody, welcome to a new post.  It is related to my first participation in a Hackathon in Madrid-Spain :es: as part of the EAGE 2022 Annual exhibition. 

# EAGE Hackathon 2022

The topic of this year was Explainable Artificial Intelligence. The primary purpose was to apply techniques that allow explaining what a model is doing (mostly related to the geoscience aspect). Most of the time, machine learning models are considered a `black box` where the user has no idea what is happening. In this context, having access or knowledge of what the model 'is looking at' is helpful to determine if it is following some physical insights or what an expert in the area normally will do. More importantly, to know if it considers the `correct features`. 


# The SnorIAX Team

In this participation, the team was composed of 4 KAUST students.  From left to right, [Miguel Corrales](https://dig.kaust.edu.sa/people/detail/miguel-corrales),[Abdullah Alali](https://swagroup.kaust.edu.sa/people/detail/abdullahalali), [Danilo Chamorro](https://dig.kaust.edu.sa/people/detail/danilo-chamorro-riascos), and [Randy Harsuko](https://swagroup.kaust.edu.sa/people/detail/mochammad-randy-caesario-harsuko).

{% include figure.html path="assets/img/Hackathon_EAGE/snorlax_team.png" title="SnorIAX Hackathon Team" class="EAGE Hackathon 2022" %}

Our team was named SnorIAX, which intends to combine my preference for Pokemon and Explainable AI. It was a fun argument at that moment; please do not judge me :smiley:. Also, the logo looks so cool :sunglasses:

{% include figure.html path="assets/img/Hackathon_EAGE/logo_snorlax.png" title="SnorIAX Logo" class="EAGE Hackathon 2022" %}


# Our approach and results

Our work mainly consisted of two approaches to explain what 'the network is looking at'. We focused our first example on the salt segmentation problem, where we added attention maps in the output gates of a U-net.

{% include figure.html path="assets/img/Hackathon_EAGE/salt_segmentation.gif" title="UNet for salt segmentation with attention maps" class="EAGE Hackathon 2022" %}

 In addition, we implemented saliency and occlusion attributes in the Discriminator of a porous media generation problem using Generative Adversarial Networks (GANs). 

 {% include figure.html path="assets/img/Hackathon_EAGE/saliency.gif" title="Saliency in Discriminator" class="EAGE Hackathon 2022" %}

  {% include figure.html path="assets/img/Hackathon_EAGE/occlusion.gif" title="Occlusion in Discriminator" class="EAGE Hackathon 2022" %}

This briefly describes our team's results during these two exhaustive days. If you would like to know more details about our implementation and from the other groups, please feel free to visit the [`GitHub site of the competition`](https://github.com/EAGE-Annual-Hackathon/SnorIAX)

# Insights and comments 

Being the first time participating in the Hackathon, I found it a fantastic experience. The first day was a bit stressful due to the problem's setup and time management. I want to thank all the sponsors, organizers, and mentors. It was such an honor to be selected as the BEST IN SHOW. What a fantastic day to close our first participation. :sunglasses: :sunglasses: :sunglasses:

{% include figure.html path="assets/img/Hackathon_EAGE/price_photo.jpeg" title="Price" class="KAUST-NVIDIA Hackathon" %}


# Interview
Thanks a lot to Ruslan Miftakhov, we have such a great time on it.

<p align='center'>
<iframe width="560" height="315" src="https://www.youtube.com/embed/AsOCNFj60CE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

