---
title: "Disease Simulator"
layout: archive-no-title
excerpt: "An ODE disease simulator written in MATLAB, with a GUI to tune disease parameters <br><img src='/images/diseasesmall.jpg' width='350' height='350'/>"
collection: portfolio
---

# Disease Simulator

## View on GitHub &nbsp; <a href="https://github.com/ggdurrant/Disease-Sim"> <img src="https://github.com/favicon.ico" alt="GitHub" width="25"> </a>
------

This disease simulator uses a system of ordinary differential equations, which can be found in Durrant_George_disease.m, to simulate the progression of a disease and the effects on a sample population. A GUI was written, with the design provided in Durrant_George_GUI.fig, and the implementation in Durrant_George_GUI.m, which allows parameters of the disease and population to be adjusted. 

The population state after a specified time interval is output, as well as a graph showing healthy, infected, immune, and deceased populations. An example can be seen:

<!-- ![deadly](/images/deadly.JPG) -->

<img src='/images/deadly.JPG' width='600' height='600'/>

Starting population parameters can be adjusted, as well as population birth and death rates. The disease parameters of transmission rate, fatality rate, and duration can be edited and the simulation re-run. There are also several presets of starting parameters which can be seen in the drop down menu:

<!-- ![preset](/images/preset.JPG) -->

<img src='/images/preset.JPG' width='600' height='600'/>

