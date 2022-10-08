---
layout: page
title: Home
---

<br />

<p class="message">
  This page will be updated as the ECCV22 conference date approaches.
</p>

<H1>Grasp'D: Differentiable Contact-rich Grasp Synthesis for Multi-fingered Hands</H1>
[Dylan Turpin](http://www.cs.toronto.edu/~dylanturpin/)<sup>1,2,3</sup>,
[Liquan Wang](https://www.linkedin.com/in/liquan-wang-a37634196)<sup>1,2,3</sup>,
[Eric Heiden](https://eric-heiden.com/)<sup>3</sup>,
[Yun-Chun Chen](https://yunchunchen.github.io/)<sup>1,2</sup>,
[Miles Macklin](mmacklin.com)<sup>3</sup>,
[Stavros Tsogkas](https://tsogkas.github.io/)<sup>4</sup>,
[Sven Dickinson](https://www.cs.toronto.edu/~sven/)<sup>1,2,4</sup>,
[Animesh Garg](https://animesh.garg.tech/)<sup>1,2,3</sup><br />
<small><sup>1</sup>[University of Toronto](https://web.cs.toronto.edu/)
<sup>2</sup>[Vector Institute](https://vectorinstitute.ai/),
<sup>3</sup>[Nvidia](https://www.nvidia.com/en-us/research/),
<sup>4</sup>[Samsung](https://research.samsung.com/)</small>

European Conference on Computer Vision (ECCV) 2022

<img src="assets/teaser.gif" alt="Example optimization trajectories for grasps created with the Graspd pipeline.">

**Abstract.** <small>The study of hand-object interaction requires generating viable grasp poses for high-dimensional multi-finger models, often relying
on analytic grasp synthesis which tends to produce brittle and unnatural
results. This paper presents Grasp’D, an approach for grasp synthesis
with a differentiable contact simulation from both known models as
well as visual inputs. We use gradient-based methods as an alternative
to sampling-based grasp synthesis, which fails without simplifying assumptions, such as pre-specified contact locations and eigengrasps. Such
assumptions limit grasp discovery and, in particular, exclude high-contact
power grasps. In contrast, our simulation-based approach allows for stable,
efficient, physically realistic, high-contact grasp synthesis, even for gripper morphologies with high-degrees of freedom. We identify and address
challenges in making grasp simulation amenable to gradient-based optimization, such as non-smooth object surface geometry, contact sparsity,
and a rugged optimization landscape. Grasp’D compares favorably to
analytic grasp synthesis on human and robotic hand models, and resultant
grasps achieve over 4× denser contact, leading to significantly higher
grasp stability.</small>

<iframe width="560" height="315" src="https://www.youtube.com/embed/tkl_lywZ94o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br />
- Code (coming soon)
- Paper (coming soon)
- [arXiv](https://arxiv.org/abs/2208.12250)
- [Video walkthrough](https://www.youtube.com/watch?v=tkl_lywZ94o)
