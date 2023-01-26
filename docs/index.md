---
layout: page
title: Home
---

<br />

<p class="message">
  Accepted to ICRA 2023. Info below will be updated as the conference date approaches.
</p>

<H1>DexGrasp-1M: Dexterous Multi-finger Grasp Generation Through Differentiable Simulation</H1>
[Dylan Turpin](http://www.cs.toronto.edu/~dylanturpin/)<sup>1,2</sup>,
[Tao Zhong](https://www.taozhong.info/)<sup>1</sup>,
[Shutong Zhang]()<sup>1</sup>,
[Guanglei Zhu](https://www.linkedin.com/in/guanglei-zhu-15a797226/)<sup>1</sup>,
[Eric Heiden](https://eric-heiden.com/)<sup>2</sup>,
[Miles Macklin](mmacklin.com)<sup>2</sup>,
[Stavros Tsogkas](https://tsogkas.github.io/)<sup>1,3</sup>,
[Sven Dickinson](https://www.cs.toronto.edu/~sven/)<sup>1,3</sup>,
[Animesh Garg](https://animesh.garg.tech/)<sup>1,2</sup><br />
<small><sup>1</sup>[University of Toronto](https://web.cs.toronto.edu/) & [Vector Institute](https://vectorinstitute.ai/),
<sup>2</sup>[Nvidia](https://www.nvidia.com/en-us/research/),
<sup>3</sup>[Samsung](https://research.samsung.com/)</small>

IEEE International Conference on Robotics and Automation (ICRA) 2023

<img src="assets/teaser.jpg" alt="Teaser image with examples of grasps of a variety of objects with the Barrett, Allegro and Shadow hands." style="max-width:none; width:140%; margin-left:-20%;">

**Abstract.** <small>
Multi-finger grasping relies on high quality training
data, which is hard to obtain: human data is hard to transfer
and synthetic data relies on simplifying assumptions that reduce
grasp quality. By making grasp simulation differentiable, and
contact-dynamics amenable to gradient-based optimization,
we accelerate the search for high-quality grasps without any
simplifying assumptions. We present DexGrasp-1M: a large-scale
dataset for multi-finger robotic grasping synthesized with FastGrasp’D, a novel diffferentiable grasping simulator. DexGrasp1M contains one million training examples for three (three,
four and five-fingered) robotic hands, each with multimodal
visual inputs (RGB+depth+segmentation, available in mono
and stereo). Grasp synthesis with Fast-Grasp’D is 10x faster
than GraspIt! [1] and 20x faster than Grasp’D differentiable
simulator [2]. Our evaluations show that these grasps are more
stable and contact-rich than GraspIt! grasps regardless of the
distance threshold used for contact generation. We validate
usefulness of our data by retraining an existing vision-based
grasping pipeline on DexGrasp-1M, and showing a dramatic
increase in model performance, with predicted grasps with 30%
more contact, have a 33% higher epsilon metric and 35% lower
simulated displacement. </small>

<small>
[1] A. T. Miller and P. K. Allen, “Graspit! a versatile simulator for robotic grasping,” IEEE Robotics & Automation Magazine, 2004.  
[2] D. Turpin, L. Wang, E. Heiden, Y.-C. Chen, M. Macklin, S. Tsogkas, S. Dickinson, and A. Garg, “Grasp’d: Differentiable contact-rich grasp synthesis for multi-fingered hands,” arXiv preprint arXiv:2208.12250, 2022.
</small>

<iframe width="560" height="315" src="https://www.youtube.com/embed/1tBuHEsAf3Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br />
- Code and Dataset (available soon)
- Paper (coming soon)
- [Video walkthrough](https://youtu.be/1tBuHEsAf3Q)
