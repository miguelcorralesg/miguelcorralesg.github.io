---
layout: distill
title: KAUST-NVIDIA Hackathon 2022
date: 2022-10-06 18:00:00
description: Accelerating Scientific Applications using GPUs
authors:
  - name: Miguel Corrales
    # url: "https://en.wikipedia.org/wiki/Albert_Einstein"
    affiliations:
      name: KAUST
bibliography: post_KAUST-NVIDIA-Hackathon.bib

toc:
  - name: What is the KAUST-NVIDIA Hackathon?
  - name: The Notorious Team
  - name: Our approach
  - name: Results
  - name: Insights and comments 
  - name: Illustrative experience

---


# What is the KAUST-NVIDIA Hackathon?

As its name suggests, it's an event organized by KAUST and NVIDIA aiming to accelerate scientific applications. The hackathon started as part of the KAUST-NVIDIA workshop in 2015. In 2022, Deep Imaging Grop members participated in the 8th competition. 

# The Notorious Team

The notorious team of this year was formed by 3 amazing people: From left to rigth, [Nick Luiken (Postdoc)](https://dig.kaust.edu.sa/people/detail/nick-luiken), [Juan Romero (Ms. Student)](https://dig.kaust.edu.sa/people/detail/juan-romero-murcia), and the writer of this post [Miguel Corrales (PhD Student)](https://dig.kaust.edu.sa/people/detail/miguel-corrales). If you want to know about everyone's research, please visit the hyperlinks. 

{% include figure.html path="assets/img/Hackathon_KAUST/hackathon_kaust.jpeg" title="DIG Hackathon Team" class="KAUST-NVIDIA Hackathon" %}

# Our approach

The problem to solve lies on Juan's research <d-cite key="doi:10.1190/image2022-3737749.1"></d-cite>. The main challenge is related to a segmentation step, where many independent bisection problems are needed to solve, which makes a perfect setting to optimize the running time performance using GPUs. 


# Results

After one day and a half, the team succesfully levaraged the capabilities of the algorithm. Roghly speaking, the team speed up the computation by 80 times. The code of the hackathon could be find in the following[`repository`](https://github.com/DIG-Kaust/HPC_Hackathon_DIG)

{% include figure.html path="assets/img/Hackathon_KAUST/logo_hackathon.png" title="Github Hackathon" class="KAUST-NVIDIA Hackathon" %}



# Insights and comments 

It was such a wonderful experience to participate in this event. Many thanks to the organizers from KAUST and NVIDIA, and of course, for all the support from the mentors who constantly help along this short journey. Luckily, the team was awarded the best team in terms of computing performance.  

{% include figure.html path="assets/img/Hackathon_KAUST/hackathon_kaust_2.jpeg" title="Price" class="KAUST-NVIDIA Hackathon" %}

# Illustrative experience
This was a post regarding the KAUST-NVIDIA Hackathon, here it is a illustrative summary related to our teamwork.   

"It's gonna be easy, probably just putting our code on numba and cuda", that is what we thought :stuck_out_tongue_winking_eye: :stuck_out_tongue_winking_eye: :stuck_out_tongue_winking_eye:
{% include figure.html path="assets/img/Hackathon_KAUST/monkey-ambulance.gif" title="Summary Hackathon" class="KAUST-NVIDIA Hackathon" %}
