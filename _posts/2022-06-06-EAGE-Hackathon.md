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
  - name: Illustrative experience

---

Hello everybody, welcome to a new post.  This post is related to my first participation in a Hackathon in Madrid, Spain, as part of the EAGE 2022 Annual exhibition. 

# EAGE Hackathon 2022

The topic of this year was Explainable Artificial Intelligence. The primary purpose was to apply techniques that allow explaining what a model is doing (mostly related to the geoscience aspect). Most of the time, machine learning models are considered a `black box` where the user has no idea what is happening. In this context, having access or knowledge of what the model 'is looking at' is helpful to determine if it is following some physical insights or what an expert in the area normally will do. More importantly, to know if it considers the `correct features`. 


# The SnorIAX Team

In this participation, the team was conformed of 4 KAUST students.  From left to right, [Miguel Corrales](https://dig.kaust.edu.sa/people/detail/miguel-corrales), Abdullah Alali, Danilo Chamorro, Randy Harsuko.


{% include figure.html path="assets/img/Hackathon_EAGE/snorlax_team.png" title="SnorIAX Hackathon Team" class="EAGE Hackathon 2022" %}

Our team was named SnorIAX which intends to combine my preference for Pokemon and Explainable AI. It was a fun argument at that moment, please do not judge me :smiley:. Also the logo looks so cool :sunglasses:

{% include figure.html path="assets/img/Hackathon_EAGE/logo_snorlax.png" title="SnorIAX Logo" class="EAGE Hackathon 2022" %}


# Our approach and results

Our work mainly consisted of two approaches to explain what 'the network is looking at'. We focused our first example on the salt segmentation problem, where we added attention maps in the output gates of a U-net.

{% include figure.html path="assets/img/Hackathon_EAGE/salt_segmentation.mp4" title="UNet for salt segmentation with attention maps" class="EAGE Hackathon 2022" %}

 In addition, we implemented saliency and occlusion attributes in the Discriminator of a porous media generation problem using Generative Adversarial Networks (GANs). 


 {% include figure.html path="assets/img/Hackathon_EAGE/saliency.mp4" title="Saliency in Discriminator" class="EAGE Hackathon 2022" %}

  {% include figure.html path="assets/img/Hackathon_EAGE/oclussion.mp4" title="Occlusion in Discriminator" class="EAGE Hackathon 2022" %}

This briefly describes our team's results during these two exhaustive days. If you would like to know more details about our implementation and from the other groups, please feel free to visit the [`GitHub site of the competition`](https://github.com/EAGE-Annual-Hackathon/SnorIAX)

# Insights and comments 

<!-- It was such a wonderful experience to participate in this event. Many thanks to the organizers from KAUST and NVIDIA, and of course, for all the support from the mentors who constantly help along this short journey. Luckily, the team was awarded the best team in terms of computing performance.  

{% include figure.html path="assets/img/Hackathon_KAUST/hackathon_kaust_2.jpeg" title="Price" class="KAUST-NVIDIA Hackathon" %} -->

# Illustrative experience
<!-- This was a post regarding the KAUST-NVIDIA Hackathon, here it is a illustrative summary related to our teamwork.   

"It's gonna be easy, probably just putting our code on numba and cuda", that is what we thought :stuck_out_tongue_winking_eye: :stuck_out_tongue_winking_eye: :stuck_out_tongue_winking_eye:
{% include figure.html path="assets/img/Hackathon_KAUST/monkey-ambulance.gif" title="Summary Hackathon" class="KAUST-NVIDIA Hackathon" %} -->
