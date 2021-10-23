---
layout: post
title:  "Smart wheeler navigation optimization techniques"
date:   2021-10-23
categories: robotics navigation
---

For the last few years, researchers and students of three universities of Quebec,  ́Ecole Polytechnique, Université de Montréal and McGill University, have been working on the creation of an Intelligent Powered Wheelchair (IPW). Thanks to their work, a wheelchair equiped with sensors and using a wide range of modules enabling the chair to do numerous automatic tasks became a reality. The IPW can therefore be considered as an example of a mobile robot.

Many possible improvements still can be performed in spite of the very advanced state of the wheelchair. The global navigation is based on a simultaneous localization and mapping (SLAM) algorithm; the GMapping algorithm that uses a perception model conceved for lasers detections only and that is therefore under the required level of efficiency when mapping is held in environments containing transparent obstacles such as glass walls. Besides, the SLAM algorithm used is, as any other SLAM solution, based on a mapping strategy that imposes the environment exploration. Thus, our work’s objectives are: First, to propose a solution to the
transparent objects problem and second, to suggest a new alternative to the old exploration based strategy by exloiting blueprints to generate occupancy grid maps automatically.

This report shows how we achieve these objectives through the study and analysis of
the available SLAM algorithm and the conception of our solutions. In the first solution, we introduce a component that takes sonars detections as inputs and that draws in real time, based on a sonar perception model, the missing transparent objects on the GMapping map. In our second solution, a new technique makes use of an algorithm that analyses the layers of CAD blueprints given in a DXF file format in order to extract the important elements used for grids construction.

Our algorithms proved to be efficient. In fact, we managed to get complete maps showing the transparent obstacles at the right spots. We managed then to make use of the sonar’s capability to see transparent objects without causing the decrease of the GMapping performance in both mapping with laser data and localisation. On the other hand, we managed to automatically build occupancy grid maps from blueprints. The built maps proved precise when used successfully in the wheeler’s navigation system. We have now a faster and cheaper mapping solution for the IPW.

<!-- Add icon library -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<!-- Auto width -->
<a class="btn" target="_blank" href="https://publications.polymtl.ca/1482/1/2014_GhaziMajdoub.pdf"><i class="fa fa-download"></i> Download full thesis in PDF format</a>

__Note__: Full thesis document is in French.