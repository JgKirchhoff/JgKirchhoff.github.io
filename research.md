---
title: Research 
layout: default
---

## Research Overview
My research currently sits at the intersection of advanced composite processing and computational science, particularly focusing on inverse problems and outer-loop settings. Through the utilization of cutting-edge computational tools, my aim is threefold: first, to deepen our understanding of the fundamental science behind manufacturing methods; second, to develop real-time monitoring and certification techniques for performance; and third, to optimize the manufacturing process itself. My work is supported by a prestigious NASA NSTGRO fellowship entitled "Data-Driven Modeling and Optimization of Robotic In-situ Consolidation of Thermoplastic Composites," despite my current emphasis being more on model-driven methods rather than data-driven ones. However, I am eager to strike a balance between these two philosophies as my research progresses. Frankly, I love this interaction of the computational science motivating a deep understanding of the physics while the manufacturing settings drives a difficult computational challenge for on-line predictive tools. 

## Thermoplastic Composites (Fusion Bonding)

<img src="images/fiber infiltration v7.1.png" />


Fusion bonding in thermoplastic composites is a key physics to understand in the context of fast-processing (automated fiber placement, thermoforming) and welding/joining. Firstly, the lamina are brought together where local (micro-level) surface roughness prevents bonding. Intimate contact is the phenomena of the lamina forming sufficient resin-resin surface to allow bonding. Immediately, upon resin-resin interfaces forming, polymer chains migrate across the interface (nano-level). This is known as interdiffusion or healing. Lastly, upon cooling, the polymer chains solidify and may crystallize. A goal of mine is to understand the intricacies of fusion bonding, namely the interlinking of the three physics, and then understand how we can take advantage during manufacturing. My first paper on the subject investigates the importance of resin percolation in intimate contact formation which leads to resin-rich interfaces commonly found in AFP. 

## Inverse Problems & Digital Twins 

Often, we cannot directly observe the parameter of interest with sensors. Instead, we can measure observations of the state (i.e, temperature, displacement, etc.,) and through an inverse problem we infer the parameter of interest. I am particuarly interested in inverse problems where the parameters exist in high-dimensions, ie., full-field measurements. This is particularly useful for manufacturing where we want to discover non-conformoties and the parameter spaces needs to be large enough to support this. Unfortunately, this problem is highly ill-posed so we introduce regularization so that we can use a Newton system to solve the problem. An example of this is an algorithm we developed to infer fully spatial modulus behavior of materials using Digital Image Correlation. Our contribution is here being able to characterize heterogenous materials, non-destructively discover voids/non-conformoties and find modulus induced stress fields. 

<img src="images/overview_v2.pdf" />



