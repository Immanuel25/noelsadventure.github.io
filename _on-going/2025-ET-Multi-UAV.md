---
title: "An Event-Triggered Multi-UAV Coordination Scheme for Simultaneous Tracking and Pursuit of Multiple Moving Targets"
collection: on-going
category: manuscripts
permalink: /publication/2025-ET-Multi-UAV
excerpt: 'This paper proposes event-triggered cooperative localization and pursuit control methods of multiple unmanned aerial vehicles (UAVs) for the purpose of tracking and monitoring multiple moving target vessels in a maritime patrol scenario.'
date: 2025-12-31
venue: 'IEEE Access'
paperurl: 'http://Immanuel25.github.io/noelsadventure.github.io/files/2025-ET-Multi-UAV.pdf'
# slidesurl: 'https://ieeexplore.ieee.org/abstract/document/10824351'
# bibtexurl: 'http://Immanuel25.github.io/noelsadventure.github.io/files/2025-ET-Multi-UAV.bib'
---
This paper proposes event-triggered cooperative localization and pursuit control methods of multiple unmanned aerial vehicles (UAVs) for the purpose of tracking and monitoring multiple moving target vessels in a maritime patrol scenario. 
In the proposed method, each UAV is assumed to be equipped with an optical sensor, which is used to measure its distances while moving in the air to the target vessels moving on the water surface.
In particular, each UAV combines its obtained measurements with those of other UAVs to be subsequently processed using an event-triggered distributed extended Kalman filter algorithm to obtain its estimates of target vessels' positions. 
The UAVs then use the position estimates of the targets to construct dynamic convex hulls that connect all of the detected moving target vessels. 
The multi-UAV tracker system then generates spatio-temporal reference path curves using cycloid-type trajectories with a formation geometry that is adapted in such a way to cover/contain the constructed convex hulls of the target vessels. 
%A  which combines state estimates from different trackers is also used to improve the accuracy of the targets' position estimate. 
Based on the generated reference path, a distributed cooperative control law based on the moving path following approach is finally proposed to maintain tracker-target's relative geometry that guarantee accurate tracking of the moving vessels. 
Extensive simulation results are presented to demonstrate the effective performance, computational efficiency, and scalability of the proposed scheme.

Index Terms—Range-based localization, target pursuit, multi-tracker, multi-target, moving path following