---
title: "Design and Experimental Validation of Closed-Form CBF-Based Safe Control for Stewart Platform Under Multiple Constraints"
collection: on-going
category: manuscripts
permalink: /publication/2025-Stewart-Platform-CBF
excerpt: 'This paper presents a closed-form solution of a Control Barrier Function (CBF) formulation for ensuring safety in the operation of a Stewart platform prototype.'
date: 2025-12-31
venue: 'Unknown'
paperurl: 'http://Immanuel25.github.io/files/2025-Stewart-Platform-CBF.pdf'
# slidesurl: 'https://ieeexplore.ieee.org/abstract/document/10824351'
# bibtexurl: 'http://Immanuel25.github.io/files/2025-Stewart-Platform-CBF.bib'
---
This paper presents a closed-form solution of a Control Barrier Function (CBF) formulation for ensuring safety in the operation of a Stewart platform prototype.
The proposed controller simultaneously enforces position and velocity constraints, using an energy-based CBF for position safety and a standard CBF for velocity safety.
Instead of solving the associated safety Quadratic Program (QP) at each control step, an explicit closed-form solution is derived to compute the safe control inputs, significantly reducing computational cost and enabling real-time implementation.
Simulation results demonstrate that the closed-form and QP-based methods yield identical control actions and successfully guarantee safe operation.
Experimental validation on the developed prototype further confirms the suitability of the closed-form approach for real-time deployment in safety-critical parallel robotic systems.

Index Terms—closed-form solution, Control Barrier Function, Stewart platform prototype, Experimental validation