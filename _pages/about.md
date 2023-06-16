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
Several engineering applications, e.g., in robotic and energy settings, hinge upon system identification,
control synthesis, and fault detection which often require knowledge of system states. However, due to the
presence of noise or uncertainties and inaccuracies in sensor measurements, system states are usually not
exactly known. This has motivated the design of state observers to estimate system states using uncertain
(noisy) observations and system dynamics. In particular, for bounded-error settings, i.e., when uncertainties are
set-valued and distribution-free and hence traditional filtering approaches are not applicable, set-valued observer
designs have recently gained much attention due to their simple principles and computational efficiency.

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

**This has resulted in several set-valued stable (and optimal) observer designs for different uncertainty set characterizations, such as intervals , hyperballs, and polytopes:**<br />

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

**1.2 Robust Reachability and Invariance Properties of Hybrid Distributed Systems.** <br />
I plan to extend my designed reachability analysis and state estimation framework to distributed settings, i.e., multi-agent systems, as well as to event-triggered,multi-modal, switched and hybrid distributed plants. Furthermore, I will leverage set-theoretic methods and
mixed-monotonicity to develop tractable algorithms for computing robust reach-avoid-maintain and (controlled)
invariant sets in general nonlinear networked systems, which has several applications, e.g., in solving safety
optimal control problems and path planning in complicated networked robotic settings.


---





<p style="margin-bottom:1.8cm; margin-left: 1.5cm"> </p>


##### **2. Resilient Estimation and Control of Networked CPS Subject to Uncertainty and Malicious Agents.**
---
While cyber-physical coupling in large scale and networked settings, such as smart grids, industrial robots
and swarm robotic systems, introduces new functions to control systems and improves their performance,
these systems also become exposed to new cyber vulnerabilities. Such safety-critical systems, if jeopardized
or malfunctioning, can cause serious detriment to their operators and users, as well as the controlled physical
components. Hence, a need for CPS security and for new designs of resilient estimation, attack mitigation and
control has been accentuated by incidents of attacks on CPS. Specifically, mode and false data injection are
among the most serious types of attacks on CPS, where malicious and/or strategic attackers compromise the
true mode of the system and/or inject counterfeit data signals into the sensors and actuators to cause damage.

<img src="collections/research/rtopic2/correction.gif" width="150"  align="left" hspace="30" vspace=5 />
**Simultaneous Input and State Set-Valued Observer Design for Several Classes of Nonlinear Sys-
tems: Unknown Input Decomposition.** <br />

I have designed tractable algorithms to simultaneously estimate the state and the data injection attack for several classes of nonlinear systems, assuming that the adversaries and uncertainties impact the system in the worst-case scenario, and no useful a priori knowledge, bound or distribution of the attack signals, nor any statistical characteristics for noise and disturbance signals are available. The main idea is to decompose the attack signal and the observation equation into two components, one affected and the other one unaffected by the attack signal, Further, I am leveraging the knowledge of physical system dynamics as an additional sensor to improve the estimates, which equips me with proper tools to develop attack identification approaches and to efficiently synthesize control signals to mitigate the effects of attacks in such settings.

M. Khajenejad and S.Z. Yong. Simultaneous state and unknown input set-valued observers for quadratically constrained
nonlinear dynamical systems. International Journal of Robust and Nonlinear Control, 32:6589–6622, 2022.

M. Khajenejad and S.Z. Yong. Resilient state estimation and attack mitigation in cyber-physical systems. In Security and
Resilience in Cyber-Physical Systems: Detection, Estimation and Control, pages 149–185. Springer, 2022.

M. Khajenejad and S.Z. Yong. Simultaneous mode, input and state set-valued observers with applications to resilient estimation
against sparse attacks. In 58th IEEE Conference on Decision and Control (CDC), pages 1544–1550, 2019.

M. Khajenejad and S.Z. Yong. Simultaneous mode, state and input set-valued observers for multimodal and switched nonlinear
systems. arXiv preprint arXiv:2102.10793, submitted, 2022.

<p style="margin-bottom:0.8cm; margin-left: 1.5cm"> </p>

---
<img src="collections/research/human/sparse_demo.gif" width="150"  align="left" hspace="30" vspace=10 />
**2.2 Multiple-Model: i) Bank of Mode-Matched Observers, ii) Mode Estimator, iii) Global Fusion.** <br />

I aim to develop a multiple-model (MM) framework consisting of a i) bank of mode-matched observers to return input and state estimates for the given mode, ii) a mode estimator to determine either the most likely or all compatible modes based on the observations and iii) a global fusion estimators and mode observer. The MM framework further helps in providing unified algorithms for resilient state
estimation and synthesizing H∞-optimal attack mitigation control strategies in CPS, in the presence of different
uncertainty models: stochastic (aleatoric), set-valued (epistemic), and random set uncertainties.


<p style="margin-bottom:0.8cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/human/ioc_incomplete.png"   width="150"   align="left" hspace="30" vspace=20 />
**2.3Resiliency of Partially Unknown CPS: Set-Membership Learning Meets State Estimation.** <br />
In this scenario, I plan to combine model-based set-valued estimation approaches that I have developed with set-membership
learning techniques, to learn an approximation of the system dynamics while simultaneously estimating
the system’s states and attacker’s policies.

<b>Wanxin Jin</b>,  Dana Kulic, Shaoshuai Mou, and Sandra Hirche <br />
*International Journal of Robotics Research (IJRR),* 40:848–865,
2021 <br />
[[PDF]](https://journals.sagepub.com/doi/full/10.1177/0278364921996384){:target="_blank"} /
[[Code]](https://github.com/wanxinjin/IOC-from-Incomplete-Trajectory-Observations){:target="_blank"}

<p style="margin-bottom:0.8cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/human/ioc_multiphase.gif"  width="190"  align="left" hspace="10" vspace=0 />
**2.4Distributed Resiliency in Networked CPS with Heterogeneous and Strategic Agents.** <br />
Armed with the theoretical tools that I have developed so far, I plan to study and design distributed active estimation,
fault detection and mitigation, and control policy synthesis in uncertain networked CPS, where instead of only
considering the best worst-case scenario, the agents strategically react against adversarial attackers. The idea is to apply game-theoretic techniques to model the strategic behavior of the agents, along with robust control based and intention estimation approaches to take to account worst-case scenarios and address resiliency. This, in combination with computationally efficient network communication protocols, can be characterized in the context of robust dynamic/differential networked games. In this context, agents with different intentions or
types and beliefs minimize their privately known cost, by making decisions based on different levels of bounded rationality, subject to the (partially unknown) state dynamics and control objectives, while the system state requires to remain safe despite all possible realizations of uncertainties and various possible types of attacks.

<p style="margin-bottom:1.8cm; margin-left: 1.5cm"> </p>


##### **3. Privacy-Preserving Optimization, Estimation, Verification and Control in Adversarial CPS.**

---
Data privacy and protection have become a critical concern in the management of CPS, e.g., multi-agent robotic systems, and their public trustworthiness. In such applications, malicious agents, e.g.,robots, can expand their attack surface by extracting valuable information from the physical, control, and communication components of the system, inflicting damage on the CPS and its users. So, a great effort is being devoted to design robust data-security control strategies for these systems.

<img src="collections/research/fundamental/pdp.gif"   width="160"  align="left" hspace="25" vspace=0 />
**3.1 Alternative Designs of Privacy-Preserving Mechanisms.** <br />
currently I am investigating alternative designs of privacy-preserving mechanisms, which can make the quantification of privacy and
the associated performance loss tractable and reasonable, respectively. Next, utilizing such alternative designs, my objective is to propose tractable and private estimation, verification, control and resource allocation algorithms in networked CPS. In my preliminary results, I have leveraged a robust optimization approach to propose a functional perturbation-based privacy-preserving mechanism for nonconvex distributed optimization and characterize the best accuracy that can be achieved by an optimal perturbation.

M. Khajenejad and S. Mart ́ınez. Guaranteed privacy of distributed nonconvex optimization via mixed-monotone functional
perturbations. IEEE Control Systems Letters, 7:1081–1086, 2023.

https://ieeexplore.ieee.org/abstract/document/9995727

<p style="margin-bottom:1.4cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/fundamental/safepdp.gif"  width="160"  align="left" hspace="25" vspace=0 />
**3.2Guaranteed Privacy-Preserving Mechanism Design: Unknown (Private) Deterministic Func-
tional Perturbations.** <br />
Leveraging mixed-monotone inclusion functions, I plan to propose privacy-preserving mechanisms for distributed optimiza-
tion, verification, estimation and control, which are based on deterministic functional perturbations of the local objective functions, and are proven to be stronger than probabilistic differential privacy. Subsequently, this will be used to guide the refinement of a guaranteed-private perturbation mechanism that can achieve a quantifiable accuracy via a theoretical upper bound that is shown to be independent of the chosen optimization, verification or estimation algorithms.

<p style="margin-bottom:1.4cm; margin-left: 1.5cm"> </p>


---
<img src="collections/research/fundamental/uncertainty_aware.gif"  width="160"  align="left" hspace="25" vspace=10 />
**3.3 Inherently Private Distributed Nonconvex Optimization, Estimation, Verification and Control.** <br />
Utilizing the notion of guaranteed privacy, I plan to propose inherently private distributed optimization, estimation, verification and control algorithms in adversarial networked environments, where convergence is guaranteed while valuable information is preserved. The goal is to design algorithms that are optimal in the sense that they minimize the corresponding inaccuracy of the networked CPS performance due to the perturbations, are robust against uncertainties in environment and models, and are resilient against changes in the adversary’s intention and knowledge of the system/setting.










<p style="margin-bottom:1.8cm; margin-left: 1.5cm"> </p>



