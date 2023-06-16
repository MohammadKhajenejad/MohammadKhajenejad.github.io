---
layout: about
title: about
permalink: /
description: 

profile:
  align: right
  image: square.jpeg
  #image: mohammad.png
  address: 


news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page



---

## **Mohammad Khajenejad** 

<p style="margin-bottom:0.8cm; margin-left: 0.5cm"> </p>


**Postdoctoral Researcher** at UC San Diego [Jacobs School of Engineering](https://jacobsschool.ucsd.edu/){:target="_blank"}, working with [Professor Sonia Martinez](https://jacobsschool.ucsd.edu/people/profile/sonia-martinez){:target="_blank"}.


I obtained my Ph.D. from the [Fulton School of Engineering](https://engineering.asu.edu/){:target="_blank"}, [Arizona State Universitiy](https://www.asu.edu/){:target="_blank"} in 2021, where I worked with [Professor Sze Zheng Yong](https://coe.northeastern.edu/people/yong-sze-zheng/){:target="_blank"} on guaranteed reachability analysis and state estimation of uncertain nonlinear systems, as well as resilient estimation in cyber-physical systems subject to different uncertainty models and malicious agents/attackers. My Ph.D. thesis: " Set-Valued Methods for Reachability Analysis and Estimation of Nonlinear Dynamical Systems" won the prestigious 2021 ASU Dean's Dissertation Award. 


**News:** 
Won the DAAD AInet Fellowship for the Postdoc-NeT-AI in Cyber-Physical Systems (Sep 2022)


**News:** 
Our book chapter Resilient State Estimation and Attack Mitigation in Cyber-Physical Systems was published in Security and Resilience in Cyber-Physical Systems (Aug 2022)

**News:** 
Our IEEE TAC Paper has been accepted (June 2022)

**News:** 
We won the award for Basic and Applied Scientific Research (W911NF-17-S-0003-AI2C) for the research proposal "Distributed Learning for Multi-Agent Cooperative Control" (June 2022)



<p style="margin-bottom:1.2cm; margin-left: 1.5cm"> </p>



<center>
    <a href = "mailto:mkhajenejad@ucsd.edu" target="_blank"> 
    <img src="assets/img/platform_icon/email.gif" width="35" target="_blank"> </a>   &nbsp;&nbsp;&nbsp;
<a href = "https://scholar.google.com/citations?user=1i8Te2sAAAAJ&hl=en" target="_blank"> 
    <img src="assets/img/platform_icon/scholar.png" width="35" target="_blank"></a>   &nbsp;&nbsp;&nbsp;

</center>


<br />




-----
#### **My Research**

A large number of <strong>cyber-physical systems (CPS)</strong>, such as unmanned aircraft systems, smart power grids, industrial robots, intelligent robotic systems, autonomous vehicles, transportation networks, air traffic systems and supply chains, are characterized as collections of interacting subsystems with ambiguous or unknown models, and are acted upon by multiple decision makers with hard-to-model and heterogeneous intentions and behaviors(malicious, competitive, cooperative, stubborn). Such large scale systems are present in all societal sectors, from critical infrastructure, manufacturing and agriculture to service sectors.
Motivated by this, my goal is to design <strong>distributed, tractable, robust, safe and private</strong> sequential decision-making algorithms in multi-modal and switched cyber-physical systems that are compromised by adversarial or malicious agents, and are subject to various forms of real-world uncertainties. 
To accomplish this objective, I will leverage <strong>model-based control-theoretic</strong>, as well as <strong>data-driven learning approaches</strong> to develop:
- **tractable and computationally efficient algorithms for reachability analysis,** 
- **state and model estimation,**
- **attack identification and mitigation,**
- **verification and control synthesis in (partially) unknown networked cyber-physical systems.**



<p style="margin-bottom:1.2cm; margin-left: 1.5cm"> </p>


-----
<center>
    <h4><strong>Highlighted Research and Publications</strong></h4>
</center>


<p style="margin-bottom:1.2cm; margin-left: 1.5cm"> </p>


##### **1. Guaranteed Reachability Analysis and State Estimation of Uncertain Nonlinear Systems**
---

<img src="collections/research/rtopic1/rtopic1.png"  width="140"  align="left" hspace="30" vspace=0 />

**1.1 Constrained Reachability Analysis & Set-Valued State Estimation for Constrained Uncertain
Systems.** <br />
I have leveraged system properties such as mixed-monotonicity to propose a novel class of bounding
functions, i.e, Tight Remainder-Form Decomposition Functions, that can be tractably computed. This enables us
to obtain tight reachable sets (tubes) of state trajectories of a very broad class of non-smooth and discontinuous
nonlinear systems subject to state constraints, observations and set-valued uncertainties, and facilitates
designing efficient set-inversion algorithms.

M. Khajenejad and S.Z. Yong. Tight remainder-form decomposition functions with applications to constrained reachability
and guaranteed state estimation. in IEEE Transaction on Automatic Control, accepted, 2023.
https://ieeexplore.ieee.org/abstract/document/10057091

M. Khajenejad, F. Shoaib, and S.Z. Yong. Guaranteed state estimation via indirect polytopic set computation for nonlinear
discrete-time systems. In 60th IEEE Conference on Decision and Control (CDC), pages 6160–6167, 2021.
https://ieeexplore.ieee.org/abstract/document/9683626

This has resulted in several set-valued stable (and optimal) observer designs for different uncertainty set characterizations, such as intervals , hyperballs, and polytopes:

M. Khajenejad, F. Shoaib, and S.Z. Yong. Interval observer synthesis for locally lipschitz nonlinear dynamical systems via
mixed-monotone decompositions. In 2022 American Control Conference (ACC), pages 2970–2975. IEEE, 2022.
https://ieeexplore.ieee.org/abstract/document/9867741

M. Khajenejad and S. Z. Yong. H∞-optimal interval observer synthesis for uncertain nonlinear dynamical systems via mixed-
monotone decompositions. IEEE Control Systems Letters, 6:3088–3013, 2022.
https://ieeexplore.ieee.org/abstract/document/9790824

T. Pati, M. Khajenejad, S.P. Daddala, and S.Z. Yong. L1-robust interval observer design for uncertain nonlinear dynamical
systems. IEEE Control Systems Letters, 6:3475–3480, 2022.
https://ieeexplore.ieee.org/abstract/document/9803272

M. Khajenejad and S.Z. Yong. Simultaneous input and state set-valued H∞-observers for linear parameter-varying systems.
In American Control Conference (ACC), pages 4521–4526, 2019.
https://ieeexplore.ieee.org/abstract/document/8814909

M. Khajenejad, F. Shoaib, and S. Z. Yong. Guaranteed state estimation via direct polytopic set computation for nonlinear
discrete-time systems. IEEE Control Systems Letters, 6:2060–2065, 2021.
https://ieeexplore.ieee.org/abstract/document/9683626

<p style="margin-bottom:1.0cm; margin-left: 1.5cm"> </p>

---
<img src="collections/research/manipulation/cartpole_wall_crop.gif"  title="SafePDP" width="150"  align="left" hspace="25" vspace=0 />
**Learning Linear Complementarity Systems** <br />
<b>Wanxin Jin</b>, Alp Aydinoglu, Mathew Halm, and Michael Posa<br />
*Learning for Dynamics and Control (L4DC)*, 2022 <br />
[[PDF]](https://arxiv.org/abs/2112.13284){:target="_blank"} / 
[[Code]](https://github.com/wanxinjin/Learning-LCS){:target="_blank"}


---
<img src="collections/research/manipulation/ball_falling.png"  title="SafePDP" width="150"  align="left" hspace="25" vspace=0 />
**Adaptive Barrier Smoothing for First-Order Policy Gradient with Contact Dynamics** <br />
 Shenao Zhang, <b>Wanxin Jin</b>, Zhaoran Wang<br />
*International Conference on Machine Learning (ICML)*, 2023 <br />
[PDF coming soon] / 
[Code coming soon] / 
[Video coming soon]




<p style="margin-bottom:1.8cm; margin-left: 1.5cm"> </p>


##### **2. Robot Learning with Human-On-The-Loop**
---
<img src="collections/research/human/correction.gif" width="150"  align="left" hspace="30" vspace=5 />
**Learning from Human Directional Corrections** <br />
<b>Wanxin Jin</b>, Todd D Murphey, and Shaoshuai Mou<br />
*IEEE Transactions on Robotics (T-RO)*, 2022 <br />
[[PDF]](https://arxiv.org/abs/2011.15014){:target="_blank"} /
[[Code]](https://github.com/wanxinjin/Learning-from-Directional-Corrections){:target="_blank"} /
[[Videos]](https://youtu.be/Mwlwt055Tgg){:target="_blank"}

<p style="margin-bottom:0.8cm; margin-left: 1.5cm"> </p>

---
<img src="collections/research/human/sparse_demo.gif" width="150"  align="left" hspace="30" vspace=10 />
**Learning from Sparse Demonstrations** <br />
<b>Wanxin Jin</b>, Todd D Murphey, Dana Kulic, Neta Ezer, and Shaoshuai Mou<br />
*IEEE Transactions on Robotics (T-RO)*, 2022<br />
[[PDF]](https://arxiv.org/abs/2008.02159){:target="_blank"}/
[[Code]](https://github.com/wanxinjin/Learning-from-Sparse-Demonstrations){:target="_blank"} /
[[Videos]](https://youtu.be/BYAsqMxW5Z4){:target="_blank"}


<p style="margin-bottom:0.8cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/human/ioc_incomplete.png"   width="150"   align="left" hspace="30" vspace=20 />
**Inverse Optimal Control from Incomplete Trajectory Observations** <br />
<b>Wanxin Jin</b>,  Dana Kulic, Shaoshuai Mou, and Sandra Hirche <br />
*International Journal of Robotics Research (IJRR),* 40:848–865,
2021 <br />
[[PDF]](https://journals.sagepub.com/doi/full/10.1177/0278364921996384){:target="_blank"} /
[[Code]](https://github.com/wanxinjin/IOC-from-Incomplete-Trajectory-Observations){:target="_blank"}

<p style="margin-bottom:0.8cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/human/ioc_multiphase.gif"  width="190"  align="left" hspace="10" vspace=0 />
**Inverse Optimal Control for Multiphase cost functions** <br />
<b>Wanxin Jin</b>, Dana Kulic, Jonathan  Lin, Shaoshuai Mou, and Sandra Hirche <br />
*IEEE Transactions on Robotics (T-RO)*, 35(6):1387–1398,
2019 <br />
[[PDF]](https://ieeexplore.ieee.org/document/8778698){:target="_blank"} / 
[[Code]](https://github.com/adaptivesystemslab/ioc){:target="_blank"}




<p style="margin-bottom:1.8cm; margin-left: 1.5cm"> </p>


##### **3. Fundamental Research: Bridging Control with Machine Learning**

---
<img src="collections/research/fundamental/pdp.gif"   width="160"  align="left" hspace="25" vspace=0 />
**Pontryagin Differentiable Programming: An End-to-End Learning and Control Framework** <br />
<b>Wanxin Jin</b>, Zhaoran Wang, Zhuoran Yang, and Shaoshuai Mou<br />
*Advances in Neural Information Processing Systems (NeurIPS),*  2020 <br />
[[PDF]](https://papers.nips.cc/paper/2020/file/5a7b238ba0f6502e5d6be14424b20ded-Paper.pdf){:target="_blank"} /
[[Code]](https://github.com/wanxinjin/Pontryagin-Differentiable-Programming){:target="_blank"} /
[[Videos]](https://slideslive.com/38936632){:target="_blank"}

<p style="margin-bottom:1.4cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/fundamental/safepdp.gif"  width="160"  align="left" hspace="25" vspace=0 />
**Safe Pontryagin Differentiable Programming** <br />
<b>Wanxin Jin</b>, Shaoshuai Mou, and George J. Pappas<br />
*Advances in Neural Information Processing Systems (NeurIPS)*, 2021<br />
[[PDF]](https://arxiv.org/abs/2105.14937){:target="_blank"} / 
[[Code]](https://github.com/wanxinjin/Safe-PDP){:target="_blank"} / 
[[Videos]](https://slideslive.com/38968248){:target="_blank"}

<p style="margin-bottom:1.4cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/fundamental/uncertainty_aware.gif"  width="160"  align="left" hspace="25" vspace=10 />
**Robust Safe Learning and Control in Unknown Environments: An Uncertainty-Aware Control Barrier Function Approach** <br />
Jiacheng Li, Qingchen Liu, <b>Wanxin Jin</b>, Jiahu Qin, and Sandra Hirche<br />
Submitted to *IEEE Robotics and Automation Letters (RA-L)*, under review, 2023<br />
[PDF coming soon] / 
[Code coming soon] / 
[Video coming soon]

---
<img src="collections/research/fundamental/keyidea.png"  width="160"  align="left" hspace="25" vspace=20 />
**Enforcing Hard Constraints with Soft Barriers: Safe-driven Reinforcement Learning in Unknown Stochastic Environments** <br />
Yixuan Wang, Simon Sinong Zhan, Ruochen Jiao, Zhilu Wang, <b>Wanxin Jin</b>, Zhuoran Yang, Zhaoran Wang, Chao Huang, Qi Zhu<br />
*International Conference on Machine Learning (ICML)*,  2023<br />
[[PDF]](https://arxiv.org/abs/2209.15090){:target="_blank"}    / 
[Code coming soon] / 
[Video coming soon]







<p style="margin-bottom:1.8cm; margin-left: 1.5cm"> </p>



