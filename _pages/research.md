---
layout: archive
title: # "CV"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Personalized computational cardiac models play a unique role in modern cardiology towards the ‘digital twins’ of the human heart. By integrating patients’ information, the knowledge of physiology, pathology and physical laws of soft tissue mechanics, solved with modern numerical methods, computational cardiology can potentially improve patient risk assessment and design new treatments.  
<!-- ![Alt Text](http://haogao.github.io/images/hg_multiscale_multiphysics.png) -->

<p align="center">
  <img src="http://haogao.github.io/images/hg_multiscale_multiphysics.png" alt="Multiscale Model" style="width:60%; max-width:1000px;">
</p>


### Immersed boundary methods in cardiac mechanics
There has been longstanding interest in modelling the complex interactions between the cardiac blood flow and the myocardial wall dynamics through fluid-structure interactions (FSI). Various cardiac FSI models have been developed using the immersed boundary method, with applications spanning a range of organs, including mitral valve, myocardial infarction, myocardial perfusion, and the four-chamber heart dynamics. 
![Alt Text](http://haogao.github.io/images/vector_MRI.gif)

### The Heart Models
![Alt Text](http://haogao.github.io/images/hg_lv.png)

### The Valve Models
![Alt Text](http://haogao.github.io/images/hg_valve.png)


### The whole-heart function


### Personalized modelling (constitutive modelling, parameter estimation, and clinical application)
One remaining challenge is the personalization of these models for real-time clinical decision-making. For example, different patients have different sets of biophysical parameters that can affect the quantities of interest but require thousands of simulations of those models, which can be very computationally expensive. Also quantification of the uncertainties associated with inferred parameters from sparse measurements usually is missing from the current modelling approaches. 
![Alt Text](http://haogao.github.io/images/hg_personalisation.png)


### Soft tissue growth and remodelling 
Computational modelling of cardiac growth and remodelling (G&R) has shown high promise to provide insight into heart disease management when mechanistic understandings are quantified between biomechanical factors and underlying cellular adaptation processes. The kinematic growth theory has been dominantly used to phenomenologically describe the biological G&R process but neglecting underlying cellular mechanisms. We have developed a constrained mixture-based G&R model with updated reference by taking into account different mechanobiological processes in the ground matrix, myocytes and collagen fibres.
![Alt Text](http://haogao.github.io/images/hg_gr.png)


### Poroelasticity in cardiac perfusion
Myocardial perfusion plays a pivotal role in maintaining normal pump function. However the development of a comprehensive myocardial perfusion model remains particularly challenging as it requires the incorporation of complex interactions across different spatial scales and physical domains,  To model myocardial perfusion, it is also necessary to couple the coronary flow with the myocardial mechanics. Here, we have developed a poroelastic framework with in the immsered boundary method, a three-phase approach including the myocaridum, the coronary flow in large arteries and the perfusion within the microvessel network approaximated by Darcy flow, and the ventricular flow. 
![Alt Text](http://haogao.github.io/images/hg_perfusion.png)

### Statistical emulation and scientific machine learning in complex systems
The computational costs of parameter estimation in cardiac models are prohibitive, thus not practical for real-time clinical decision support systems, whihc is due to the need to repeatedly solve the mathematical equations numerically during an iterative optimization routine. We have started to develop statistical emulators using Gaussian processes and Graph Neural Network for accelerating the computation of the forward physics models. We demonstrate the computational costs can be reduced by about several orders of magnitude, with hardly any loss in accuracy, 
![Alt Text](http://haogao.github.io/images/hg_surrogate.png)

### Electrophysiology and EM coupling


### PhD research on carotid plaque modellig

